# Test Notes

**Learning question:** When a student sees a job ad, does a short set of questions with a Quick apply / Worth tailoring / Ask first result help them decide what to do, and do they treat the result as a final verdict?

**Prototype:** `prototype/index.html` (open in a browser).

**Task (read aloud, do not explain the buttons):** "Pick a real job ad you are considering right now and are deciding what to do about. Show me how you'd use this page, and tell me what you'd do next."

Neutral follow-up: "What would you do next?"

**Setup decision (prototype-reviewer finding 2, accepted):** each participant brings their own real job ad, so answers are not hypothetical. Because ads differ, results are not directly comparable across tests.

**Prototype version for test 1:** without the "this is a prompt for your own judgement, not a decision" note under the result (prototype-reviewer finding 1, accepted). If a later test adds the note back, record it here so the tests are not mixed up.

**Versions:** `prototype/index-v1-test1.html` is the version used for Tests 1-3 (title "Job check"). `prototype/index.html` is v2: new title "Should I apply to this job?", new intro, Q2 reworded with 3 options (No, it matches / Yes, it asks for more / I can't tell). "Yes, it asks for more" gives Ask first, "I can't tell" does not. Next steps under results are not changed yet. Record which version each test used; do not compare v1 and v2 results as if they were one set.

**Known limits of this version (deferred reviewer findings):** no "Not sure" option on Q2 and Q4, so participants must guess; Q3 says "including language" without naming which language. Watch for hesitation on these and note it.

**Facilitator log:** the page keeps a log of every result shown (open "Facilitator log" at the bottom). Copy it into the notes after each test. Participants may change answers before clicking "Show result"; note whether they did.

## Test 1 (labelled proxy: teammate, observed by facilitator)

Context and limits (who, which job ad, real or proxy): proxy tester (teammate), observed by facilitator. Job ad: ... (to fill in). One tester only.

Result shown (from facilitator log): Ask first
Did they agree with the result? ... (to fill in)
Did they change any answers before clicking "Show result"? ... (to fill in)
What were they leaning toward before the result? After? ... (to fill in)

### Observations (what happened, no interpretation)
- Attempted: used the page and got the result "Ask first".
- Hesitated or struggled at: Q2, which was unclear to them. After the result, unsure whom to ask and what to ask.
- Succeeded at: ... (to fill in)
- Did not understand why they were doing the test.

### What they said (quotes, kept separate)
- Paraphrased only so far, exact words to be added: unsure whom to ask; unsure what to ask; Q2 not clear; not clear why they did this.

### Questions this test did not answer
- What exactly was unclear in Q2 (wording, or not knowing the answer).
- Whether they agreed with "Ask first" and what they would do next.
- Whether they treated the result as a final verdict.

## Test 2 (labelled proxy: teammate, NOT observed, reported to facilitator)

Context and limits (who, which job ad, real or proxy): proxy tester (teammate). Job ad: ... (to fill in). Not observed: everything below is reported, lower confidence than Test 1.

Result shown (from facilitator log): Worth tailoring
Did they agree with the result? ... (to fill in)
Did they change any answers before clicking "Show result"? ... (to fill in)
What were they leaning toward before the result? After? ... (to fill in)

### Observations (what happened, no interpretation)
- Attempted: used the page and got the result "Worth tailoring".
- Hesitated or struggled at: Q2, which was not clear to them.
- Said they were still not sure what the use of the result is.
- Said they wanted more clear answers instead of just yes or no: if yes, what to do; if no, what to do.
- Succeeded at: ... (to fill in)

### What they said (quotes, kept separate)
- Paraphrased only so far, exact words to be added: still not sure what the use of the result is; second question not clear; would like more clear answers instead of yes or no: if yes what to do, if no what to do (reported, not observed).

### Questions this test did not answer
- What exactly was unclear in Q2.
- What they would do next with the job.

## Test 3 (labelled proxy: teammate, observed by facilitator)

Context and limits (who, which job ad, real or proxy): proxy tester (teammate), observed by facilitator. Job ad: ... (to fill in).

Result shown (from facilitator log): Ask first
Did they agree with the result? ... (to fill in)
Did they change any answers before clicking "Show result"? ... (to fill in)
What were they leaning toward before the result? After? ... (to fill in)

### Observations (what happened, no interpretation)
- Attempted: used the page and got the result "Ask first".
- Said the page title "Job Check" is misleading for her.
- When handed the page, she did not understand what it was for from the title "Job Check". She understood after answering the questions and seeing the result (facilitator observed this).
- Said she found the page useful.
- Said she liked that the answer description changes according to the answer selected.
- Hesitated or struggled at: ... (to fill in)
- Succeeded at: ... (to fill in)

### What they said (quotes, kept separate)
- Paraphrased only so far, exact words to be added: title "Job Check" is misleading; found it useful; likes that the description changes with the selected answer.

### Questions this test did not answer
- What title she would expect.
- Whether she knew whom to ask and what to ask after "Ask first" (Test 1 did not).
- What she would do next, and whether she treated the result as a verdict.
- Whether she hesitated at Q2.

## Interpretation (fill in AFTER the observations are written)

| Observation | Interpretation | Decision |
|---|---|---|
| "Ask first" with no who or what (Test 1) | The result gives a direction but no next step, so it may feel like a dead end. Hypothesis, one proxy. | Wait for more tests to see if others say the same. |
| Q2 unclear (Test 1) | Matches the known gap: no "Not sure" option on Q2. | Candidate fix: reword Q2 and add "Not sure". Do not change before more tests. |
| Unclear why they did the test (Test 1) | The page may need a short intro, or the task framing was missing. | Check how the task was explained to them. |
| Q2 unclear in Test 1 and Test 2 | Repeated in 2 of 2 proxy tests, so more likely a real wording problem than one person's confusion. Still a small sample. | Strongest candidate for a fix: reword Q2, add "Not sure". |
| Unsure of the use of the result (Test 1 "Ask first" had no next step; Test 2 unsure of its use) | Hypothesis: the result does not tell people what to do with it. | Wait for more tests; consider adding a next step under each result. |
| Wants answers that say what to do after yes and after no (Test 2, reported) | Hypothesis: they want a next step tied to each answer, not only a label. Same point as the missing next step in Test 1. | Consider adding a short "what to do next" under each result, tested as a new version. |
| Title "Job Check" did not explain the page; she understood only after answering the questions and seeing the result (Test 3, observed; facilitator agrees) | The title does not tell people what the page is for. Matches Test 1 "unclear why they did this" and Test 2 "unsure of the use". One tester said so directly. | Change the title in the next version to say what it does (e.g. about deciding what to do with a job ad). Test whether it helps. |
| Found it useful; liked description changing with the answer (Test 3, observed) | Supports that tailored descriptions help. Possible link to the next-step request in Tests 1-2. Conflicts with Tests 1-2 on usefulness, so not all testers agree. | Keep the changing descriptions; build the next steps into them. |
