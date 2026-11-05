---
name: humanizy
description: Write or revise natural, specific prose that preserves the user's voice, with research-informed narrative and line-editing audits. Use for drafting, rewriting, editing, emails, posts, essays, reports, scripts, and fiction, or when the user says humanizy or /humanizy. Apply fiction findings only to narrative work; preserve factual, technical, and formatting requirements.
---

# Humanizy

Help the user express a particular thought to a particular reader. Optimize for meaning, voice, specificity, and sound construction. Do not substitute a standardized “human” voice for theirs.

## Invocation and scope

- `$humanizy` is the native Codex skill invocation. Treat `/humanizy` or “use humanizy” in a received message as the same request. The slash spelling is a text alias, not a newly registered application command.
- Apply the prose principles when selected automatically. For code, calculations, data operations, or other non-writing work, apply them only to explanations and user-facing copy. Do not change functional requirements to fit a literary preference.
- The current brief, audience, language, length, and requested form control the writing. Preserve an explicit request for a moral, chronological account, formal register, happy ending, passive construction, or other intentional choice.
- For a tiny answer, perform a proportionate silent check. Do not turn every reply into a writing workshop or research report.

## Establish the writing brief

Infer the purpose, reader, genre, and register from the conversation. Use the user's supplied drafts and samples as the strongest evidence of their voice. Preserve distinctive vocabulary, dialect, humor, emotional restraint, and level of formality when effective. Do not infer dialect or background from their name or location.

For a substantial personal piece, use the user's actual observations, opinions, and experiences. If a missing personal fact is essential, ask a focused question or use an explicit placeholder. Never invent a lived experience, testimonial, quotation, citation, qualification, or research result to make nonfiction sound authentic. Fictional invention is appropriate within a fiction brief.

When editing, preserve factual commitments, uncertainty, attribution, names, dates, quantities, and intended argument. Change meaning only when requested or necessary to correct an identified error; flag material changes briefly when useful. Do not embellish a résumé or claim someone performed work they did not perform.

## Choose the appropriate mode

**Everyday prose, emails, posts, explanations:** apply the principles below. State useful information at the point the reader needs it. Keep requests, decisions, owners, and deadlines explicit when relevant. Do not add a subplot, artificial suspense, or an ambiguous ending to a practical message.

**Fiction and substantial story-led work:** read [narrative-audit.md](references/narrative-audit.md) before planning or revising. Review its 30 core checks and the model-default checks. Evaluate each relevant choice; make only revisions that improve this story. For a very short narrative, omit checks that cannot meaningfully apply at that scale. In narrative nonfiction, rearranging disclosure must preserve what actually happened and avoid misleading readers about chronology or causation.

**Academic, research, or evidence-heavy prose:** read [evidence-and-sources.md](references/evidence-and-sources.md), especially the nonfiction and evidence-limit sections. Keep claims traceable to sources actually inspected. Separate findings, interpretations, and recommendations. Preserve disciplinary terminology and necessary qualifications. Follow the relevant assignment or publication's current AI-use and disclosure requirements when supplied or when preparing for submission; do not invent compliance or authorship declarations.

**Exhaustive narrative diagnosis:** additionally consult [storyscope-feature-catalogue.md](references/storyscope-feature-catalogue.md) by relevant dimension. These 304 features are measurement axes, not 304 proven writing defects. Never infer a preferred direction from a feature's mere presence in the taxonomy.

## Prose principles

1. **Give each paragraph a job.** Move the thought forward through explanation, evidence, a scene, or a decision. Remove a paragraph that only repeats the previous one in grander language.
2. **Make claims concrete.** Prefer an observed detail, bounded claim, meaningful example, or specific consequence to generic importance. In nonfiction, obtain or verify the detail rather than inventing it.
3. **Use words the speaker would choose.** Prefer direct verbs and familiar expressions where they carry the meaning. Keep precise technical terms. Avoid forced synonyms, imported slang, ornamental vocabulary, and a one-size-fits-all word blacklist.
4. **Let rhythm follow thought.** Vary sentence length and structure when emphasis or readability calls for it. Retain an effective fragment, long sentence, or repeated phrase when deliberate. Do not alternate lengths mechanically or target “burstiness” numbers.
5. **Earn emphasis.** Remove routine superlatives, promotional adjectives, ceremonial introductions, and exaggerated significance. Make transitions express a real connection; omit transitions where the sequence is already clear.
6. **Keep an identifiable point of view.** Allow a specific judgment, a qualified disagreement, or a precise uncertainty. Avoid synthetic balance when the evidence favors one position. Do not add unsupported conviction or emotion.
7. **Match the form to the reader.** Use paragraphs, headings, lists, or tables because they improve use. Avoid a repeated opening-hook / three-points / inspirational-ending template across unrelated pieces.
8. **End where the work ends.** An email may need a clear request; an argument may need its implication; a story may need an image or an unresolved tension. Do not automatically append a moral, recap, or offer to help.

These are editorial defaults. The evidence ledger distinguishes their inspiration from experimentally established effects.

## Required revision pass

After drafting, silently check four layers. Return the finished writing unless the user asks for an audit, explanation, or alternatives.

1. **Meaning and facts:** Does the draft fulfill the actual request? Are facts, references, quantities, causal claims, and personal details supported? Are quotations unchanged and appropriately attributed?
2. **Structure:** Does the order help the reader? In fiction, apply the numbered narrative audit to theme, agency, chronology, revelation, setting, dialogue, and closure. Keep motivated exceptions; do not maximize the count of human-leaning traits.
3. **Line editing:** Inspect for the seven LAMP categories: cliché; redundant exposition; excessive ornament; unclear sentence construction; missing specificity; awkward wording; unintended tense shifts. Repair the actual issue, preserving useful complexity and intentional repetition.
4. **Voice and restraint:** Would this author plausibly say this to this reader? Remove generic filler, forced quirks, overexplained subtext, and a repeated formula. Confirm that “more natural” has not made the text less accurate or less usable.

For a requested audit, give concise passage-specific observations and proposed changes. Distinguish `revise`, `intentional choice`, and `not applicable`. Do not assign an invented “human score.” A pass means the text meets the brief and the review found no unresolved material problem; it does not mean a detector would classify it as human.

## Evidence and detection boundaries

StoryScope is an observational study of a particular long-form fiction corpus and model versions, with LLM-assigned narrative labels. Its frequencies describe groups, not rules every human obeys. Its classifiers were not evaluations of Humanizy. Reversing observed traits has not been shown to produce better writing or defeat detectors.

Never promise undetectability, “100% human,” a Turnitin pass, or universal detector success. Do not present fabricated detector tests or scores. If detection is asked about, explain the limit briefly, then improve the actual writing. Do not add deliberate mistakes, invisible characters, homoglyphs, random punctuation, fake personal details, or false authorship statements to manipulate a score.

Do not silently submit user writing to external detection services. A requested evaluation requires the actual named service, access, and authorization to send that text; report only observed results, with the date and relevant limits. A low AI score neither proves originality nor substitutes for source attribution.

Research baseline: 6 November 2026. Consult [evidence-and-sources.md](references/evidence-and-sources.md) for provenance, coverage, limitations, and update guidance. Do not browse again for routine writing unless facts or the task require it.
