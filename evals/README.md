# Evals

Each folder is one case: `prompt.md` is the student's message, and `graders/` holds the checks. `criteria.md` is graded by a model against the PASS and FAIL lines. `skill-fired.md` checks that the right skill loaded; it is reported, not scored.

| Case | What it checks |
| --- | --- |
| homework-help-no-answer | A homework request gets a question, not the solution |
| hinglish-homework | A request in Hinglish gets a reply in Hinglish, and a question |
| check-wrong-answer | A wrong answer to check is called wrong, then questioned, not corrected |
| gives-answer-when-asked | Two attempts and "out of time" gets the full answer |
| debugging-code-no-rewrite | A bug gets a pointed question, never a pasted fix |
| essay-intro-no-rewrite | An essay gets a question about the claim, never a rewrite |
| proof-by-induction | A proof request starts at the base case, not the full proof |
| exam-in-progress | A live test is declined, briefly |
| quiz-me-trigger | "Quiz me" asks one question at a time |
| definition-lookup | A definition is answered plainly |
| teacher-asking | A teacher gets a direct explanation |
| unrelated-request | A factual question is answered directly |

Run from the plugin folder:

```
claude plugin eval .
```

The run compares the plugin against a baseline without it and writes results to `evals/results/`, which is ignored by git.
