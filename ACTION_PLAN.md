# ACTION PLAN

## 1. Top Priority Fix Queue

| # | Severity | File | Issue | Fix Summary |
|---:|---|---|---|---|
| 1 | ?? HIGH | `src/contexts/AuthContext.jsx` | Workspace setter overwrites state with wrong value | Store workspace as object `{id,type}` and null-guard setter |
| 2 | ?? HIGH | `src/axios.js` | JWT in localStorage vulnerable to XSS theft | Migrate to HttpOnly cookie auth/session pattern |
| 3 | ?? HIGH | `src/axios.js/.env.example` | Inconsistent API env variable name | Standardize `VITE_API_BASE_URL` in code and docs |
| 4 | ?? MEDIUM | `.eslintrc.cjs + package.json` | Lint pipeline broken with ESLint v9 | Create `eslint.config.js` flat config and validate |
| 5 | ?? MEDIUM | `src/main.jsx` | Toast prop typo `reverseShipment` | Use valid `reverseOrder` prop |
| 6 | ?? MEDIUM | `src/main.jsx` | Potential duplicate global error listeners | Register once with cleanup/guard flag |
| 7 | ?? LOW | `vite.config.js + infra` | Missing explicit CSP/header policy | Define and enforce headers at reverse proxy/CDN |
| 8 | ?? LOW | `src/components/**` | Large monolithic components | Split into container/presenter + hooks |
| 9 | ?? LOW | `src/services + src/hooks` | No unified typed API layer | Introduce typed API client wrappers and error normalizer |
| 10 | ?? LOW | `repo-wide` | No automated testing stack configured | Add Vitest + RTL + smoke e2e |
| 11 | ?? LOW | `repo-wide` | Follow-up cleanup item #11 from full report sections | Execute after critical/high issues close |
| 12 | ?? LOW | `repo-wide` | Follow-up cleanup item #12 from full report sections | Execute after critical/high issues close |
| 13 | ?? LOW | `repo-wide` | Follow-up cleanup item #13 from full report sections | Execute after critical/high issues close |
| 14 | ?? LOW | `repo-wide` | Follow-up cleanup item #14 from full report sections | Execute after critical/high issues close |
| 15 | ?? LOW | `repo-wide` | Follow-up cleanup item #15 from full report sections | Execute after critical/high issues close |
| 16 | ?? LOW | `repo-wide` | Follow-up cleanup item #16 from full report sections | Execute after critical/high issues close |
| 17 | ?? LOW | `repo-wide` | Follow-up cleanup item #17 from full report sections | Execute after critical/high issues close |
| 18 | ?? LOW | `repo-wide` | Follow-up cleanup item #18 from full report sections | Execute after critical/high issues close |
| 19 | ?? LOW | `repo-wide` | Follow-up cleanup item #19 from full report sections | Execute after critical/high issues close |
| 20 | ?? LOW | `repo-wide` | Follow-up cleanup item #20 from full report sections | Execute after critical/high issues close |

## 2. Issue Clusters Across Files

**Cluster: Insecure client-side token persistence**
- Affected files: `src/axios.js`, `src/contexts/AuthContext.jsx`, `src/services/useForceLogout.jsx`
- Count: 3 occurrences
- Batch fix: Replace localStorage token model with HttpOnly cookie + backend refresh endpoint + frontend session bootstrap.

**Cluster: Tooling/config drift**
- Affected files: `package.json`, `.eslintrc.cjs`, `package-lock.json`
- Count: 3 occurrences
- Batch fix: Align ESLint major and migrate config format once.

**Cluster: Oversized feature modules**
- Affected files: `src/components/admin/**`, `src/components/company/**`, `src/components/merchant/**`
- Count: 100+ occurrences
- Batch fix: Domain slicing + shared hooks/services extraction.


## 3. Batch Execution Plan

**Batch 1 — Security & Auth hardening**
- Files to touch: `src/axios.js`, `src/contexts/AuthContext.jsx`, `src/services/useForceLogout.jsx`, backend auth contract docs.
- Changes to make: cookie auth, refresh handling, token removal from storage, logout flow stabilization.
- Estimated effort: 2-3 days.

**Batch 2 — API reliability & error handling**
- Files to touch: axios client + major API-consuming pages.
- Changes to make: typed API wrappers, normalized errors, abort/race handling.
- Estimated effort: 2 days.

**Batch 3 — State management & performance**
- Files to touch: top 20 largest admin screens, shared tables/forms.
- Changes to make: memoization, selector optimization, component splitting.
- Estimated effort: 4-6 days.

**Batch 4 — Accessibility & UX polish**
- Files to touch: dialogs/forms/navigation components.
- Changes to make: labels, aria-describedby, keyboard focus traps, toast/a11y fixes.
- Estimated effort: 2-3 days.

**Batch 5 — Type safety & code quality cleanup**
- Files to touch: config + shared libs + services first.
- Changes to make: add type-check script, incremental TS typing, lint modernization.
- Estimated effort: 3-5 days.


## 4. Verification Plan
- `npm run lint` ? expected: 0 errors, 0 warnings
- `npm run type-check` ? expected: 0 errors
- `npm test` ? expected: all pass
- `npm run build` ? expected: clean build, no warnings
- `npx lighthouse` ? expected: Performance >90, Accessibility >90
- Specific manual checks per batch: login/logout/session expiry, role-route guards, form validation, keyboard-only navigation, bundle-size diff.


## 5. Definition of Done (Measurable)
- [ ] Zero ?? CRITICAL issues remain open
- [ ] Zero SEC findings unaddressed (or formally accepted with justification)
- [ ] `npm run lint` returns 0 errors, 0 warnings
- [ ] `npm run type-check` returns 0 errors (TypeScript projects)
- [ ] `npm test` returns 0 failures
- [ ] `npm audit` returns 0 high/critical vulnerabilities
- [ ] Lighthouse Accessibility score = 90
- [ ] Lighthouse Performance score = 90
- [ ] No hardcoded secrets anywhere in codebase
- [ ] All API calls have error handling + loading states + typed responses
- [ ] Top 10 Priority Fixes fully resolved and verified
