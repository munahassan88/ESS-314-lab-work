# AI Error Log

A running list of moments when my AI assistant got something wrong
about geophysics — what it said, why it was wrong, and how I
verified.

This file lives in `ai_logs/error_log.md` and grows across the course.
It is referenced in my final project's reproducibility section as
evidence of my fact-checking practice.

---

## Entry template

```yaml
date: 2026-06-27
tool: [Chatgpt 5.5]
session_link: ai_logs/lab7_session_NN.md
topic: Seismic refraction
```

**What the AI said (quote or paraphrase):**

> [paraphrased claim or pasted excerpt — keep it short]

**Why it is wrong:**

[Specific reason in your own words. One short paragraph.]

**Primary-source verification:**

[The textbook page, equation number, or course lecture URL that
disproves the AI's claim. Include the exact quote if the source
contradicts the AI directly.]

**How I would have detected this with prompt strategy alone:**

[One sentence — e.g., "I should have asked for a unit check before
accepting the formula."]

---

## Entry 1
what the ai said 

Claim B is incorrect because the intercept time is not simply 2h/V₁; it depends on the critical-angle geometry and the velocity contrast between the two layers.

why its wrong 

After checking my Lab 3 notebook, I found that the claim itself was wrong, not the AI's evaluation. The intercept time in a two-layer refraction problem depends on both V₁ and V₂ through the critical-angle relationship. The claim incorrectly treated the intercept time as the same as the vertical two-way travel time through the upper layer.

Primary source verification 

In my Lab 3 seismic refraction notebook. The refracted-wave travel-time equation derived in the notebook shows that the intercept time includes a velocity-dependent term involving both V₁ and V₂. Therefore, the intercept time is not equal to 2h/V₁ as stated in Claim B

How I would have detected this with prompt strategy alone:

I should have asked for the full intercept-time equation and compared it to the equation I derived in Lab 3 before accepting the claim.


## Entry 2

[Add entries as the course progresses — Labs 7, 8, final project.]
