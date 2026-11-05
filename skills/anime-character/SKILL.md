---
name: anime-character
description: Generate an Anime character from an uploaded reference image, preserving facial identity and the exact outfit in a full-body cinematic 2D anime illustration with vertical 9:16 composition. Use when the user requests this character transformation or invokes Anime character.
---

# Anime character

สร้างภาพตัวละครอนิเมะจากภาพอ้างอิงที่ผู้ใช้อัปโหลด โดยรักษาเอกลักษณ์ใบหน้าและชุดเดิมให้ใกล้เคียงภาพต้นฉบับที่สุด

## Workflow

1. Use the uploaded reference image as the main character reference. If no reference image is available, ask the user to upload one before generating. If multiple images contain different characters and the intended character is unclear, ask which reference to use.
2. Use the available image generation/editing tool with the actual reference image attached as an input. Follow that tool's instructions for referencing uploaded images or local image paths; inspect local images before editing. Do not substitute a text-only reconstruction of the reference.
3. Use the prompt below as the base prompt. Incorporate the user's requested pose, body posture, facial expression, lighting, background, or cinematic atmosphere while preserving facial identity and clothing. Do not invent changes to the face or outfit. If essential outfit details are outside the reference frame, request a fuller reference when exact preservation depends on them.
4. Request a full-body vertical 9:16 image at 4K resolution when supported. Keep the entire character, including feet, in frame. If the tool cannot produce the requested resolution or aspect ratio, use the closest supported option and state the actual limitation; do not claim an unverified 4K output.
5. Return the generated image. Keep accompanying text brief. If visible identity or clothing details differ materially from the reference, refine the result with the image tool when possible rather than claiming exact fidelity.

## Base prompt

```text
Use the uploaded reference image as the main character reference. Create a full-body anime character in Cinematic Anime 2D style, 4K resolution, vertical 9:16 composition.

Preserve the character’s facial identity as closely as possible: keep the same face shape, eye shape, eye size, eyebrows, nose, lips, hairstyle, hair volume, glasses, and overall facial impression from the reference image. Do not redesign, simplify, or beautify the face too much. The face should remain highly recognizable from the reference.

Preserve the character’s clothing exactly as in the reference image. Do not redesign, restyle, replace, simplify, or recolor any part of the outfit. Keep the same clothing design, colors, layers, patterns, accessories, and overall appearance of the outfit as closely as possible.

You may change only the pose, body posture, facial expression, lighting, background, and cinematic atmosphere, while keeping the face and outfit faithful to the reference.

Full body view, detailed anime rendering, clean line art, cinematic lighting, expressive emotion, high-quality 2D anime illustration, sharp details.
```
