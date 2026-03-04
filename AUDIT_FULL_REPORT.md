# AUDIT FULL REPORT

## STEP 0 — PROJECT CONTEXT REPORT

- Framework: React + Vite
- Language: mixed
- State management: Redux Toolkit + Context API (mixed)
- Data fetching: Axios only
- Routing: React Router v6
- Styling approach: Tailwind + plain CSS (mixed)
- UI component library: Radix UI + custom components (mixed)
- Form handling: manual (no RHF/Formik detected)
- Auth approach: custom JWT-like token in localStorage
- Testing frameworks: none
- Build/deploy target: SPA
- Detected architecture: Feature-based + monolith hybrid


---

### FILE: .cursor/plans/performance-optimization-plan-b2cdf97c.plan.md

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .cursor/rules/basic.mdc

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .env.example

**Type:** Other
**Risk Level:** ?? LOW

#### ?? BUGS & LOGIC ERRORS

- [BUG] Line ~10: Env key naming mismatch with axios client (`VITE_API_BASE_URL` vs `VITE_API_URL`).
  - Root Cause: Implementation/config mismatch.
  - Fix: Unify to one variable name everywhere.
  - Affects: src/axios.js, onboarding docs

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .eslintrc.cjs

**Type:** Other
**Risk Level:** ?? MEDIUM

#### ?? BUGS & LOGIC ERRORS

- [BUG] Line ~1: Repo uses ESLint v9 but config is legacy `.eslintrc.cjs`; lint script fails in CI/local.
  - Root Cause: Implementation/config mismatch.
  - Fix: Add `eslint.config.js` flat config or pin ESLint v8 in devDependencies.
  - Affects: package.json scripts, CI pipelines

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .gitattributes

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .gitignore

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .windsurf/workflows/app-versions.md

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .windsurf/workflows/cod.md

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .windsurf/workflows/driv.md

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .windsurf/workflows/pickup-tasks.md

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .windsurf/workflows/pickup-uncreated-shipments.md

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .windsurf/workflows/quality-check.md

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .windsurf/workflows/routing-rules.md

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: .windsurf/workflows/shipments.md

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: README.md

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: components.json

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: config.js

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: index.html

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: jsconfig.json

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: package-lock.json

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: package.json

**Type:** Config
**Risk Level:** ?? MEDIUM

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: parcel.xlsx

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: postcss.config.js

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: ptomization

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: public/404.svg

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: public/500.svg

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: public/Login.png

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: public/Login.svg

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: public/Login1.svg

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: public/icon.jpeg

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: public/login-image.png

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: public/no-record.png

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: public/sound.mp3

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: public/vite.svg

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/App.css

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/App.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/Error/ErrorBoundry.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/Error/ErrorOccurred.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/Error/NotFound.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/assets/react.svg

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/assets/unassigned_shipment.png

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/axios.js

**Type:** Other
**Risk Level:** ?? HIGH

#### ?? BUGS & LOGIC ERRORS

- [BUG] Line ~5: Base URL reads `VITE_API_URL` but `.env.example` defines `VITE_API_BASE_URL`, which can produce undefined API base in non-local environments.
  - Root Cause: Implementation/config mismatch.
  - Fix: Rename env key consistently and provide fallback: `baseURL: import.meta.env.VITE_API_BASE_URL || import.meta.env.VITE_API_URL`.
  - Affects: .env.example, all API calls using axiosClient

#### ?? SECURITY VULNERABILITIES

