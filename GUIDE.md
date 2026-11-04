# AI Testing Evidence Guide: decision guide

Ask what would make an AI feature acceptable.

**For:** Product owners and QA leaders evaluating an AI feature in an enterprise platform or digital product.

**Decision in focus:** What evidence and decision ownership are needed to discuss acceptable AI behaviour?

## Define acceptable behaviour in context

An AI feature needs a business purpose and a clear account of acceptable and unacceptable behaviour. A fluent output is not evidence of correctness. Discuss where a person must review or intervene and which decision the feature is allowed to influence.

**Question to discuss:** What outcome would be unacceptable even if the response sounded convincing?

## Ask about evaluation evidence and its limits

The relevance of an evaluation depends on the task, examples, review criteria and system configuration. A public checklist cannot establish actual quality. Ask how representative the evidence is and who can interpret it without sharing datasets, prompts or production conversations publicly.

**Question to discuss:** Which user situation is least well represented by the evidence available?

## Discuss risk categories without implying validation

NIST AI RMF is a voluntary risk-management reference. OWASP documents prompt injection as a risk category for generative AI. Referring to these materials does not certify a product, demonstrate resistance to attacks or replace a scoped evaluation.

**Question to discuss:** Who owns the decision when an AI output conflicts with a business rule?

## Treat change as an evidence question

Changes to a model, retrieval content, instructions or connected tools can change behaviour. A discovery discussion should clarify which changes trigger review and who can suspend use. No reusable attack corpus, evaluation harness or delivery methodology is supplied here.

**Question to discuss:** What change would make existing evaluation evidence need review?

## Read next

Read [source status and retrieval limitations](SOURCES.md), try the local mini tool using the [README instructions](README.md#start-here), or [discuss the question on LinkedIn](https://www.linkedin.com/in/manoj-rollo/). A short, non-confidential outline is enough. Professional assessment or delivery is separately scoped. This guide does not assess a system or approve a release.
