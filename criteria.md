# Acceptance criteria — The Unofficial Guide

## 1. Retrieved chunks contain the answer

For at least 4 of my 5 test questions, the retrieved chunks include one that
contains the answer.

**Why this target:**

The advice threads cover specific student situations, so most answers should be directly present in the retrieved chunks. I allow one miss because some questions may require combining advice from multiple replies.

## 2. Every answer names a source

Every answer the system produces names at least one source document.

**Why this target:**

Each advice thread comes from a named source file, so the system has a source available for every in-scope answer. The criterion would only fail if the generation step leaves out the retrieved source information.

## 3. The relevance gate stops out-of-corpus questions

When I ask a question my documents clearly don't cover, the relevance gate
stops it and the system returns "I don't have enough information about that" —
in at least 4 of 5 tries.

**Why this target:**

The corpus focuses on college life, student routines, and campus experiences, so unrelated questions should be rejected. I allow one miss because an out-of-scope question may still resemble a topic in the advice threads and pass the relevance cutoff.

## 4. Chunk readability and completeness

At least 4 of 5 sampled chunks read as a complete thought, with no sentence cut off at either end.

**Why this target:**

The corpus focuses on college life, student routines, and campus experiences, so unrelated questions should be rejected. I allow one miss because an out-of-scope question may still resemble a topic in the advice threads and pass the relevance cutoff.

## 5. The system represents tradeoffs when the thread contains multiple viewpoints

At least 4 of 5 comparison questions, the answer includes at least two relevant advantages, disadvantages, or differing viewpoints instead of presenting one universal recommendation.

**Why this target:**

Several threads present both benefits and drawbacks, such as biking, parking, meal plans, and textbook editions. Including both sides helps the system reflect the corpus accurately instead of turning personal advice into a universal rule.

<!-- ─────────────────────────────────────────────────────────────────────────
     UNIT 2 — read this before you change anything above.

     If a criterion turns out to be BROKEN rather than merely unmet, you can
     revise it, and that earns credit. But never delete or edit the original
     line. Add the revision underneath it, like this:

         ## 1. Retrieved chunks contain the answer

         For at least 4 of my 5 test questions, the retrieved chunks include
         one that contains the answer.

         **Why this target:** ...

         > **Revised in unit 2:** For at least 4 of 5 questions, the top three
         > results contain the answer.
         >
         > **Why revised:** I couldn't judge "the chunks include one that
         > contains the answer" the same way twice — I scored two questions
         > differently on Monday than on Wednesday. The new version is
         > something I can actually check.

     That's a revision because the criterion couldn't be MEASURED.

     Lowering a target because you missed it is not a revision, and it costs
     you the point:

         ✗ "I said 4 of 5 but got 2 of 5, so 2 of 5 is more realistic."

     A number you missed stays where it is, gets diagnosed, and gets a fix
     attempted. That's where the points are.

     The whole reason the originals stay visible is so someone can see what you
     said before you knew the answer.
     ───────────────────────────────────────────────────────────────────────── -->