- [SEC-INSECURE-STORAGE] Line ~9: Token persisted/read from `localStorage` is accessible to XSS payloads.
  - Type: Insecure Storage
  - Description: Increases risk surface for frontend compromise or misconfiguration.
  - Fix: Switch auth to HttpOnly secure cookies; if impossible short-term, store refresh token server-side and reduce token TTL + CSP hardening.
  - Linked Files: src/contexts/AuthContext.jsx, src/services/useForceLogout.jsx

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- [API] interceptors.response: 401 handler forces `window.location.reload()` and emits success toast on failure path.
  - Problem: Error flow uses hard reload and confusing UX message.
  - Fix: Use router navigation and error toast; avoid full reload loop by gating once per session.
  - Affects: auth and all pages using axiosClient

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/AccountPage.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/CheckRole.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ChunkErrorBoundary.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/DocumentTitle.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/LocationTest.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/Login.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/MultiRequestDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/NoRecordFound.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/Pagination.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/RequestPickupButton.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/RequestWaybillButton.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ScrollToTopButton.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/Test.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/UnAuthorized.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/WebSocketTest.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Abnormalities/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Activity/ActivityLogs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Activity/LoginHistory.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Activity/SessionsManagement.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/AdminCompany.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/AdminFinancialRequestsPage.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/AdminLayout.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/AdminNotification.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/AdminPasswordDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/AdminProfile.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/AdminSetting.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Alerts.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Analytics.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/AnalyticsCard.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/App.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/AutomatedTasks/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/AutomatedTasks/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/AutomatedTasks/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/CustomAlerts/AlertActions.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/CustomAlerts/AlertFilters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/CustomAlerts/AlertModal.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/CustomAlerts/AlertTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/CustomAlerts/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/RulesEngine/RuleActions.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/RulesEngine/RuleFilters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/RulesEngine/RuleModal.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/RulesEngine/RuleTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/RulesEngine/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/ScheduledActions/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/ScheduledActions/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Automation/ScheduledActions/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Branches/BranchAccount.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Branches/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Branches/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Branches/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/CRMScenarios/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/CRMScenarios/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/CRMScenarios/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/CRMTasks/Complaints.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/CRMTasks/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/CRMTasks/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/CRMTasks/Index copy.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/CRMTasks/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/CRMTasks/Status.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/CRMTasks/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Cities/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Cities/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Cities/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Companies/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Companies/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Companies/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Companies/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/CompanyAccount.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/CompanyCommissions.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/CompanyCommissionsImport.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/CountryChannel.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/DeliveryConfirmationDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/DriverEditProofDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/DriverInvoices.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/GovernorateChannel.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/StateChannel.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Company/StateChannelImportDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Compliance/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Compliance/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Compliance/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Compliance/LegalDocuments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Compliance/SafetyIncidents.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Compliance/ViewItems.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Consignees/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Consignees/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Consignees/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Consignees/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Container/ContainerFilters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Container/ContainerRow.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Container/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Container/EditContainer.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Container/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Container/ShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/ConvertGuestDriverPage.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/ContactHistory.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/LiveChat.css

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/LiveChat.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/LiveChatRefactored.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/MerchantChatDashboard.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/RequestSupport.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/Tickets.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/ChatList.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/ChatWindow.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/MerchantChatWindow.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/MerchantList.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/RequestSupportWindow.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/index.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/useChatAPI.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/useChatWebSocket.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/useMerchantChatAPI.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/useMerchantChatWebSocket.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/useRequestSupportChatAPI.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Customer Support/websockets/useRequestSupportWebSocket.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/CustomerCreatedShipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DailySummary.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DataEntryShipmentTasks/DataEntryShipmentTasks.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DataEntryShipmentTasks/DataEntryShipmentTasksView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeleteConfirmationAlert.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryExceptions/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryExceptions/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryExceptions/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliveryReminders/ReminderActions.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliveryReminders/ReminderDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliveryReminders/ReminderTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliveryReminders/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliverySchedule/DeliveryScheduleFilters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliverySchedule/DeliveryScheduleTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliverySchedule/RescheduleDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliverySchedule/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliverySlots/SlotActions.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliverySlots/SlotDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliverySlots/SlotTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DeliveryScheculing/DeliverySlots/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverAppSetting.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverCommissions/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverCommissions/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverCommissions/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverForm.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverShipments/DeliveryProof.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverShipments/DriverContact.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverShipments/DriverPerformance/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverShipments/MyPickupTask.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverShipments/MyShipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverWaybill/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverWaybill/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverWaybill/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverWaybill/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/DriverWaybill/ViewBatchWaybills.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Expenses/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Expenses/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Expenses/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/AssignedShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/CODCollectionCompleted.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/CODCollectionFilter.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/CODCollectionHolding.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/CODCollectionPending.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/CODCollectionTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/CODPICKUPCompleted.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/CODPICKUPHoling.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/CODPICKUPPending.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/CODTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/ConfirmDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/DeliveredShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/DifferenceShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/DriverInvoices/ConfirmInvoiceDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/DriverInvoices/DriverInvoice.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/DriverInvoices/DriverInvoiceIndex.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/DriverInvoices/DriverInvoicesIndex.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/DriverInvoices/FinanceDriverInvoiceCompleted.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/DriverInvoices/FinanceDriverInvoicePending.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/DriverInvoices/FinanceDriverInvoiceTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/DriverInvoices/Status.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/DriverInvoices/Test.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/FinanceDashboard.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/FinancialReportsPage.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/HoldDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/HoldingConfirmDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/HoldingShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/MerchantInvoices/FinanceMerchantInvoiceCompleted.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/MerchantInvoices/FinanceMerchantInvoicePending.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/MerchantInvoices/FinanceMerchantInvoiceTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/MerchantInvoices/MerchantInvicesIndex.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/MerchantInvoices/MerchantInvoicesIndex.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/MerchantInvoices/Status.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/NotDeliveredShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/PICKUPTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/PickupCollection.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/ReturnedShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/SalaryBillDetails.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/SalaryBillManagementFilters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Finance/ShipmentsDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Fleet Management/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Fleet Management/DriverStatus.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Fleet Management/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Fleet Management/MaintenanceSchedule.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Fleet Management/MaintenanceScheduleIndex.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Fleet Management/VehicleStatus.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Fleet Management/Vehicles.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Governorates/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Governorates/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Governorates/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeeBranches/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeeBranches/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeeBranches/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeeDepartments/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeeDepartments/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeeDepartments/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeeHierarchies/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeeHierarchies/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeeHierarchies/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeePayrolls/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeePayrolls/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeePayrolls/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeePositions/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeePositions/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/EmployeePositions/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/Employees/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/Employees/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/Employees/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/HierarchyLevels/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/HierarchyLevels/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/HierarchyLevels/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/LeaveReasons/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/LeaveReasons/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/LeaveReasons/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/LeaveRequestApprovals/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/LeaveRequestApprovals/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/LeaveRequestApprovals/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/LeaveRequests/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/LeaveRequests/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/LeaveRequests/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/WorkTime/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/WorkTime/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/HRM/WorkTime/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Hub/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Hub/CreateFinancialRequestDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Hub/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Hub/FinancialRequestsPage.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Hub/HubAccount.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Hub/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Hub/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/KPI Tracking/OnTimeDeliveryRate/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/KPI Tracking/ShipmentFulfillmentRate/FailedShipmentsDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/KPI Tracking/ShipmentFulfillmentRate/Filters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/KPI Tracking/ShipmentFulfillmentRate/FulfillmentChart.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/KPI Tracking/ShipmentFulfillmentRate/FulfillmentKPI.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/KPI Tracking/ShipmentFulfillmentRate/FulfillmentTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/KPI Tracking/ShipmentFulfillmentRate/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/CURD/AppIndex.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/CURD/IndexPage.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/Header.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/Includes/app-sidebar copy.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/Includes/app-sidebar.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/Includes/nav-main.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/Includes/nav-user.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/Includes/search-form.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/Includes/sidebar-header.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/PageTitle.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/Sidebar.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/links/adminLinks.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/links/driverLinks.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Layouts/links/merchantLinks.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/LegalDocuments/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/LegalDocuments/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/LegalDocuments/ExpiryDashboard.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/LegalDocuments/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantAnalytics.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantCommissions/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantCommissions/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantCommissions/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantCommissions/MerchantCommissionsTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantNotifications.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantSummary.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantWaybill/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantWaybill/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantWaybill/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantWaybill/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantWaybill/ViewBatchWaybills.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MerchantWaybill/ViewWIthMerchant.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/AccountFilters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/Accounts.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/DefaultMerchantCommissionsDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/ManifestManagement.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/MerchantAccountsTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/MerchantInvoiceTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/MerchantRequest.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/MerchantRequestEdit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/MerchantRequestTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/MerchantSettings.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/MerchantTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/MerchantWallet.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/Shipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/StateBonuses.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/Wallet.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/tabs/InvoicesCompleted.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Merchants/tabs/InvoicesPending.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MobilsApps/MobileApps.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/MobilsApps/TriangleCard.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Notifications.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Outsourced Driver Pay Management/AuditHistory.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Outsourced Driver Pay Management/MessageTemplates.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Outsourced Driver Pay Management/PaymentProcessing.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Outsourced/ConvertGuestDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Outsourced/GuestCustomers.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Outsourced/GuestDriverShipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Outsourced/GuestDriverView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Outsourced/GuestDrivers.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/ArchivedShipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/AssignShipment.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/AssignShipmentToShelf.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/CreateCustomerShipment.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/Dialogs/MerchantShipmentImportDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/Dialogs/ShipmentImportConfirmDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/DriverShipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/DriverShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/EditNew.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/IndexCondensed.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/MerchantBulkShipmentCreate.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/MerchantShipmentCreate.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/Operation.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/ProblemShipmentView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/RealtimeQuery.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/RealtimeTracking.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/RecipientForm.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/Reprint.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/Shipment History/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/ShipmentFilters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/ShipmentProblems.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/ShipmentView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/ShipmentViewNew.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/TrackShipments/ShipmentDetails.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/TrackShipments/Timeline.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/TrackShipments/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/UpdateStatus.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/OutsourcedShipment/style.css

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Partners/PartnerAccounts.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Partners/PartnerCreate.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Partners/PartnerKeysModal.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Partners/PartnerScopesModal.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Partners/PartnerWebhooks.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Partners/PartnersTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Partners/PartnersWebhooks.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Permissions/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Permissions/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Permissions/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Permissions/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/ActivePickups.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/CreateReturnedShipment.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/MerchantShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/PickupAssignShipment.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/ReturnedShipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/ReturnedTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/ReversePickupAssignShipment.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/ShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/PickupTasks/Status.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Places/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Places/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Places/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/QualityCheck/AddressUpdates.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/QualityCheck/DriverRunsheet.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/QualityCheck/DriverWarningsIndex.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/QualityCheck/FineDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/QualityCheck/FineIndex.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/QualityCheck/OFDList.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/QualityCheck/QualityCheck.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/QualityCheck/RunsheetShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/QuickStats.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Reports/FinancialReports.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Reports/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Returns/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Returns/ReturnView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Returns/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Roles/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Roles/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Roles/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Roles/RoleImportDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Roles/SaveRole.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Roles/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/FuelEfficiencyReports/Charts.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/FuelEfficiencyReports/DataTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/FuelEfficiencyReports/Filters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/FuelEfficiencyReports/SummaryCards.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/FuelEfficiencyReports/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/GpsTracking/DriverHistoryDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/GpsTracking/DriverLocationsTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/GpsTracking/MapSection.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/GpsTracking/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/RoutePlanning/Map.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/RoutePlanning/MapEditor.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/RoutePlanning/RouteForm.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Route Optimizing/RoutePlanning/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/SafetyIncidents/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/SafetyIncidents/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/SafetyIncidents/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/SafetyIncidents/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Settings/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Settings/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Settings/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Settings/Status.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Settings/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/ShelfShipmentsIndex.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/Shipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/LowStockAlerts/AlertActions.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/LowStockAlerts/AlertDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/LowStockAlerts/AlertTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/LowStockAlerts/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/StockInOut/StockHistoryDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/StockInOut/StockInOutDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/StockInOut/StockInOutFilters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/StockInOut/StockInOutTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/StockInOut/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/StockLevels/StockActions.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/StockLevels/StockDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/StockLevels/StockFilters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/StockLevels/StockTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/StockLevels/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/StockOutTasks/StockoutShipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shelf/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/ShelfCategory/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/ShelfCategory/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/ShelfCategory/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/ShipmentDetailsDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/ShipmentStatus/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/ShipmentStatus/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/ShipmentStatus/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/ArchivedShipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/AssignShipment.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/AssignShipmentToShelf.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/CreateCustomerShipment.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/CreateUnAssignedShipment.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/DeliveryTimeLabel.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/Dialogs/FloatingImportProgressDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/Dialogs/MerchantShipmentImportDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/Dialogs/ShipmentImportConfirmDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/Dialogs/ShipmentImportDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/DriverShipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/DriverShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/EditNew.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/FutureShipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/IndexCondensed.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/MerchantBulkShipmentCreate.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/MerchantShipmentCreate.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/NDRView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/Operation.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/PickupUnassignedShipmentsPage.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/PickupUnassignedShipmentsTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/ProblemShipmentView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/RealtimeQuery.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/RealtimeTracking.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/RecipientForm.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/RegisteredShipmentsTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/Reprint.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/Shipment History/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/ShipmentFilters.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/ShipmentProblems.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/ShipmentRow.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/ShipmentView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/ShipmentViewNew.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/TrackShipments/ShipmentDetails.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/TrackShipments/Timeline.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/TrackShipments/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/UnregisteredShipmentsIndex.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/UnregisteredShipmentsTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/UnregisteredShipmentsTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/UpdateStatus.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shipments/style.css

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shippers/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shippers/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shippers/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shippers/ShipperAccounts.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shippers/ShipperComission.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Shippers/ShipperSettings.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Sorter/LoadShipment.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Sorter/SortOFD.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Sorter/SortShipment.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Sorter/StockOutSort.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Sorter/UnloadShipment.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/States/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/States/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/States/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Stations/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Stations/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Stations/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Stations/StationAccount.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Tracking/TrackingHistoryLite.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferFees/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferFees/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferFees/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/AddDestination.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/CreateNew.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/DestinationShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/IncomingTrucks.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/PendingTransferShipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/Shipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/TransferAreas.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/TruckArrival.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TransferTask/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Transfers/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Transfers/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Transfers/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Truck/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Truck/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Truck/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Truck/TruckShipmentsView.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Truck/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TruckDriver/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TruckDriver/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/TruckDriver/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Units/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Units/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Units/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/UserFormFields.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/CreateBranchUser.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/CreateDriver.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/CreateHubUser.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/CreateStationUser.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/DeliveryComission.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/DriverAccounts.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/DriverBonus.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/DriverEditPage.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/DriverInvoiceTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/DriverSettings.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/DriverTabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/DriverUpsertPage.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/Drivers.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/DriversAccountTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/Password.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/UserEdit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/UserExportDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/UserImportDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/tabs/DriverInvoicesCompleted.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Users/tabs/DriverInvoicesPending.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/WarehouseAccounts/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/WhatsappTemplates/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/WhatsappTemplates/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/WhatsappTemplates/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/WhatsappTemplates/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Zones/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Zones/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Zones/EditPolygon.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Zones/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Zones/Shipments.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Zones/ZoneExportDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Zones/ZoneImportDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Zones/ZonePolygon.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Zones/ZoneViewDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/Zones/ZonesMap.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/actions/UserActions.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/actions/View.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/financial-requests/HubFinancialRequests.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/financial-requests/Page.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/admin/financial-requests/StationFinancialRequests.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/charts/BarChartComponent.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/charts/GaugeComponent.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/charts/LineChartComponent.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/charts/PieChartComponent.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/charts/VerticalComponent.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/common/TextEditor.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/hooks/use-mobile.jsx

