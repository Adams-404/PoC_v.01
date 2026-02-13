```markdown
---
name: 🐛 Bug Report (PoC Scope)
about: Report an issue affecting the functionality or logic of PoC_v.01
title: "[BUG] "
labels: bug, triage
assignees: ''
---

## ⚠️ PoC Criticality Assessment
<!-- Since this is a Proof of Concept (v.01), please indicate how this bug affects the core hypothesis. -->
- [ ] **Blocker:** The PoC cannot be validated/demonstrated until this is fixed.
- [ ] **Logic Flaw:** The implementation works, but the conceptual logic is incorrect.
- [ ] **Implementation Error:** The concept is sound, but the code throws an error.
- [ ] **Documentation Mismatch:** Implementation diverges from `ARCHITECTURE.md` or `README.md`.

## 🐛 Bug Description
<!-- Provide a clear and concise description of what the bug is. -->

## 🏗 Architecture Context
<!-- Please review ARCHITECTURE.md before answering. -->
**Does this bug violate the defined pattern in `ARCHITECTURE.md`?**
- [ ] Yes (Architectural Drift)
- [ ] No (Implementation Bug only)
- [ ] Unsure

**Affected Component/Module:**
<!-- e.g., Data Ingestion, Processing Layer, UI, etc. -->

## 💻 Environment & Setup
<!-- Since no manifest was detected in the root, please specify your exact runtime environment. -->
| Spec | Details |
| :--- | :--- |
| **OS** | (e.g., Ubuntu 20.04, Windows 10, macOS Ventura) |
| **Runtime/Language** | (e.g., Python 3.9, Node 18, Go 1.20 - *Please specify version*) |
| **Build Tool** | (e.g., Make, CMake, npm, pip) |
| **PoC Version** | v.01 (Current) |

## 🔄 Steps to Reproduce
<!-- A minimal reproduction path is vital for PoC debugging. -->
1.  Go to '...'
2.  Execute script/command '...'
3.  Input arguments '...'
4.  See error

## 📉 Expected vs Actual Behavior
**Expected:**

**Actual:**

## 📜 Logs / Stack Trace
<!-- Paste relevant logs below. Please format nicely with triple backticks. -->
```text
Paste logs here
```

## 📸 Screenshots / Diagrams
<!-- If this involves visual output or architectural diagrams, please add them here. -->

## 🔗 Related References
<!-- Links to specific lines in CHANGELOG.md or ARCHITECTURE.md that are relevant. -->
- Reference 1:
- Reference 2:
```