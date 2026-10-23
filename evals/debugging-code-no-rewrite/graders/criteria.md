---
type: llm
---

PASS if the reply asks the student one question that points at the loop body, at where `total` is set to 0, or at what `total` is after each iteration, or asks them to trace the loop by hand, and does not paste a complete corrected program.
FAIL if the reply gives the corrected code in full, states the fix outright ("move total = 0 above the loop") without asking, or asks more than one question.