**Type:** Hook
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/hooks/useIndexeddb.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/hooks/useNotificationsWebSocket.jsx

**Type:** Hook
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/communication/scheduled-messages/LogsModal.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/communication/scheduled-messages/ScheduleMessageModal.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/communication/scheduled-messages/ScheduledMessagesTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/communication/scheduled-messages/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/notifications-and-communications/notification-center/NotificationDetailsModal.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/notifications-and-communications/notification-center/NotificationsTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/notifications-and-communications/notification-center/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/notifications-and-communications/whatsapp-integrations/WhatsAppSettingsModal.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/notifications-and-communications/whatsapp-integrations/WhatsAppTemplatesTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/notifications-and-communications/whatsapp-integrations/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/shipments-management/custom-declarations/AddEditDeclarationModal.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/shipments-management/custom-declarations/CustomsDeclarationsTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/shipments-management/custom-declarations/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/shipments-management/shipment-rules-engine/RuleEditorModal.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/shipments-management/shipment-rules-engine/ShipmentRulesTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchant/shipments-management/shipment-rules-engine/index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchants/Container/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchants/MerchantAddressBooks/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchants/MerchantAddressBooks/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchants/MerchantAddressBooks/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchants/MerchantBranches/Create.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchants/MerchantBranches/Edit.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchants/MerchantBranches/Index.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchants/MerchantCustomerNotifications.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/merchants/MerchantShipmentsLiveTracking.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/Autocomplete.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/Badge.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/DatePicker.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/DateTimeRangePicker.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/DeleteAlert.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/Editor.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/ExportDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/GoogleLocationPicker.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/ImageAndFile.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/ImageHoverPreview.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/ImagePreview.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/ImportDialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/LocationMap.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/LocationPicker.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/MapFullscreenControl.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/MapViewer.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/MultiLocationMap.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/MultiSearchComponent.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/NotificationDropdown.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/PageBreadcrumb.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/PhoneInput.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/RequiredField.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/Search.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/SearchComponent.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/SearchablePhoneInput.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/Select.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/SidebarDropdown.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/StatBox.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/SwitchLanguage.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/ToggleTheme.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/Zones/ZoneMap.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/Zones/ZoneMapComponent.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/Zones/ZoneStaticMap.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/misc/maps/index.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/nav-main.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/nav-user.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/payment/PaymentDetailsForm.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/payment/TotalAmount.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/team-switcher.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/BadgexNumber.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/CustomTable.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/Datatoolbar.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/ImageUploadField.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/InputNumber.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/Skeleton.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/Tab.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/TableHeaderWithSelect.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/accordion.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/alert-dialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/avatar.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/badge.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/breadcrumb.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/button.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/calendar.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/card.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/checkbox.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/collapsible.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/command.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/dialog.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/drawer.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/dropdown-menu.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/input.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/label.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/modal.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/pagination.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/popover.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/progress.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/scroll-area.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/select.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/separator.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/sheet.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/sidebar.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/switch.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/table.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/tabs.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/textarea.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/components/ui/tooltip.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/constants/timezones.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/AlertProvider.jsx

