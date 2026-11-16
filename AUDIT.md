# AUDIT

Name:

## Baseline (home.html before any changes)

| Check                            | Result |
| -------------------------------- | ------ |
| Lighthouse accessibility score   | 17     |
| Lighthouse failed audits         |  3     |
| WAVE errors                      |  1     |
| WAVE contrast errors             |  6     |
| WAVE alerts                      |  9     |
| HTML validator errors            |  5     |
| Keyboard test (notes)            |  Can tab but its not clearly visible that I am tabbing.|
| 200% zoom and 320px test (notes) |  Text does get cut off, its not responsive.            |

Contrast pairs checked:

| Text color | Background color | Ratio | Pass or fail (4.5:1 normal, 3:1 large) |
| ---------- | ---------------- | ----- | -------------------------------------- |
| ffffff     |  F5A25D          | 2.05:1| Fail                                   |
| 8ab4ff     |  ffffff          | 2.08:1| Fail                                   |
| b388d6     |  ffffff          | 2.83:1| Fail                                       |

## Problems found on home.html (at least 8)

| #   | What I saw (evidence)    | Tool or test that showed it | POUR principle | WCAG idea | Severity | Planned fix |
| --- | ---------------------    | --------------------------- | -------------- | --------- | -------- | ----------- |
| 1   | Img folder missing Logo  |                             |                |           |          |             |
| 2   |                          |                             |                |           |          |             |
| 3   |                          |                             |                |           |          |             |
| 4   |                          |                             |                |           |          |             |
| 5   |                          |                             |                |           |          |             |
| 6   |                          |                             |                |           |          |             |
| 7   |                          |                             |                |           |          |             |
| 8   |                          |                             |                |           |          |             |

## ARIA notes (Part 2, step 13)

For each ARIA attribute you kept or added, explain why a native HTML element could not do the job. If you use none, say so.

## Usability review of services.html

Task scenarios:

- Task A: Estimate the cost for a large dog for boarding and grooming.
- Task B: Find out if a stay from December 24, 2026 to December 26, 2026 is possible.
- Task C: You added Training by mistake. Remove only Training.

Findings (at least 6, at least 5 different heuristics):

| #   | Task | Evidence (what happened) | Heuristic | Severity | Change to test |
| --- | ---- | ------------------------ | --------- | -------- | -------------- |
| 1   |      |                          |           |          |                |
| 2   |      |                          |           |          |                |
| 3   |      |                          |           |          |                |
| 4   |      |                          |           |          |                |
| 5   |      |                          |           |          |                |
| 6   |      |                          |           |          |                |

Design checklist for this page:

- Who is using this?
- What is the primary action?
- What competes with it?

## Retest of services.html

| Task | Before (result) | After (result) |
| ---- | --------------- | -------------- |
| A    |                 |                |
| B    |                 |                |
| C    |                 |                |

## Verification of book.html

| Check                                                                        | Result |
| ---------------------------------------------------------------------------- | ------ |
| HTML validator errors                                                        |        |
| Lighthouse accessibility score                                               |        |
| Keyboard test (notes)                                                        |        |
| DevTools check of the status message container (what attribute did you see?) |        |

## After (home.html final)

| Check                          | Before | After |
| ------------------------------ | ------ | ----- |
| Lighthouse accessibility score |        |       |
| WAVE errors                    |        |       |
| WAVE contrast errors           |        |       |
| HTML validator errors          |        |       |
| Keyboard test                  |        |       |
| 200% zoom and 320px test       |        |       |

## Before shipping checklist (all three pages)

- [ ] Keyboard access works everywhere. Proof:
- [ ] Focus is always visible. Proof:
- [ ] Contrast passes. Proof:
- [ ] Layout works on small screens. Proof:
- [ ] Feedback is meaningful (errors and success). Proof:

## One thing I had to check by hand that the tools did not catch
