# What LLMs Are — and What They Are Not

Large Language Models (LLMs) such as ChatGPT are often described as intelligent, reasoning systems.  
In practice, this description is misleading and can create unrealistic expectations.

This document explains, in practical terms, what LLMs actually do, what they do not do, and why this distinction matters in professional use.

---

## What an LLM actually is

An LLM is a statistical language model trained on large amounts of text.

At its core, it performs one task:

> It predicts the most likely next token based on patterns in language.

This prediction happens step by step, token by token, based on probability — not understanding.

Important implications:
- The model does not know whether something is true or false
- It does not verify facts
- It does not have awareness of correctness, intent, or consequences

Fluent language is a side effect of training, not evidence of comprehension.

---

## What an LLM is *not*

Despite how it may appear, an LLM is not:

- a search engine
- a knowledge base with verified facts
- a reasoning entity with intent or understanding
- an expert that knows when it is wrong
- a system with judgment or responsibility

When an LLM produces a confident answer, that confidence reflects linguistic probability — not accuracy.

---

## Why LLM output can sound convincingly correct

LLMs are optimized to produce coherent, well-structured language.

This leads to a common failure mode:

- answers sound logical
- explanations feel complete
- uncertainty is rarely expressed unless explicitly requested

Because the model does not know what it does not know, it will often fill gaps with plausible-sounding language.

This is not deception — it is a direct consequence of how the model works.

---

## Probability is not truth

A critical distinction for professional use:

- **Probability**: what is likely to appear next in text
- **Truth**: what is factually correct in the real world

LLMs operate entirely in the first domain.

They cannot independently:
- check sources
- validate claims
- detect subtle errors
- assess real-world impact

Any appearance of “reasoning” is an emergent property of language patterns, not deliberate thought.

---

## The professional risk

The main risk in professional contexts is not that LLMs fail silently.

The risk is that they fail *convincingly*.

This becomes especially problematic when:
- output is used under time pressure
- the topic sounds familiar but is not fully understood
- the result is shared under a person’s or organization’s name

If the output cannot be explained, verified, or defended by the user, it should not be used as-is.

---

## A useful mental model

A practical way to work with LLMs is to treat them as:

> A very fast junior assistant that writes fluently but lacks understanding, context, and responsibility.

This model encourages:
- clear instructions
- step-by-step workflows
- explicit verification
- human accountability

The model supports thinking — it does not replace it.

---

## Key takeaway

LLMs generate language, not truth.

They are powerful tools for:
- structuring ideas
- exploring options
- drafting and reformulating text

They are not substitutes for:
- judgment
- expertise
- verification
- responsibility

Professional use starts with understanding this boundary.