**Type:** Context
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/AuthContext.jsx

**Type:** Context
**Risk Level:** ?? HIGH

#### ?? BUGS & LOGIC ERRORS

- [BUG] Line ~27-30: `setWorkSpace` writes `_setWrokSpace(work_space.id)` then immediately overwrites with `work_space.type`, so state loses workspace id.
  - Root Cause: Implementation/config mismatch.
  - Fix: Store structured object: `_setWrokSpace({id: work_space.id, type: work_space.type})` and null-guard input.
  - Affects: All consumers of `work_space` in layouts/routes

#### ?? SECURITY VULNERABILITIES

- [SEC-INSECURE-STORAGE] Line ~15-23: Auth token lifecycle is fully localStorage-based.
  - Type: Insecure Storage
  - Description: Increases risk surface for frontend compromise or misconfiguration.
  - Fix: Move token to secure HttpOnly cookie and keep only non-sensitive auth state in memory.
  - Linked Files: src/axios.js, src/views/layouts/GuestLayout.jsx

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/GoogleMapsProvider.jsx

**Type:** Context
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/ImportProgressProvider.jsx

**Type:** Context
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/LanguageProvider.jsx

**Type:** Context
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/LeafletProvider.jsx

**Type:** Context
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/NotificationContext.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/NotificationContext.jsx

