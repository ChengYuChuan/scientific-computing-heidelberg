# 📧 Email Archive

This folder contains anonymized email exchanges between students and Dr. M. Winckler (program coordinator).

---

## ⚠️ Mandatory Anonymization Rules

Before uploading any email, you **must** remove or replace the following:

| What to remove | Replace with |
|---|---|
| Your full name | `[Student Name]` |
| Your student ID (Matrikelnummer) | `[Student ID]` |
| Your email address | `[student@uni-heidelberg.de]` |
| Any identifying details (thesis topic, etc.) | `[redacted]` |

**Winckler's name and role may be kept**, as he is acting in an official capacity.

---

## 📁 File Naming Convention

```
YYYY-SS-topic-slug.md
```

Examples:
- `2024-WS-gpu-computing-eligibility.md`
- `2025-SS-bsc-import-credit-limit.md`

Semester codes: `WS` = Winter Semester, `SS` = Summer Semester

---

## 📄 File Template

Copy this template when creating a new email archive entry:

```markdown
# [Short description of topic]

**Semester:** WS/SS YYYY  
**Topic category:** [Course Eligibility / Registration / Thesis / Other]  
**Related FAQ entry:** [faq/coordinator-qa.md#section] (if applicable)

---

## Email Thread

### Student → Winckler (YYYY-MM-DD)

[Paste anonymized email text here]

---

### Winckler → Student (YYYY-MM-DD)

[Paste Winckler's response here]

---

## Summary / Takeaway

[2-3 sentences: what did we learn from this exchange?]
```

---

*To add an email, submit a Pull Request with a new `.md` file following the convention above.*
