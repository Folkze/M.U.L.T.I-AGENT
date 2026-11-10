# ลมริมหน้าต่าง

Example request: ใช้ภาพอ้างอิงทำอนิเมะ 8 วินาที ให้ตัวละครหันมองฝน

## A. Creative Summary (Thai)

ลมริมหน้าต่าง: เรื่องสั้น 8 วินาที 2 ฉาก เล่าอารมณ์ผ่านการกระทำและสีหน้า ใช้ Cinematic Japanese 2D Anime

## B. Scene Timeline (Thai)

| ฉาก | เวลา | ระยะเวลา | เหตุการณ์ |
| --- | --- | --- | --- |
| 1 | 0–3 s | 3 s | คงเฟรมเริ่มต้นและมองออกไป |
| 2 | 3–8 s | 5 s | ยิ้มบาง ๆ |

รวม 8 วินาที ใช้จุดตัดต่อเนื่อง ไม่มีเวลาทรานซิชันเพิ่มเติม

## C. FINAL SEEDANCE PROMPT (English + Thai Dialogue)

```text
VIDEO CONFIGURATION
Image-to-video; 8-second editorial sequence; 2 scenes; desired 16:9 composition.
REFERENCE ASSET MAPPING
Opening reference: the supplied portrait, used for identity, visible outfit, style, and first-frame composition. Bind it using the selected interface; no special tag syntax is assumed.
CHARACTER IDENTITY LOCK
For this illustrative inspected-reference scenario: oval face, brown almond-shaped eyes, shoulder-length black hair, ivory blouse with blue collar, small silver stud earrings, soft cel shading. Preserve visible traits; hands and lower outfit remain outside frame.
STORY OVERVIEW
From reflective stillness to a small moment of acceptance.
TIMESTAMPED SCENE BREAKDOWN
Scene 1, 0–3 s: Begin from the supplied image composition: an adult woman beside a window, hands below the frame. Hard cut at the endpoint.
Scene 2, 3–8 s: Continue in the same room and pose as her expression softens. End on the final state.
CAMERA DIRECTIONS
Scene 1: Medium locked framing matching the opening image.
Scene 2: Slow subtle dolly in, ending on her face.
CHARACTER ACTIONS
Scene 1: Her gaze shifts toward rain outside; her body remains still.
Scene 2: She blinks once, exhales, and forms a faint smile; only loose hair tips move in a light breeze.
THAI DIALOGUE
No dialogue, narration, or subtitles.
AUDIO DIRECTIONS
Soft exterior rain throughout; a quiet breath near 5 s; no music needed.
VISUAL STYLE
Cinematic Japanese 2D Anime; clean contours, stable cel shading, painted backgrounds, soft overcast directional light, muted blue shadows with warm skin accents. Keep faces legible.
CONTINUITY RULES
Carry each scene's final pose and prop state into the next shot. Preserve outfit, hair, eye color, setting, light direction, and screen direction. Keep hand occupancy and object contact physically coherent. Use only motivated movements.
QUALITY CONSTRAINTS
Stable facial identity and anatomy; readable hands when visible; no costume swaps, extra props, unintended text, or unexplained camera cuts. Keep motion restrained enough for the allocated time.
```

## D. Optional Production Notes

ตัวอย่างสมมติว่าตรวจภาพแล้วและพบลักษณะตามที่ระบุ ไม่ได้มีภาพจริงแนบในไฟล์นี้; เมื่อนำไปใช้ต้องตรวจภาพจริงและแทนรายละเอียดก่อนสร้าง Prompt

ตัวอย่างนี้เป็นแผนการผลิต ยังไม่ได้เรนเดอร์หรือยืนยันความสามารถเฉพาะ Seedance 2.5; ตรวจสอบโหมด ระยะคลิป และเสียงในผู้ให้บริการที่เลือกก่อนใช้ หากไม่รองรับเสียง ให้ใช้ส่วนเสียงเป็นบรีฟงานหลังการผลิต