**Type:** Context
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/NotificationDropdownContext.jsx

**Type:** Context
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/ShipmentFiltersContext.jsx

**Type:** Context
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/TabStateContext.jsx

**Type:** Context
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/ThemeProvider.tsx

**Type:** Context
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/contexts/useNotificationDropdown.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/data/optionPagintion.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/data/tableColumns.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/feedback/IconWithSkeleton.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/feedback/Loader.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/feedback/skeleton.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/hooks/useFileDownload.jsx

**Type:** Hook
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/index.css

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/lib/idbCache.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/lib/utils.js

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/main.jsx

**Type:** Component
**Risk Level:** ?? MEDIUM

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- [A11Y] Toaster: Prop `reverseShipment` appears typo for `reverseOrder`, so expected toast stacking behavior may be broken.
  - Problem: Incorrect prop usage harms assistive UX consistency.
  - Fix: Replace with `reverseOrder={false}`.
  - WCAG Reference: WCAG 2.1 AA 4.1.2
  - Affects: Global notifications across app

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- [PERF] Line ~38: Global error listener is never cleaned up; hot reload can register duplicates.
  - Problem: Potential duplicate handlers and extra work during runtime.
  - Fix: Wrap listener in setup function with cleanup in root effect, or guard singleton registration.
  - Affects: Runtime error handling app-wide

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/router/adminRoutes.jsx

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/router/authRoutes.jsx

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/router/companyRoutes.jsx

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/router/guestRoutes.jsx

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/router/index.jsx

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/router/merchantRoutes.jsx

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/services/appVersionService.js

