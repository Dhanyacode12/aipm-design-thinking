# Decision Log

HMW (hypothesis, see `discovery.md`): How might we help mid-bootcamp students decide which jobs are worth tailoring a CV for, when job ads can be misleading and the outcome is uncertain?

## Ideas generated (before evaluation)

| # | Idea | One-line description |
|---|---|---|
| 1 | Job-ad reality check | Checklist that flags mismatches in an ad, such as "junior" with "5+ years" |
| 2 | Effort-vs-payoff tracker | Students log applications and outcomes to see what is worth the effort |
| 3 | Peer hiring stories | Shared board where classmates post what they heard back |
| 4 | Apply-or-skip questions | Short questions about a job that end in a recommendation |
| 5 | Ask-before-applying script | Short questions to send a recruiter or contact before tailoring a CV |

## Selection criteria

User value, learning value, feasibility, risk (3 = low risk), quick to test (added by the AI Project Manager: a classmate can try it in under 10 minutes).

## Scores (AI judgement, 1-3; not evidence)

| Idea | User value | Learning value | Feasibility | Risk | Quick to test | Total |
|---|---|---|---|---|---|---|
| 1 | 2 | 2 | 3 | 3 | 3 | 13 |
| 2 | 2 | 2 | 2 | 3 | 1 | 10 |
| 3 | 2 | 2 | 2 | 2 | 2 | 10 |
| 4 | 3 | 3 | 3 | 1 (lowered after PM challenge) | 3 | 13 |
| 5 | 2 | 2 | 3 | 3 | 2 | 12 |

## PM challenge

The AI Project Manager identified a risk in idea 4 that the AI had under-rated: a false "skip" verdict could stop a student from applying to a job they might have succeeded in. Risk score lowered from 2 to 1.

## Decision

**Chosen direction: idea 4, modified (Option X).** Instead of "apply or skip", the output is one of:
- Quick apply (low effort, little to lose)
- Worth tailoring (the match looks decent)
- Ask first (unclear, check with someone)

It never says "don't apply". The test must watch whether students treat the output as a final verdict.

**Why:** it tests the core hypothesis from `discovery.md` (do students want to judge whether a job is worth the effort?), which the evidence-auditor said has no direct evidence. It is fast to prototype and test.

## Rejected options

| # | Reason |
|---|---|
| 1 | Lower risk but tests less; does not touch the "is it worth my effort?" premise. Kept as the fallback if idea 4 is rejected. |
| 2 | Needs days of use; not testable today. |
| 3 | Hearsay can mislead; needs a larger group than is available. |
| 5 | Depends on recruiter replies; hard to test in a short session. |

## Iteration after Tests 1-3 (v1 to v2)

Evidence: `test-notes.md`. Tests 1-3 were proxy teammates (Tests 1 and 3 observed, Test 2 reported only). Three testers is a small sample, so these are hypotheses.

| Change in v2 | Evidence | Decision |
|---|---|---|
| Title "Job check" changed to "Should I apply to this job?" (title option 1) | Test 3 (observed): did not understand the page from the title, understood after the result. Test 1 "unclear why", Test 2 "unsure of the use". | Accepted by the PM. Risk: the title promises a yes or no; watch whether testers expect a verdict. |
| Intro shortened to option B (no "prompt for your own judgement" note) | Keeps the note out as a variable, as in test 1. | Accepted. |
| Q2 reworded: "Does the ad ask for more years of experience than its level suggests?" with No, it matches / Yes, it asks for more / I can't tell | Tests 1 and 2: Q2 unclear. Test 2 wanted clearer answers than yes or no. | Accepted option 1. PM rejected option 2 (years asked): the page does not know the tester's own experience, so a match cannot be judged. |
| Next step under each result | Tests 1 and 2 asked for it; Test 3 liked the changing descriptions. | NOT done in v2. Next iteration. |

v1 is saved as `prototype/index-v1-test1.html`. v2 is `prototype/index.html`. v2 has not yet been tested with participants.

