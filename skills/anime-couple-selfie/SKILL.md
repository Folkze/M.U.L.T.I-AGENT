---
name: anime-couple-selfie
description: Create an Anime couple selfie from reference images of two adult characters, preserving the female character's cartoon/anime style and the male character's semi-realistic anime style in a romantic half-body smartphone selfie. Use when the user requests this composition or invokes Anime couple selfie.
---

# Anime couple selfie

สร้างภาพเซลฟี่คู่รักผู้ใหญ่จากภาพอ้างอิงสองตัวละคร โดยให้ฝ่ายหญิงถือโทรศัพท์ รักษาความแตกต่างของสไตล์ตัวละคร และจัดองค์ประกอบครึ่งตัวแนวตั้ง 9:16

## Workflow

1. Use the user's reference images for both adult characters. A single reference containing both characters is also suitable. If either reference is missing, ask the user to upload the missing image before generating. If the intended characters or their roles are unclear, ask which references to use for the female and male characters.
2. Use the available image generation/editing tool with all relevant reference images attached as inputs. Follow the tool's instructions for uploaded images or local paths; inspect local images before editing. Do not replace the references with text-only descriptions.
3. Use the complete base prompt below. Preserve the recognizable identity and original style of each reference: large expressive cartoon/anime eyes for the female character and semi-realistic anime styling for the male character. Do not equalize their eye sizes or make the female character overly realistic.
4. Request a half-body, front-camera smartphone selfie at face level, in vertical 9:16 composition. The female character holds the phone at a natural arm-length distance; the male character gently holds her waist with one hand. Use natural selfie perspective and balanced facial structure, head sizes, and visibility. If the exact aspect ratio is unsupported, use the closest supported option and state the limitation.
5. Check the result for both faces being clearly visible, balanced presence, natural arms and hands, respectful waist contact, clean cropping, and consistent lighting. Refine with the image tool when possible if these requirements are visibly missed. Return the generated image with brief accompanying text.

## Base prompt

```text
Create an image of these two people together in one frame as a front-camera smartphone selfie of a romantic adult couple. The female character is holding the phone. Half-body composition, close face-level selfie angle, realistic arm-length distance, natural-looking arm.

The two characters stand close together in a warm, affectionate pose, gently leaning toward each other, with their faces slightly angled toward the camera. The male character gently holds the female character’s waist with one hand in a natural and respectful way. His hand rests softly around her waist, while the other hand or arm remains in its natural default position and does not need to be visible.

Preserve their original style differences. The female character must remain clearly cartoon/anime-stylized with large expressive anime eyes. Do not reduce her eye size or make her overly realistic. The male character should remain semi-realistic anime. Their eye sizes do not need to match.

Judge face size by facial structure only, not by eye size. Use realistic selfie perspective with natural wide-angle distortion, so the closer person appears slightly larger and the person farther back appears slightly smaller.

Keep both characters visually balanced, with equal presence in the frame. The female may appear slightly closer because she is holding the phone, but both faces should remain clearly visible, well-proportioned, and naturally harmonized. Maintain balanced head sizes, natural spacing, clean composition, no oversized arm or hand, no awkward cropping, and no distorted body proportions.

Unify the image with consistent lighting, shadows, color tone, and mood while preserving the style contrast between the two characters. Slightly blurred background. Cinematic Anime 2D, high detail, clean line art, polished shading, 9:16.
```