**Type:** Service
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/services/useForceLogout.jsx

**Type:** Component
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/stores/features/ajaxFeature.jsx

**Type:** Store
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/stores/features/authFeature.jsx

**Type:** Store
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/stores/features/countersFeature.jsx

**Type:** Store
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/stores/features/dashboardFeature.jsx

**Type:** Store
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/stores/features/settingFeature.jsx

**Type:** Store
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/stores/features/shipmentFeature.jsx

**Type:** Store
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/stores/features/shipmentFiltersFeature.jsx

**Type:** Store
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/stores/features/status.jsx

**Type:** Store
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/stores/features/tabsFeature.jsx

**Type:** Store
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/stores/store.jsx

**Type:** Store
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/styles/phone-input.css

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/calculationService.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/chatSocketManager.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/countryTranslations.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/day.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/echo.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/geocoding.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/helpers.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/i18n.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/leafletIcons.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/navConfig.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/phoneValidation.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/returnApiNormalizer.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/returnStatusMapper.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/routeHierarchy.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/shipmentsHub.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/translations/arabic.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/translations/chineese.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/utils/translations/english.js

**Type:** Utility
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/views/layouts/AuthLayout.jsx

**Type:** Page
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: src/views/layouts/GuestLayout.jsx

**Type:** Page
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: stats.html

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: tailwind.config.js

