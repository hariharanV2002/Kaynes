---
name: ERPNext Custom App — Issue (Agent Ready)
about: High-level issue template for @claude to reproduce, fix/build safely, and raise a PR to our main branch.
title: "[Bug|Enhancement|Feature] "
labels: ["needs-triage"]
---

# 1) Issue Summary

**One-liner:** 

**Business impact:** 

---

# 2) Scope & Safety (Must Not Break)

**In scope:** 

**Out of scope:** 

**Must not break flows:**
1. 
2. 
3. 

---

# 3) Expected vs Actual

**Expected (functional contract):**
- When [condition], given [context], system must: [expected behavior]

**Actual:**
- [What actually happens]

---

# 4) Reproduction (Deterministic)

**Preconditions / Setup:**


**Steps:**
1. 
2. 
3. 

**Observed result:**


**Expected result:**


---

# 5) Evidence

**Doc links/IDs:** 

**Screenshots/recording:** 

**Logs/traceback (redact secrets):**
```
[paste logs here]
```

---

# 6) Environment

* **ERPNext:** v15.80.1 (version-15)
* **Frappe:** v15.83.0 (version-15)
* **Custom app:** kaynes
* **Python version:** 
* **Database:** 

---

# 7) Acceptance Criteria

* [ ] Repro now matches expected behavior
* [ ] Tests added/updated (unit/integration where applicable)
* [ ] Regression checked for "Must not break" flows
* [ ] No new errors/tracebacks; permissions remain correct

---

# 8) Repo Branching & PR Policy (MANDATORY)

**Our main branch:** `feat/wo-fg-from-development`

**@claude must:**
1. Create a new branch **from** `feat/wo-fg-from-development`
2. Commit changes to the new branch only
3. Raise PR **to** `feat/wo-fg-from-development` (base branch)
4. **Never** open PRs to `main` / `master`

**Branch name convention:** `claude/issue-<issue-number>-<short-description>`

**PR must include:**
- Summary of changes
- Root cause analysis
- Fix approach
- Tests run + results
- Regression notes
```
