# Peer Review (Example)

This file is only an example. Change it freely: add, remove, or reword sections to fit your review.

Copy it to `peer-review.md` and submit it on Canvas (**HW4 Part 2 Peer Review** or **HW4 Part 3 Peer Review**). Review all three of your HW1 peers, and keep each answer short and specific.

**Reviewer:** Your name
**Stage reviewed:** Stage 1 (Part 2) or Stage 2 (Part 3)

---

## Peer 1: Student name

**Summary:** The project works end to end and was updated steadily, but input validation is incomplete and two acceptance tests fail.

- **Reviewed version:** https://github.com/student/project (commit `a1b2c3d`)
- **Setup:** I followed the README. The server started after I installed MySQL 8. Blockers: none.
- **Acceptance tests:** I ran `./run_tests.sh`. 18 of 20 passed. Failing: `POST /todos` with an empty title returns 200; expected 400.
- **Claim checked:** The README says "all protected endpoints reject missing tokens." I called 3 protected endpoints with `curl` and no token. Each returned 401.
- **Progress:** Did the student make steady progress and keep updating? Example: the plan (Plan vs Actual) was updated 4 times, and commits are spread over 5 weeks.
- **Quality:** Did the student build a high-quality software product? Example: every endpoint has automated tests and the README is reproducible, but input validation is incomplete.
- **Strengths:** Clear README; all tests are automated and report pass/fail.
- **Weaknesses:** Missing validation for empty input; the MySQL version is not documented.
- **Suggestion:** Add the required MySQL version to the README prerequisites, and return 400 for empty titles.
- **Score (/100):** 85. Works end to end with steady updates; points lost for the two failing tests and missing validation.

**Note to the professor:** The student's updates were consistent, and the test script is well made. The README claims were accurate when I checked them.

---

## Peer 2: Student name

**Summary:**

- **Reviewed version:**
- **Setup:**
- **Acceptance tests:**
- **Claim checked:**
- **Progress:**
- **Quality:**
- **Strengths:**
- **Weaknesses:**
- **Suggestion:**
- **Score (/100):**

**Note to the professor:**

---

## Peer 3: Student name

**Summary:**

- **Reviewed version:**
- **Setup:**
- **Acceptance tests:**
- **Claim checked:**
- **Progress:**
- **Quality:**
- **Strengths:**
- **Weaknesses:**
- **Suggestion:**
- **Score (/100):**

**Note to the professor:**
