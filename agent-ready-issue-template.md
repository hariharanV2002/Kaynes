---
name: 🤖 ERPNext Issue (Claude Ready)
about: Template optimized for @claude to understand, reproduce, and fix issues safely
title: ""
labels: ["needs-triage"]
---

## 📋 Issue Summary

**What's the problem (one line):**


**Why this matters to business:**


---

## 🎯 What Should Happen vs What's Happening

**What you expected:**


**What actually happens:**


---

## 🔄 How to Reproduce This Issue

**Setup needed before testing:**


**Steps to reproduce:**
1. 
2. 
3. 
4. 

**What you see (the error/problem):**


---

## 📸 Evidence & Details

**Screenshots or screen recording:**
(Drag and drop images here or paste links)


**Error messages or logs:**
```
Paste any error messages here
```

**Related documents/records:**
(Mention DocType names, Document IDs, etc.)


---

## 💻 Environment Details

- **ERPNext Version:** v15.80.1
- **Frappe Version:** v15.83.0
- **Custom App:** kaynes
- **Database:** MariaDB / PostgreSQL
- **Browser:** Chrome / Firefox / Safari (if relevant)

---

## ⚠️ Critical - What Must NOT Break

**These workflows MUST continue working:**
1. 
2. 
3. 

**Areas that should NOT be touched:**


---

## ✅ Definition of Done

When can we consider this issue resolved?

- [ ] The reproduction steps now work as expected
- [ ] No new errors or warnings appear
- [ ] The "Must NOT break" items still work perfectly
- [ ] Tests added/updated (if applicable)
- [ ] Code reviewed and approved

---

## 🌳 Branch & PR Instructions for @claude

**⚠️ MANDATORY - READ CAREFULLY:**

**Our main development branch:** `feat/wo-fg-from-development`

**When fixing this issue, @claude you MUST:**

1. ✅ Create a NEW branch from `feat/wo-fg-from-development`
2. ✅ Use branch name: `claude/issue-{issue-number}-{short-description}`
   - Example: `claude/issue-42-fix-batch-error`
3. ✅ Make all your changes in this new branch ONLY
4. ✅ Create Pull Request (PR) targeting `feat/wo-fg-from-development` (NOT main/master)
5. ✅ Include in PR description:
   - Root cause analysis
   - What you changed and why
   - How you tested it
   - Regression testing notes

**❌ NEVER do this:**
- Open PR to `main` or `master` branch
- Commit directly to `feat/wo-fg-from-development`
- Make changes without creating a new branch

---

## 💡 Additional Context (Optional)

**Any other information that might help @claude:**


**Similar issues or related tickets:**


**Workarounds you've tried:**


---

**Ready to assign?** Tag @claude in the comments below to start working on this issue! 🚀