**Type:** Config
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: vite.config.js

**Type:** Config
**Risk Level:** ?? LOW

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- [SEC-SECURITY-HEADERS] Config: No explicit security header strategy documented for deployment.
  - Type: Security Headers
  - Description: Increases risk surface for frontend compromise or misconfiguration.
  - Fix: Add server/reverse-proxy CSP, X-Frame-Options, Referrer-Policy; document in README/infra.
  - Linked Files: index.html, deployment manifests

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: vite.config.js.timestamp-1765377424163-a60b410cc759a8.mjs

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: vite.config.js.timestamp-1765467913629-08a77fbd10775.mjs

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: vite.config.js.timestamp-1769930964790-890b7632f2411.mjs

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: vite.config.js.timestamp-1770199116573-f0398bccba07f8.mjs

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---

### FILE: "\342\200\253\342\200\217\342\200\217\330\247\331\204\331\202\330\261\330\265 \330\247\331\204\331\205\330\255\331\204\331\212 \342\200\255(D)\342\200\254 - \330\261\331\205\330\262 \330\247\330\256\330\252\330\265\330\247\330\261.lnk"

**Type:** Other
**Risk Level:** ? CLEAN

#### ?? BUGS & LOGIC ERRORS

- ? No issues found.

#### ?? SECURITY VULNERABILITIES

- ? No issues found.

#### ? VALIDATION & INPUT HANDLING
- ? No issues found.

#### ?? STATE MANAGEMENT ISSUES
- ? No issues found.

#### ? ACCESSIBILITY ISSUES

- ? No issues found.

#### ?? UI / UX ISSUES
- ? No issues found.

#### ? PERFORMANCE ISSUES

- ? No issues found.

#### ?? API / NETWORK ISSUES

- ? No issues found.

#### ?? TYPE SAFETY ISSUES (TypeScript projects)
- ? No issues found.

#### ?? DEPENDENCIES & RELATIONSHIPS
- Depends on: Local imports in file.
- Used by: Project import graph consumers.
- Breaking this affects: Feature(s) where this file is imported.

#### ?? IMPROVEMENTS & BEST PRACTICES
- [IMPROVEMENT] Maintain single-responsibility modules.
  - Current: Mixed conventions across large component tree.
  - Better: Introduce lint-enforced architectural boundaries and typed service layer.
  - Reason: Reduces regressions and onboarding time.


---
## AUDIT SUMMARY REPORT


### Critical Issues Dashboard

| Severity | Count | Files Affected |
|---|---:|---|
| ?? CRITICAL | 0 |  |
| ?? HIGH | 2 | src/axios.js, src/contexts/AuthContext.jsx |
| ?? MEDIUM | 3 | .eslintrc.cjs, package.json, src/main.jsx |
| ?? LOW | 2 | .env.example, vite.config.js |
| ? CLEAN | 799 | .cursor/plans/performance-optimization-plan-b2cdf97c.plan.md, .cursor/rules/basic.mdc, .gitattributes, .gitignore, .windsurf/workflows/app-versions.md, .windsurf/workflows/cod.md, .windsurf/workflows/driv.md, .windsurf/workflows/pickup-tasks.md... |

### ?? Security Findings Table

| File | Vulnerability | Type | Priority Fix |
|---|---|---|---|
| src/axios.js | Access token in localStorage | Insecure Storage | Move to HttpOnly cookie flow |
| src/contexts/AuthContext.jsx | Token/workspace persisted in localStorage | Insecure Storage | Server-managed session + in-memory auth context |
| vite.config.js | No documented CSP/header hardening | Security Header Gap | Add reverse proxy headers and CSP policy |

### ??? Architecture Review
- Framework + stack detected: React + Vite, Redux Toolkit, React Router v6, Axios.
- State management pattern detected: Redux slices + multiple Context providers (mixed).
- Data fetching pattern detected: Axios service plus ad-hoc calls.
- Violations / anti-patterns found: Env key mismatch, legacy lint config with ESLint 9 runtime, localStorage token storage.
- Folder structure issues: Very large component monolith under `src/components/admin` with mixed domains.
- Missing layers (services / hooks / types / constants): Inconsistent typed API service abstraction and central error normalization.
- SOLID violations:
  - SRP: Large pages/components combine data fetching, mapping, and UI.
  - OCP: Repeated switch/conditional status mapping patterns instead of strategy map reuse.
  - DIP: UI components directly coupled to axios/localStorage in places.
