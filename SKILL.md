---
name: narrative-prose
description: Draft, rewrite, and critique Chinese long-form narrative prose using a pre-extracted New Concept Writing style system. Use only when explicitly invoked as $narrative-prose.
---

# Narrative Prose

Use this skill only when the user explicitly invokes `$narrative-prose`.

This skill is a runtime writing system, not a live research workflow. The New Concept Writing influence has already been abstracted into reusable principles, modes, and revision criteria. During ordinary use, do not browse the web, search for winning works, or re-analyze source texts unless the user explicitly asks for fresh research.

## Load Order

Read these references before writing or revising:

1. `references/style-bible.md` for the fixed style system and anti-patterns.
2. `references/prose-framework.md` for the base prose architecture.
3. `references/mode-selector.md` for selecting the prose mode.
4. `references/revision-rubric.md` for critique, rewrite, and final self-check.

Read `references/source-index.md` only when the user asks where the style system came from or asks to refresh the research basis.

## Supported Tasks

- **Generate** a Chinese long-form narrative prose piece from a theme, memory, object, scene, relationship, place, or emotional target.
- **Rewrite** an existing draft while preserving its factual core and transforming its structure, rhythm, detail density, and ending.
- **Critique** a draft against the fixed style system and provide concrete revision actions.

## Runtime Workflow

1. Identify the user's task as generation, rewrite, critique, or mixed work.
2. Extract the available inputs: theme, material, narrator, audience, emotional temperature, length, constraints, and any forbidden content.
3. If the input lacks material needed for a credible 2500-4000 Chinese-character piece, ask at most three targeted questions. Ask about lived detail, relationship stakes, and ending direction before asking about wording preferences.
4. Select one primary mode from `mode-selector.md`; use a secondary mode only when the material clearly needs it.
5. Build the hidden working plan: surface event, deeper proposition, scene chain, emotional arc, image/object thread, sentence rhythm, and ending mechanism.
6. Output in this order unless the user requests otherwise:
   - `文章命题`
   - `叙事提纲`
   - `完整正文`
   - `风格自检`
7. Keep the self-check brief and specific. Mention no more than five issues or strengths.

## Defaults

- Language: Simplified Chinese.
- Length: 2500-4000 Chinese characters for the body when the user asks for a long piece and gives enough material.
- Voice: first person by default for memory-based prose; third person or second person only when the prompt, subject, or mode makes it stronger.
- Style: literary but concrete, personal but not self-indulgent, restrained but emotionally legible.
- Ending: return to an earlier object, sentence, place, or gesture; avoid slogan-like conclusions.

## Non-Negotiables

- Do not copy or closely paraphrase identifiable winning works, published essays, or user-provided reference samples.
- Do not invent personal facts and present them as the user's lived experience. If details are missing, use clearly fictionalized neutral scaffolding or ask.
- Do not explain the New Concept Writing research process during normal output. The skill should behave as if the style has already been internalized.
- Do not make the prose merely ornate. Every lyrical sentence must be tied to a person, object, scene, action, or change in understanding.
