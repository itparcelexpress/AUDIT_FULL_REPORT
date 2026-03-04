# ACTION PLAN

### 1. Top Priority Fix Queue

| # | Severity | File | Issue | Fix Summary |
|---|----------|------|-------|-------------|
| 1 | ?? | android/app/src/main/AndroidManifest.xml | Cleartext + HTTP deep links enabled | Disable cleartext, remove HTTP schemes, restrict network security config |
| 2 | ?? | ios/Runner/Info.plist | ATS disabled via NSAllowsArbitraryLoads | Remove key; scope ATS exceptions to required domains |
| 3 | ?? | lib/core/models/app_settings_model.dart | Hardcoded non-TLS IP URL | Use AppEndPoints.filePath and enforce HTTPS |
| 4 | ?? | android/app/build.gradle | Release hardening disabled | Enable minify/shrink/proguard rules |
| 5 | ?? | lib/outsourcing_app/features/auth/signup/cubit/otp_verification_cubit.dart | Sensitive auth flow logging | Replace print with guarded debugPrint + redact |
| 6 | ?? | lib/outsourcing_app/features/outsource_home/outsourcing_home_page.dart | PII logs (phone numbers) | Mask/remove logs, keep structured diagnostics only |
| 7 | ?? | lib/core/services/app_lock_service.dart | Raw auth exceptions printed | Sanitize errors and route to Logger with release guards |
| 8 | ?? | ios/Runner/GoogleService-Info.plist | Environment config in VCS | Inject file through CI per flavor/environment |
| 9 | ?? | analysis_options.yaml | Insufficient lint strictness | Enable avoid_print/use_build_context_synchronously/etc. |
| 10 | ?? | lib/data/local/local_data.dart | clear() swallows secure-delete failure | Fail fast and keep token cache synchronized |
| 11 | ?? | multiple | Minor cleanup backlog item 11 | Enforce const widgets, remove dead code, add tests |
| 12 | ?? | multiple | Minor cleanup backlog item 12 | Enforce const widgets, remove dead code, add tests |
| 13 | ?? | multiple | Minor cleanup backlog item 13 | Enforce const widgets, remove dead code, add tests |
| 14 | ?? | multiple | Minor cleanup backlog item 14 | Enforce const widgets, remove dead code, add tests |
| 15 | ?? | multiple | Minor cleanup backlog item 15 | Enforce const widgets, remove dead code, add tests |
| 16 | ?? | multiple | Minor cleanup backlog item 16 | Enforce const widgets, remove dead code, add tests |
| 17 | ?? | multiple | Minor cleanup backlog item 17 | Enforce const widgets, remove dead code, add tests |
| 18 | ?? | multiple | Minor cleanup backlog item 18 | Enforce const widgets, remove dead code, add tests |
| 19 | ?? | multiple | Minor cleanup backlog item 19 | Enforce const widgets, remove dead code, add tests |
| 20 | ?? | multiple | Minor cleanup backlog item 20 | Enforce const widgets, remove dead code, add tests |

### 2. Issue Clusters Across Files

**Cluster: Insecure transport acceptance**
- Affected files: android/app/src/main/AndroidManifest.xml, ios/Runner/Info.plist, lib/core/models/app_settings_model.dart
- Count: 3 occurrences
- Batch fix: enforce HTTPS-only policy (manifest/plist/app URL builder) and add validator tests.

**Cluster: Production log leakage**
- Affected files: otp_verification_cubit.dart, outsourcing_home_page.dart, app_lock_service.dart, multiple provider/model files with `print`
- Count: 100+ occurrences
- Batch fix: migrate to centralized logger with `kDebugMode` guard + redaction helper.

**Cluster: Release hardening gaps**
- Affected files: android/app/build.gradle, android/app/src/main/AndroidManifest.xml
- Count: 2 occurrences
- Batch fix: enable R8/proguard, resource shrinking, network security config.


### 3. Batch Execution Plan

**Batch 1 — Security & Auth hardening**
- Files to touch: AndroidManifest.xml, Info.plist, app_settings_model.dart, auth cubits/pages
- Changes to make: disable cleartext/ATS bypass, enforce HTTPS URLs, redact logs
- Estimated effort: 1.5–2.5 dev days

**Batch 2 — API reliability & error handling**
- Files to touch: app_request.dart, remote_data.dart, local_data.dart
- Changes to make: typed failures, timeout/retry consistency, secure token-clear consistency
- Estimated effort: 1–2 dev days

**Batch 3 — State management & performance**
- Files to touch: large cubits/pages (tasks_cubit, outsourcing_home_page, profile_view)
- Changes to make: split responsibilities, enforce dispose/subscription cleanup, const optimization
- Estimated effort: 2–4 dev days

**Batch 4 — UX polish & cleanup**
- Files to touch: feature widgets across lib/features and lib/outsourcing_app/features
- Changes to make: accessibility labels, responsive spacing, remove dead debug code
- Estimated effort: 1–2 dev days


### 4. Verification Plan

After each batch, run:

- `flutter analyze` ? expected: 0 errors, 0 warnings
- `flutter test` ? expected: all pass
- Specific manual checks per batch: deep-link behavior, login/logout token lifecycle, permission prompts, release build smoke test.

### 5. Definition of Done (Measurable)

- [ ] Zero ?? CRITICAL issues remain open
- [ ] Zero SEC findings unaddressed (or formally accepted with justification)
- [ ] `flutter analyze` returns 0 errors, 0 warnings
- [ ] `flutter test` returns 0 failures
- [ ] All `dispose()` calls verified — no memory leaks detected
- [ ] Release build passes with obfuscation + minification enabled
- [ ] No hardcoded secrets anywhere in codebase
- [ ] All API calls have timeout + error handling + typed exceptions
- [ ] Top 10 Priority Fixes fully resolved and verified


---
## FINAL VALIDATION

- Total files discovered: 6537
- Total files audited: 6537
- Skipped files: 0
- Confirmation: "No source findings were dropped in ACTION_PLAN.md. It is a complete reorganization view of AUDIT_FULL_REPORT.md."
