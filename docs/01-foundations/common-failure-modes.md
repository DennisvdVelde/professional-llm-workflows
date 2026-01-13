# Common Failure Modes of Large Language Models

Large Language Models (LLMs) do not fail randomly.

They tend to fail in recognizable, repeatable ways.  
Understanding these failure modes is essential for anyone using LLMs in professional contexts.

This document outlines the most common patterns in which LLM output becomes unreliable.

---

## Hallucinated facts and sources

One of the most well-known failure modes is hallucination.

This occurs when an LLM:
- generates facts that do not exist
- invents references or sources
- combines unrelated concepts into plausible claims

From the model’s perspective, this is not an error.
It is simply completing a pattern that *looks* correct in language.

The output may be detailed, specific, and confidently written — and still entirely false.

---

## Overgeneralization

LLMs are trained on broad patterns across many contexts.

As a result, they often:
- flatten important distinctions
- apply general rules where exceptions matter
- ignore contextual constraints

This is especially risky in:
- policy
- legal or regulatory contexts
- organizational decision-making
- domain-specific expertise

What sounds like a “best practice” may not apply to the actual situation.

---

## Hidden assumptions

LLMs rarely surface their assumptions unless explicitly asked.

Typical hidden assumptions include:
- the environment or organization behaves in a certain way
- constraints are standard or typical
- missing information can be safely inferred
- edge cases are negligible

Because these assumptions remain implicit, they are easy to miss during review.

---

## False precision

LLMs can produce:
- exact numbers
- step counts
- percentages
- timelines

even when such precision is not justified.

This creates a dangerous illusion of accuracy.

Precision should not be confused with correctness.  
If the model cannot justify a number, the number should be treated as illustrative at best.

---

## Confident extrapolation beyond training context

LLMs may confidently answer questions about:
- recent events
- internal systems
- niche organizational processes
- undocumented practices

The model does not know where its training data ends or becomes unreliable.

If a question resembles something it has seen before, it will attempt to answer — regardless of actual knowledge.

---

## Inconsistent logic across long outputs

Within longer responses, LLMs may:
- contradict earlier statements
- shift definitions mid-way
- apply different criteria in different sections

Because the output is generated incrementally, global consistency is not guaranteed.

This makes long, complex outputs especially vulnerable to subtle errors.

---

## Polished but shallow explanations

LLMs are good at explaining *how things usually work*.

They are less reliable when asked to:
- deeply analyze unique situations
- account for organizational nuance
- handle conflicting constraints

The result may be text that sounds complete but lacks depth or relevance.

---

## Why these failures matter professionally

In professional contexts, these failure modes can lead to:
- incorrect decisions
- reputational damage
- flawed documentation
- misplaced confidence in AI-supported output

The more “finished” the text appears, the more dangerous these failures become.

---

## Key takeaway

LLM failures are patterned, not random.

Once these patterns are understood, they become easier to detect and control.

Professional use of LLMs requires:
- awareness of these failure modes
- explicit checks for them
- workflows that assume errors will occur

Ignoring these patterns does not make them disappear — it only makes them harder to spot.
