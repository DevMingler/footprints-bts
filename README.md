# Footprints BTS

Behind-the-scenes research, prompt development, evaluation, and experimentation for the Footprints project.

## What is Footprints?

Footprints is an experiment in helping people better understand their own conversation history.

Given a ChatGPT export (`chat.json`), Footprints aims to identify:

* Projects and initiatives
* Recurring themes
* Questions that persist over time
* Creative and reflective seasons
* Emerging interests
* Patterns of growth and attention
* Significant moments and turning points

The goal is not surveillance, productivity scoring, or behavioural optimisation.

The goal is reflection.

Footprints attempts to answer a simple question:

> Looking back across a year of conversations, what emerged?

---

## Repository Purpose

This repository contains the research and development work behind Footprints.

It serves as the source of truth for:

* Chat export structure analysis
* Prompt experimentation
* Evaluation criteria
* Prompt iteration history
* Sample outputs
* Research findings
* Design decisions
* Known limitations

The GPT and Codex Skill repositories consume the outputs of this work.

---

## Research Principles

### Reflection over analytics

Footprints is intended to help users reflect on their own conversations.

It is not intended to score, rank, judge, diagnose, or profile people.

### Transparency over magic

Outputs should be explainable.

If a conclusion cannot be reasonably supported by the conversation history, it should not be presented as fact.

### Patterns over individual messages

The focus is on long-term trends and recurring themes rather than isolated conversations.

### Signal over volume

A topic appearing frequently does not automatically make it important.

Some of the most meaningful ideas may appear only a few times.

---

## Evaluation Criteria

A successful report should:

* Identify major projects accurately
* Detect recurring themes
* Recognise long-term interests
* Surface meaningful patterns
* Avoid excessive repetition
* Avoid overfitting to recent conversations
* Avoid making unsupported claims
* Feel useful and recognisable to the user

The ideal reaction is:

> "Yes, that feels like my year."

---

## Current Scope

Current outputs may include:

* Major projects
* Recurring themes
* Creative seasons
* Persistent questions
* Idea archaeology
* Notable shifts in focus
* Reflection summaries
* Custom awards and highlights

Future outputs may include:

* Timeline generation
* Visual reports
* Presentation exports
* Interactive summaries

---

## Related Repositories

### footprints-custom-gpt

Contains the instructions and supporting assets required to run Footprints as a Custom GPT.

### footprints-codex-skill

Contains the Codex Skill implementation and community-driven enhancements.

---

## Status

Experimental.

The methodology, prompts, structure, and outputs are expected to evolve significantly as more exports are tested and evaluated.

---

## License

MIT

---

## Philosophy

People leave footprints everywhere.

In notebooks.

In projects.

In conversations.

In unfinished ideas.

Footprints exists to help make those paths visible again.
