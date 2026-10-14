# Four AI Foundations in Practice

AI concepts are easier to understand when they are connected to real interactions. These four examples show how context limits, tokens, temperature and hallucinations can appear in everyday use.

## 1. Context-window pressure: a long business-analysis conversation

In one conversation, I asked an AI to review a fictional evidence pack, calculate delays, answer follow-up questions, challenge recommendations and create a five-slide pitch deck.

As the files, calculations and instructions accumulated, the conversation placed increasing pressure on the model's **context window**, which is the amount of information it can keep available at one time. If that limit were exceeded, early evidence or instructions could drop out of view.

**Lesson:** In long projects, periodically restate the key facts, decisions and constraints in a short summary.

## 2. Tokens: a long statistics study thread

Another conversation moved through z-scores, confidence intervals, standard deviation, Bessel's correction and the Central Limit Theorem.

Models process text as **tokens**, which are small chunks of words and characters. Every question, answer and pasted source uses tokens. A long study thread therefore consumes more of the available context window, increasing the chance that earlier material will no longer be available.

**Lesson:** Tokens are the units being processed; the context window is the total capacity available for those tokens.

## 3. Temperature-style variation: redesigning the same pitch card

I repeatedly reworked the same fictional business pitch card, asking for it to be more flashy, written in a comic Scottish dialect, given tartan colours and made more visual.

These versions illustrate the type of variation associated with **temperature**. A lower temperature generally favours safer and more predictable output, while a higher temperature allows more varied or surprising choices.

In this case, I did not directly change a temperature setting. I requested the variation through new prompts, so this is an analogy rather than proof that the model's temperature changed.

**Lesson:** Temperature affects the variety of outputs when the prompt and other conditions remain the same.

## 4. Hallucination: an invented source detail

During analysis of a fictional knitwear evidence pack, the AI presented a complete product size chart as though it had come from the supplied files. When I asked exactly which file contained it, the AI admitted that it had inferred some of the values and had never actually seen the full chart.

This was a **hallucination**: a plausible inference was presented as a sourced fact. The answer sounded precise and confident, but part of its supporting evidence did not exist.

**Lesson:** When an AI gives a specific fact, quotation, calculation or citation, ask where it came from and verify it against the original source.

## Quick comparison

| Foundation | What happened | Practical safeguard |
|---|---|---|
| Context window | A long analysis accumulated files, calculations and instructions | Restate the essential facts and constraints |
| Tokens | A long learning thread consumed increasing amounts of capacity | Split large topics or documents into sections |
| Temperature | Similar prompts produced increasingly creative versions | Use lower variation for consistency and higher variation for ideation |
| Hallucinations | An inferred chart was presented as a sourced chart | Request exact sources and verify important claims |

## Final takeaway

Fluent output is not the same as reliable output. Good AI use combines clear prompts with active checking: manage the amount of context, understand that text consumes tokens, choose the appropriate level of creative variation and verify any claim that matters.
