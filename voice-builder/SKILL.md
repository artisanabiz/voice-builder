---
name: voice-builder
description: Learn an existing writing voice from samples and concrete feedback, then create a standalone Writer skill. Use for the user's own voice or a clearly labeled reference voice, with an adaptive quiz and real writing trials.
metadata:
  version: "0.1.0"
---

# Voice Builder

Help a person turn an existing writing voice into a usable Writer skill. The Builder discovers and calibrates the voice; the exported Writer writes and reviews in it. Success requires useful writing accepted by the user and instructions that work without this conversation. A technical validator alone establishes neither.

The workflow is language- and format-adaptive. Learn from the current user's authorized material; this package supplies no personal voice, sample corpus, default signature, or prior user decisions. Use only the resources inside this skill for its instructions. Never look for the package author's chats, private files, or development history.

## Start with the first useful output

Reuse the information already supplied. Establish what the person wants to write first, in which language, and whose voice the samples represent. Own writing, a reference author's writing, and a deliberate blend have different provenance; keep these labels throughout. Ask about an unresolved distinction only when it matters to the output.

Make choices easy: one consequential question at a time, a few concrete options, and a way to write a different answer. Use native selectable controls when available; otherwise show numbered options and accept a number or free text. Describe options in the user's conversational language. Do not prescribe a fixed questionnaire or promise buttons on a host that cannot provide them.

Invite available samples and explain the AI-processing boundary before private material; follow [sample handling](references/samples-and-privacy.md). There is no sample quota. If a person wants their own voice but has no saved samples, offer a short natural response to a familiar situation. Treat it as new writing evidence. Creating an invented persona is a different task from learning an existing voice; clarify that distinction if requested.

## Learn and propose the voice

Use [learning and calibration](references/learning-and-calibration.md) to examine expression, development, reader relationship, situational differences, and recurring signatures. Distinguish observations from explicit preferences and proposed adaptations. Write a short concrete proposal the person can assess, rather than an adjective list.

If a closing or other phrase recurs with a stable role, make it an explicit choice: keep it exactly, create a different signature, vary the same idea, or omit it. When proposing replacement wording, show the actual wording. Preserve an approved exact phrase in its agreed scope. A general acknowledgment does not resolve a still-open choice.

Recap the proposed direction and resolved choices, and get approval before a trial. Once those decisions are settled, a simple approval is sufficient. Do not reopen settled questions.

## Try the voice on real material

Get the subject, purpose, and necessary facts. The user can delegate topic selection. Separate the voice from the current editorial angle, format, and factual material. Research current claims if the request requires it and tools permit; use opened, reliable sources and make access limits clear. Source claims in the writing samples are not automatically verified.

Write one useful draft in the agreed language and format. Let the brief and useful development determine length. Do not impose an arbitrary word range, a storytelling formula, or catchphrase density.

Ask the user to assess fluency and voice resemblance separately, using selectable choices plus optional direct edits. Also check factual fidelity and the requested angle. A fluent text may still sound generic. On mismatch, use a short passage or concrete correction to locate the problem before another full rewrite. Update only the supported hypothesis; [learning and calibration](references/learning-and-calibration.md) explains how to avoid swinging between universal rules.

Continue until the user accepts useful writing and the lasting guidance, requests a provisional export, or chooses to pause. Do not invent the user's acceptance or run a predetermined number of rounds.

## Export and check independently

Follow [Writer export](references/writer-export.md). Confirm or use an already authorized name and destination; create the actual skill when file tools are available. Keep the original voice labels and approved signatures. Export minimal useful guidance, not this interview or private evidence. Confirm permission before including exact sample excerpts.

Offer an independent use in a fresh chat or, when authorized, an isolated agent using only the export and a new brief. If a reference answer for a topic was consulted during calibration, use a different topic for the independent trial. The user judges the new writing; an agent report is not human acceptance. Keep creation, installation, and publication separate.

Deliver the Writer, a short use example, and what has actually been tested. A provisional export remains labeled provisional. If a fresh-context trial fails, repair the exported guidance rather than depending on hidden conversation history. Do not update a released Writer or inspect unrelated private writing without authorization.
