---
name: seedance-anime-director
description: Create production-ready Seedance video prompts, anime scripts, storyboards, scene timelines, Thai dialogue, and cinematic anime scenes from ideas or reference images. Use for Seedance prompts, text-to-video, image-to-video, reference-to-video, anime shorts, action, fantasy, romance, slice of life, music videos, trailers, or general AI video planning; prioritize the user's Seedance 2.5 target without assuming unverified platform features.
---

# Seedance Anime Director

Turn even a brief idea into a coherent, timed production prompt. Default to Cinematic Japanese 2D Anime, English visual/technical instructions, and Thai spoken dialogue when speech serves the story. Respond with Thai summaries. Respect explicit user choices, including other languages and non-anime styles.

## Workflow

1. **Analyze intent.** Extract genre, theme, desired emotion, audience, motivation, constraints, and output mode. Preserve the user's central idea. Proceed with reasonable stated assumptions when enough information exists; ask only for essential missing references or unresolved identity mappings.
2. **Identify assets.** Inspect accessible images before describing them. Map each to a stable character, environment, style, prop, or opening-frame role. Read [character consistency](references/character-consistency.md). Never infer unseen clothing or pretend an unavailable image was inspected. If a required image is missing, request it; an explicitly labeled text-only draft may still be useful.
3. **Set duration and scene count.** Honor supplied values. Otherwise plan a 15-second editorial sequence and choose 2–4 scenes suited to the idea; this is a creative default, not a claimed platform limit. Read [scene timing](references/scene-timing.md) and the compatibility section in [prompt structure](references/prompt-structure.md). Distinguish total film length from supported generation clip length.
4. **Develop the story.** Establish beginning, development, climax, and resolution through a visible emotional change. Use [storytelling](references/storytelling.md); compress beats rather than forcing four separate scenes.
5. **Allocate time.** Use unequal durations where appropriate. Budget dialogue, reaction, action, camera travel, and transitions. Build contiguous half-open intervals from zero to the exact requested total. Simplify overloaded scenes.
6. **Direct each scene.** Specify composition, one primary camera behavior, timed character action, expression, eye line, secondary hair/clothing motion, and environmental response. Read [cinematography](references/cinematography.md) and [visual styles](references/anime-visual-styles.md).
7. **Direct speech and sound.** Read [Thai dialogue and audio](references/thai-dialogue-audio.md). Assign exact dialogue to named speakers with time windows, vocal character, emotion, delivery, ambience, effects, music, and lip-sync intent. Use silence when stronger. Do not imply native audio support without verification.
8. **Lock continuity.** Track pose, hands, props, screen direction, location, light, weather, outfit, and emotion across every cut. Describe motivated changes explicitly.
9. **Compile.** Use the twelve-part structure in [prompt structure](references/prompt-structure.md). Remove repetition and contradictions. Treat platform settings as separate UI selections only when verified; do not invent API parameters or reference syntax.
10. **Validate.** Apply [quality control](references/quality-control.md), fix failures, and deliver. Never promise perfect identity, exact lip sync, or deterministic rendering. Producing a prompt does not mean a video was generated or tested.

## Required output

**A. Creative Summary (Thai)** — Brief idea, story, scene count, emotional arc, and consequential assumptions.

**B. Scene Timeline (Thai)** — Table of scene, start–end, duration, key event, and speech window where applicable. Include total duration.

**C. FINAL SEEDANCE PROMPT (English + Thai Dialogue)** — Exactly one Markdown code block containing the complete actionable prompt. English for direction; Thai for exact spoken lines by default. Include no explanations to the user inside this block. For a film requiring separate renders, keep all labeled clip instructions in this same block and explain the assembly outside it.

**D. Optional Production Notes** — Include only necessary asset binding, supported UI settings, unverified capability limitations, or editing/audio fallback. Never claim a supplied reference tag is bound before it is actually attached.

## Examples

Read the closest example rather than loading everything:
- [Emotional anime](examples/emotional-anime.md): quiet emotional change and Thai dialogue.
- [Action anime](examples/action-anime.md): readable movement and restrained camera.
- [Image-to-video](examples/image-to-video.md): reference inspection and identity locks.
- [Multi-scene story](examples/multi-scene-story.md): five unequal scenes and continuity.

## Scope and installation

This skill creates production instructions; invoke a video tool only when requested and available. Do not substitute an image generator for video generation.

The portable source lives at `skills/seedance-anime-director`. To register in a Codex checkout supporting repository skills, copy this entire directory into `.agents/skills/seedance-anime-director/` at that repository root. For personal use, copy it into `~/.agents/skills/seedance-anime-director/`. Preserve existing installations; review differences before replacing them. Reload the session and confirm the skill appears in the available-skill list. If this client uses another skill registry, use its documented import mechanism; filesystem presence alone does not prove discovery.

Invoke with `$seedance-anime-director` or explicitly request the skill by name.
