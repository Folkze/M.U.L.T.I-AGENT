# ร่มคันเดียว

Example request: สร้างอนิเมะโรแมนติก 15 วินาที 5 ฉาก ตัวละครผู้ใหญ่สองคนแบ่งร่มกัน

## A. Creative Summary (Thai)

ร่มคันเดียว: เรื่องสั้น 15 วินาที 5 ฉาก เล่าอารมณ์ผ่านการกระทำและสีหน้า ใช้ Cinematic Japanese 2D Anime

## B. Scene Timeline (Thai)

| ฉาก | เวลา | ระยะเวลา | เหตุการณ์ |
| --- | --- | --- | --- |
| 1 | 0–2 s | 2 s | พบกันกลางฝน |
| 2 | 2–5 s | 3 s | เสนอที่หลบฝน |
| 3 | 5–9 s | 4 s | ก้าวเข้ามาใต้ร่ม |
| 4 | 9–12 s | 3 s | ตอบรับด้วยรอยยิ้ม |
| 5 | 12–15 s | 3 s | เดินไปด้วยกัน |

รวม 15 วินาที ใช้จุดตัดต่อเนื่อง ไม่มีเวลาทรานซิชันเพิ่มเติม

## C. FINAL SEEDANCE PROMPT (English + Thai Dialogue)

```text
VIDEO CONFIGURATION
Text-to-video; 15-second editorial sequence; 5 scenes; desired 16:9 composition.
REFERENCE ASSET MAPPING
No references supplied; original fictional adult couple. If references are later supplied, inspect them and replace these invented profiles before generation.
CHARACTER IDENTITY LOCK
Man: short dark hair, brown eyes, navy coat, gray trousers. Woman: chin-length chestnut hair, brown eyes, cream coat, teal scarf. One red umbrella, always in the man’s right hand.
STORY OVERVIEW
From distance through a generous gesture to shared connection.
TIMESTAMPED SCENE BREAKDOWN
Scene 1, 0–2 s: An adult man stands screen left holding an open red umbrella in his right hand. An adult woman waits screen right outside its cover. Hard cut at the endpoint.
Scene 2, 2–5 s: The man shifts the umbrella canopy toward the woman without changing hands. Hard cut at the endpoint.
Scene 3, 5–9 s: The woman takes one step left into the canopy shelter. Hard cut at the endpoint.
Scene 4, 9–12 s: They exchange a small smile under the umbrella. Hard cut at the endpoint.
Scene 5, 12–15 s: Both walk toward screen right beneath the same canopy. End on the final state.
CAMERA DIRECTIONS
Scene 1: Wide locked shot.
Scene 2: Medium two-shot, locked.
Scene 3: Medium locked two-shot on the same side of the axis.
Scene 4: Close two-shot with a slight dolly in.
Scene 5: Wide locked shot.
CHARACTER ACTIONS
Scene 1: They notice each other across a single step of distance.
Scene 2: He tilts his head invitingly; she glances at the dry space.
Scene 3: He holds the shaft steadily in his right hand; she stops beside him and speaks.
Scene 4: Their shoulders relax; their eyes meet briefly, then turn toward the path.
Scene 5: The man continues carrying the umbrella in his right hand; their pace matches.
THAI DIALOGUE
Woman, 7–8.5 s: "ขอบคุณนะ". Soft adult feminine voice, warm and slightly hesitant. Only her mouth speaks.
AUDIO DIRECTIONS
Continuous light rain, damp footsteps at 5–6 s and 12–15 s. Soft piano swells after the spoken line. Keep rain and music below dialogue.
VISUAL STYLE
Cinematic Japanese 2D Anime; clean contours, stable cel shading, painted backgrounds, soft overcast directional light, muted blue shadows with warm skin accents. Keep faces legible.
CONTINUITY RULES
Carry each scene's final pose and prop state into the next shot. Preserve outfit, hair, eye color, setting, light direction, and screen direction. Keep hand occupancy and object contact physically coherent. Use only motivated movements.
QUALITY CONSTRAINTS
Stable facial identity and anatomy; readable hands when visible; no costume swaps, extra props, unintended text, or unexplained camera cuts. Keep motion restrained enough for the allocated time.
```

## D. Optional Production Notes

หากระบบไม่รองรับห้าฉากในคลิปเดียว ให้สร้างแยกตามขีดจำกัดที่ตรวจสอบแล้วและตัดต่อบน Timeline เดิม; ใช้ hard cuts ไม่เพิ่มเวลาทรานซิชัน

ตัวอย่างนี้เป็นแผนการผลิต ยังไม่ได้เรนเดอร์หรือยืนยันความสามารถเฉพาะ Seedance 2.5; ตรวจสอบโหมด ระยะคลิป และเสียงในผู้ให้บริการที่เลือกก่อนใช้ หากไม่รองรับเสียง ให้ใช้ส่วนเสียงเป็นบรีฟงานหลังการผลิต