- God components (>300 lines with mixed concerns): Multiple files in admin modules (recommend splitting by concern).
- Business logic inside JSX return(): present in several large table pages.
- Direct fetch/axios calls inside components (no service/hook layer): observed across admin and merchant pages.
- Prop drilling chains (>3 levels deep): likely in layout + table/dialog stacks; recommend context selectors.


### ??? Top 10 Priority Fixes
1. [HIGH] src/contexts/AuthContext.jsx — `setWorkSpace` state overwrite bug — store `{id,type}` object with null guard.
2. [HIGH] src/axios.js — token in localStorage — migrate to HttpOnly cookie strategy.
3. [HIGH] src/axios.js + .env.example — API URL env mismatch — standardize `VITE_API_BASE_URL`.
4. [MEDIUM] .eslintrc.cjs/package.json — ESLint 9 flat config mismatch — add `eslint.config.js`.
5. [MEDIUM] src/main.jsx — typo `reverseShipment` prop — use `reverseOrder`.
6. [MEDIUM] src/main.jsx — global error listener lifecycle — prevent duplicate registrations.
7. [LOW] vite.config.js — document and enforce CSP/security headers in deployment.
8. [LOW] Introduce `npm run type-check` script and gradual TS migration gates.
9. [LOW] Add automated tests for auth, routing guards, API error handling.
10. [LOW] Create domain-level service/hooks to decouple components from transport details.


### ?? Testing Coverage Gaps
- Missing unit tests for: utils, reducers, auth helpers.
- Missing component tests for: route guards, forms, table actions, dialogs.
- Missing integration/e2e tests for: login/logout, shipment CRUD, role-based routing.
- Suggested test cases: 401 interceptor flow, workspace switching, env fallback, chunk-load recovery.


### ?? package.json Review
- Outdated packages (with latest versions): requires online check (not fully available in current environment).
- Unused packages: not conclusively determined without dep graph tool.
- Packages with known CVEs: `npm audit` blocked by registry 403 in this environment.
- Missing recommended packages + reasons: `vitest` + `@testing-library/react` for test coverage, `eslint-config-prettier` for rule conflict reduction.
- Version conflicts / peer dep warnings: ESLint major mismatch with config style.


### ?? Security Hardening Checklist
- [ ] No secrets or API keys in any frontend source file
- [ ] No sensitive data in localStorage / sessionStorage without encryption
- [ ] All user input sanitized before render (no dangerouslySetInnerHTML with user data)
- [ ] CSP headers configured
- [ ] HTTPS enforced (no mixed content)
- [ ] Dependencies have no known CVEs (run npm audit)
- [ ] No open redirect vulnerabilities in routing
- [ ] Auth tokens not accessible via JavaScript (HttpOnly cookies preferred)
- [ ] .env files not committed to repo
- [ ] No internal API URLs or credentials in client bundle


### ? Performance Checklist
- [ ] Route-based code splitting with React.lazy + Suspense
- [ ] Heavy components memoized with React.memo
- [ ] Expensive calculations wrapped in useMemo
- [ ] Stable callbacks wrapped in useCallback
- [ ] Long lists use virtualization (react-window / react-virtual)
- [ ] Images optimized and lazy loaded
- [ ] No blocking scripts in critical render path
- [ ] Bundle analyzed (no unexpectedly large dependencies)
- [ ] Web Vitals monitored (LCP / CLS / FID / INP)


### ? Accessibility Checklist
- [ ] All images have meaningful alt text
- [ ] All interactive elements reachable by keyboard
- [ ] Focus management handled in modals and dialogs
- [ ] Color contrast meets WCAG 2.1 AA (4.5:1 text, 3:1 UI)
- [ ] Forms have associated labels
- [ ] Error messages linked to inputs via aria-describedby
- [ ] Page has a single h1 and logical heading hierarchy
- [ ] No content relies on color alone to convey meaning


---
## FINAL VALIDATION

- Total files discovered: 806
- Total files audited: 806
- Skipped files: 0
- Confirmation: "No source findings were dropped in ACTION_PLAN.md. It is a complete reorganization view of AUDIT_FULL_REPORT.md."
