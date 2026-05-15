# Anthropic — Many-shot jailbreaking
Source: https://www.anthropic.com/news/many-shot-jailbreaking
Fetched: 2026-04-30

## Date
2024-04-02

## Definition (verbatim)
"A 'jailbreaking' technique — a method that can be used to evade the safety guardrails put in place by the developers of large language models (LLMs)."

## Technique (verbatim)
"By including large amounts of text in a specific configuration, this technique can force LLMs to produce potentially harmful responses, despite their being trained not to do so."

The method involves filling the long context window with many fake user/assistant turns showing the model "complying" with prior unsafe queries.

## Specific numbers (verbatim)
Effective with "up to 256" fake dialogues.
"As the number of included dialogues (the number of 'shots') increases beyond a certain point, it becomes more likely that the model will produce a harmful response."

## Affected models (verbatim)
"The technique...is effective on Anthropic's own models, as well as those produced by other AI companies."
Demonstration used "Claude 2.0."
The jailbreak "is often more effective...for larger models."
