# Evaluation Process explanation v1

## Goal

Decide whether a Footprints report is accurate, meaningful, and recognisable
enough to keep testing.

This is a lightweight research check, not a formal scoring system.

## Evaluation Questions

Answer each question with **Yes**, **Partly**, or **No**.

### 1. Is it accurate?

Are the major projects, themes, and evidence anchors supported by the user's
conversations?

### 2. Did it find what mattered?

Does the report include the most important work, interests, and recurring
questions without giving too much attention to minor topics?

### 3. Did it reveal useful patterns?

Does it connect ideas across time or surface something the user may not have
noticed or remembered?

### 4. Is it balanced and restrained?

Does it represent the full period, avoid overemphasising recent conversations,
and avoid unsupported claims or personality judgements?

### 5. Does it feel recognisable?

Does the export owner feel that the report reflects their period in a useful
and human way?

## Automatic Failure

A report fails if it:

* invents or seriously misrepresents evidence;
* bases a claim about the user only on assistant-generated text;
* makes diagnostic, sensitive, or judgemental claims without clear support;
* exposes system, tool, or unnecessary private content.

## Result

* **Pass:** No automatic failures, at least four answers are **Yes**, and
  accuracy and recognition are both **Yes**.
* **Revise:** The report is promising but has one or more **Partly** or **No**
  answers that can guide a prompt change.
* **Reject:** It has an automatic failure or does not feel grounded in the
  export.

## Test Process

1. Generate a report with a recorded prompt version.
2. Check the major findings against the source conversations.
3. Ask the export owner the five evaluation questions.
4. Record the strongest result, the biggest problem, and one proposed change.
5. Test prompt changes on the same export and at least one other export before
   accepting them.

When comparing prompt versions, prefer the report that is more accurate and
recognisable. Do not choose a version merely because it is longer or more
polished.

