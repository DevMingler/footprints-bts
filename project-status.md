# Project Status

## Overview

Footprints is an experiment in turning ChatGPT conversation exports into meaningful reflective reports.

The project seeks to identify recurring themes, projects, interests, questions, and patterns across a user's conversation history and present them in a format that feels recognisable, useful, and human.

Current focus is on prompt engineering, evaluation, and report quality rather than product development.

---

## Current Phase

Phase 0 — Research & Validation

Objective:

> Determine whether a sufficiently capable prompt can generate valuable reports from a standard ChatGPT export (`chat.json`).

Success criteria:

* Reliable identification of major projects
* Detection of recurring themes
* Recognition of long-term interests
* Meaningful summaries
* Outputs that users recognise as accurate and useful

---

## Repositories

### footprints-bts

Status: Active

Purpose:

* Research repository
* Prompt development
* Evaluation framework
* JSON structure analysis
* Example outputs
* Design decisions

---

### footprints-custom-gpt

Status: Planned

Purpose:

* Public-facing Custom GPT
* Uses distilled prompt developed in footprints-bts
* Enables users to upload their own exports and receive reports

Current focus:

* Awaiting prompt maturity

---

### footprints-codex-skill

Status: Planned

Purpose:

* Open-source Codex Skill
* Advanced and community-driven version of Footprints
* Allows experimentation, custom outputs, and workflow modifications

Current focus:

* Awaiting prompt maturity

---

## Current Priorities

### Priority 1

Understand the structure of modern ChatGPT exports.

Tasks:

* Obtain sample export
* Document schema
* Identify required fields
* Understand conversation hierarchy

Status: Complete

Findings: [ChatGPT Export Findings](docs/chatgpt-export-schema.md)

---

### Priority 2

Develop initial report prompt.

Tasks:

* Define report sections
* Establish analysis workflow
* Create first prompt version

Status: Complete

Design: [Report Design v1](docs/report-design-v1.md)

Prompt: [Footprints Reflective Report Prompt v0.1](prompts/001-generate-reflective-report.md)

---

### Priority 3

Create evaluation rubric.

Tasks:

* Define quality measures
* Establish comparison criteria
* Create test methodology

Status: Complete

Process explanation: [Evaluation Process explanation v1](docs/evaluation-process-explanation-v1.md)

Template: [Evaluation Template](evaluations/evaluation-template.md)

---

### Priority 4

Generate first successful report.

Goal:

Produce a report that accurately reflects the contents of a real export and would cause a user to say:

> "Yes, that feels like the path I walked."

Status: Complete

First run:

* Export: [Example Chat](example-chats/chat.json)
* Prompt: [Footprints Reflective Report Prompt v0.1](prompts/001-generate-reflective-report.md)
* Report: [Reflective Report 001](reports/001-example-chat.md)
* Evaluation: [Evaluation 001](evaluations/001-example-chat.md)

The report has been generated. 
The evaluation is complete and the result meets the pass criteria. 
Priority 4 is complete.

---

## Risks

### Overfitting

Prompts may become tuned to a single export.

Mitigation:

* Multiple test exports
* Diverse evaluation cases

---

## Definition of Success

A user uploads their export and receives a report that:

* Feels accurate
* Reveals useful patterns
* Encourages reflection
* Surfaces forgotten projects and themes
* Helps them better understand their own journey

without requiring technical knowledge, dashboards, databases, or external tooling.

---

## Long-Term Vision

Create a lightweight, accessible way for people to explore the paths they have walked through their conversations.

The destination is not analytics.

The destination is reflection.

---

Last Updated: 2026-06-10
Project State: Research & Validation
Overall Progress: 80%
