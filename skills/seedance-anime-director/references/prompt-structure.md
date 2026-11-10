# Prompt structure and platform compatibility

## Compatibility ledger

Last reviewed: 2026-11-10. No authoritative Seedance 2.5 documentation was available in the task's supplied sources. **No version-specific platform capability is confirmed by this package.** The requested model target is not evidence of its release, availability, input modes, audio generation, or limits.

| Class | What this package can assert | How to use it |
| --- | --- | --- |
| Confirmed platform capabilities | None independently verified for Seedance 2.5 | Populate only from official documentation or the actual selected provider UI |
| Recommended prompting techniques | Scene timing, identity descriptions, restrained camera instructions, continuity, exact dialogue scripts | Natural-language production intent; not guaranteed controls |
| Optional experimental techniques | Timestamp adherence, multi-shot generation, reference tags such as @image1, native Thai audio, lip synchronization | Use only after checking support; otherwise use explicit prose mapping or postproduction |

Before platform-specific delivery, check the exact provider/model version, available input modes, clip durations, aspect ratios, resolution, asset count/types, reference binding, native audio/language support, and any negative-prompt field. Record source URL or UI identifier, date, model/provider, supported value, and remaining uncertainty here when verified. Do not borrow limits from a different Seedance version or a third-party wrapper. Never invent API field names.

If verification is unavailable, provide a model-neutral Seedance-targeted production prompt and disclose this briefly in production notes. Desired duration/aspect ratio are editorial intent, not proven accepted settings. For unsupported multi-scene or long-form output, render supported individual clips and edit them together. If audio is unavailable, produce Thai voice-over/dialogue, Foley, and music in postproduction. Do not claim these fallback tools are included in Seedance.

Update this ledger and relevant reference guidance for future versions without rewriting the main workflow.

## Final prompt template

Fill every section with concise instructions; use `None` when genuinely inapplicable. Scene-level directions are authoritative; global directions supply defaults. Resolve conflicts before output.

1. VIDEO CONFIGURATION: target model when selected, input mode, editorial duration, desired frame composition/aspect ratio, scene count. Do not include unsupported API syntax.
2. REFERENCE ASSET MAPPING: asset label → role; attach using the actual interface. Use @image1 only if confirmed by that interface.
3. CHARACTER IDENTITY LOCK: stable named profiles and immutable traits.
4. STORY OVERVIEW: motivation, obstacle, visible emotional turn, ending.
5. TIMESTAMPED SCENE BREAKDOWN: scene ID, start–end, setting, initial state, key beats, final state, transition.
6. CAMERA DIRECTIONS: scene ID → framing, angle, primary movement, focus target.
7. CHARACTER ACTIONS: scene ID → ordered body, eyes, face, hands, and secondary motion.
8. THAI DIALOGUE: speaker, exact quoted line, start–end, vocal character, emotion, delivery; or no dialogue.
9. AUDIO DIRECTIONS: ambience, timed effects, music dynamics and speech priority; production audio intent if native generation is unavailable.
10. VISUAL STYLE: coherent linework, shading, palette, lighting, atmosphere, animation treatment.
11. CONTINUITY RULES: persistent state and motivated changes; matching end/start frames where useful.
12. QUALITY CONSTRAINTS: a short list of relevant risks, e.g. stable face/outfit, readable hands, no unintended text, no unmotivated cuts.

For concise outputs, sections 6–9 may refer to scene IDs rather than repeat the scene descriptions. Do not use unexplained placeholders in a final production prompt. Negative constraints belong in natural language unless a separate negative-prompt control is verified.
