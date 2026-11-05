# Humanizy

A Codex writing skill for natural, specific prose that preserves the writer's intent and voice. Built from StoryScope, research on expert editing, and evidence on creative diversity, academic writing, and detector limitations.

Humanizy includes a **30-check narrative audit**, the human/AI measurements behind each check, model-specific findings, a catalogue of **304 StoryScope measurement features**, and a required revision pass. It has separate handling for everyday prose, fiction, and evidence-heavy writing.

## Use

```text
$humanizy Rewrite this email in my voice. Keep the facts and the deadline.
$humanizy Draft a short story from this premise.
$humanizy Audit this essay for clarity without changing my argument.
```

Codex's native invocation is `$humanizy`. `/humanizy` is a text alias defined by the supplied global instructions, not an application slash command registered by this repository. The alias works when the message reaches the assistant. Automatic selection remains enabled.

## Install in Codex

Copy the entire `humanizy` folder, including `references` and `agents`, into a user skill directory recognized by your Codex installation. This task's desktop installation uses `~/.codex/skills/humanizy`; current OpenAI documentation also describes `~/.agents/skills`. Use one location, not duplicate copies in multiple discovery roots. If `CODEX_HOME` is customized, account for that installation's configuration.

For default use across projects, append the block in [settings/codex-global-instructions.md](settings/codex-global-instructions.md) to your existing `~/.codex/AGENTS.md` (or the equivalent under `CODEX_HOME`), preserving existing instructions. A global `AGENTS.override.md`, if present, takes precedence. Restart Codex or open a fresh chat if a newly installed skill is not listed.

See [OpenAI's skills documentation](https://learn.chatgpt.com/docs/build-skills) and [global AGENTS.md guidance](https://learn.chatgpt.com/docs/agent-configuration/agents-md). Other computers and cloud runtimes need their own installed skill files.

## ChatGPT default

The text in [settings/chatgpt-custom-instructions.txt](settings/chatgpt-custom-instructions.txt) is a compact, self-contained default for ChatGPT's custom instructions. Merge it with existing preferences in **Settings → Personalization → Edit ChatGPT custom instructions**, then save. It does not install or load the full local Codex skill in ChatGPT.

The settings page may also offer separate Codex custom instructions synced across desktop and web. Those can carry the default preference; the complete local skill still needs to be available in the environment doing the work.

## What the evidence supports

StoryScope v6 reports 93.2% macro-F1 for human/AI classification using narrative features alone, with LLMs assigning those features from full stories. Its corpus concerns long fiction and specific model versions. The [narrative audit](humanizy/references/narrative-audit.md) records all 30 core features and measured values. Humanizy turns the results into **editorial checks**, not empirically proven interventions or rigid laws about human writing.

The [evidence ledger](humanizy/references/evidence-and-sources.md) records source access, methods, limits, additional findings, and reporting inconsistencies. Research review date: **6 November 2026**. This was a focused review of relevant sources, not every page on the internet.

Humanizy does **not** guarantee passing Turnitin or any other AI detector. No external detector scores or controlled writing-quality improvements are claimed. The aim is better writing, accurate content, and meaningful author control.

## Files

- [Skill instructions](humanizy/SKILL.md)
- [Narrative audit](humanizy/references/narrative-audit.md)
- [Evidence and sources](humanizy/references/evidence-and-sources.md)
- [Complete feature catalogue](humanizy/references/storyscope-feature-catalogue.md)
- [Source attribution](humanizy/references/third-party-notices.md)

## Validation

The package is checked with Codex's skill validator, local reference checks, and scenario-based editorial review. These checks validate packaging and inspect instruction behavior; they are not detector certification or an empirical benchmark.
