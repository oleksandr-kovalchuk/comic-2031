# Промпти для коміксу «Я · 2031»: один день мого життя у 33

Стиль: б'юті-фотосесія (фотореалізм, світло й глянець). Усі сцени вертикальні 4:5.

## Що підготувати

- **Мої фото:** 2–3 штуки, бажано в моїх окулярах. Потрібні лише для аркуша ref-me.
- **Фото чоловіка:** 1 чітке фото обличчя, бажано в його окулярах.
- **Фото Емочки:** 1 фото, де добре видно породу й забарвлення.

## Як генерувати

- Працюйте в **новому** чаті Gemini, не в тому, де генерували комікс.
- Спершу зробіть 2 аркуші персонажів, потім 12 сцен.
- Прикладайте файли **саме в тому порядку**, як указано над промптом.
- Якщо обличчя відрізняється, допишіть у тому ж чаті: `Keep the face exactly like in the attached images: <що виправити>`.
- Якщо обличчя все одно «пливе», додайте ще одне своє справжнє фото останнім файлом і допишіть: `The last attached photo is the same woman, use it for the face.`
- Якщо зникли окуляри, допишіть: `Add her eyeglasses exactly as in image 1, same frames.` Для чоловіка: `Add his eyeglasses exactly as in image 2, same frames.`
- Якщо вийшло квадратне фото, допишіть: `Make it vertical 4:5, same scene.`
- Готові фото можна класти в корінь проєкту: Claude сам перейменує й розкладе їх в `images/`.

| Файл | Що прикласти (у цьому порядку) | Що на фото |
|---|---|---|
| ref-me ✓ | 2–3 мої фото | Аркуш: я у 33 |
| ref-daughter ✓ | ref-me, фото чоловіка | Аркуш: донька, 4 роки |
| scene-01 | ref-me, фото чоловіка | 07:00 Прокидаюся вдома |
| scene-02 | ref-me | 07:30 Б'юті-рутина |
| scene-03 | ref-me, фото чоловіка, ref-daughter | 08:00 Сімейний сніданок |
| scene-04 | ref-me, фото Емочки | 08:30 Прогулянка з Емочкою |
| scene-05 | ref-me | 09:00 Приїжджаю в салон |
| scene-06 | ref-me | 10:00 Навчання з брів |
| scene-07 | ref-me | 12:00 Обід із подружками |
| scene-08 | ref-me | 13:30 Постійна клієнтка |
| scene-09 | ref-me | 15:00 Масаж |
| scene-10 | ref-me, ref-daughter | 16:30 Озеро з донькою |
| scene-11 | ref-me | 18:00 Онлайн-спільнота |
| scene-12 | ref-me, фото чоловіка, ref-daughter, фото Емочки, scene-03 | 19:00–22:00 Вечір із сім'єю |

---

## Аркуш ref-me · прикласти 2–3 мої фото

```
Create a photo reference sheet of the woman from the attached photos at age 33. Keep exactly the same face: face shape, eyes, brows, nose, lips, skin tone and hair color. Long glossy well-groomed hair below the shoulders with soft waves, toned slim healthy figure, light natural makeup, perfectly groomed brows, small gold earrings. She wears her eyeglasses exactly as in the attached photos (same frame shape and color); if the photos show no glasses, give her elegant thin gold-rimmed eyeglasses. Glasses on in all four shots. Layout 2x2 on a plain soft-beige studio backdrop: front close-up portrait, 3/4 portrait, profile portrait, full-body standing pose in a cream silk blouse and high-waisted beige trousers. Same lighting in all four. Photorealistic beauty editorial photography, soft diffused light, glowing skin with natural texture, crisp detail on brows and lashes, pastel pink and champagne-gold color grading. Square 1:1. No text, no watermark.
```

## Аркуш ref-daughter · прикласти: 1) ref-me, 2) фото чоловіка

```
Create a photo reference sheet of the 4-year-old daughter of the two people in the attached images (image 1 is the mother, image 2 is the father). A cheerful little girl who naturally resembles both parents: hair color and eye color taken from the parents, shoulder-length hair in two small ponytails, round rosy cheeks, bright smile. Outfit: light pink cotton dress and white sneakers. Layout 2x2 on a plain soft-beige studio backdrop: front close-up portrait, 3/4 portrait, profile portrait, full-body standing pose. Same lighting in all four. Photorealistic editorial photography, soft diffused light, natural skin texture, pastel pink and champagne-gold color grading. Square 1:1. No text, no watermark.
```

---

## Сцена 1 · 07:00 · прикласти: 1) ref-me, 2) фото чоловіка

```
Vertical 4:5. Early morning in a spacious, bright bedroom of our own modern house: large windows, warm morning sun, light linen bedding, elegant calm interior in cream and soft beige. The woman from image 1 sits up in bed in light silk pajamas, long hair loose, stretching gently and looking around with a soft, grateful smile. Her husband from image 2 lies beside her, just waking up and smiling at her sleepily. The husband always wears his eyeglasses: exactly the same frames as in image 2 (if image 2 shows none, simple thin dark-rimmed eyeglasses). Camera at the foot of the bed, slightly to the side. Keep every face exactly as in the attached references (same face shape, eyes, brows, nose, lips, skin tone, hair color). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33, with long glossy well-groomed hair and a toned slim figure. Photorealistic beauty editorial photography, soft diffused light, glowing skin with natural texture, crisp detail on brows and lashes, clean airy look, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```

## Сцена 2 · 07:30 · прикласти: 1) ref-me

```
Vertical 4:5. Slow morning beauty routine in a bright, elegant bathroom with a marble vanity: the woman from image 1, in a soft satin robe, applies face serum with her fingertips. Skincare bottles, a jade roller and makeup brushes on the counter. Her long glossy hair is freshly styled in soft waves, light natural makeup, perfect brows. Calm, confident, feminine mood, toned slim figure. Camera from the side at 3/4, face clearly visible; the mirror is only partly in frame, without a full reflection. Keep the face exactly as in the attached reference (same face shape, eyes, brows, nose, lips, skin tone, hair color). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33. Photorealistic beauty editorial photography, soft diffused light, glowing skin with natural texture, crisp detail on brows and lashes, clean airy look, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```

## Сцена 3 · 08:00 · прикласти: 1) ref-me, 2) фото чоловіка, 3) ref-daughter

```
Vertical 4:5. Unhurried family breakfast in a beautiful modern kitchen with a large island and morning sun. The woman from image 1 (cream silk blouse, beige trousers, long glossy hair) and her husband from image 2 cook together: he pours coffee, she puts pancakes and berries on plates. The husband always wears his eyeglasses: exactly the same frames as in image 2 (if image 2 shows none, simple thin dark-rimmed eyeglasses). Their 4-year-old daughter from image 3 sits at the island in a kindergarten outfit with a small backpack beside her, laughing. Warm, loving mood, all three faces clearly visible. Keep every face exactly as in the attached references (same face shape, eyes, brows, nose, lips, skin tone, hair color). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33, with a toned slim figure. Photorealistic beauty editorial photography, soft diffused light, glowing skin with natural texture, clean airy look, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```

## Сцена 4 · 08:30 · прикласти: 1) ref-me, 2) фото Емочки

```
Vertical 4:5. Morning walk near our house: the woman from image 1 (cream silk blouse, beige trousers, light beige blazer, elegant loafers, long glossy hair) walks the dog from image 2 on a leash through a green yard with a neat lawn, young trees and flowers, the house softly blurred behind. Fresh air, soft morning sun, calm unhurried mood; she smiles down at the dog. Keep the dog exactly as in image 2 (breed, size, coat color and markings). Keep the woman's face exactly as in image 1 (same face shape, eyes, brows, nose, lips, skin tone, hair color). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33, with a toned slim figure. Photorealistic beauty editorial photography, soft diffused light, glowing skin with natural texture, clean airy look, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```

## Сцена 5 · 09:00 · прикласти: 1) ref-me

```
Vertical 4:5. The woman from image 1 (cream silk blouse, beige trousers, light beige blazer, small gold earrings, long glossy hair) steps out of her white premium SUV, car keys in hand. The car is parked in front of her small but very stylish beauty salon on a charming old European street in Ternopil, Ukraine: a large glass storefront, warm interior light, plants, elegant furniture and shelves with cosmetics visible inside. Confident, happy expression, face clearly visible. No signboards or hanging signs anywhere; the car has no logos or readable text. No second pair of glasses in her hands. Keep the face exactly as in the attached reference (same face shape, eyes, brows, nose, lips, skin tone, hair color). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33, with a toned slim figure. Photorealistic beauty editorial photography, soft diffused light, glowing skin with natural texture, clean airy look, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```

## Сцена 6 · 10:00 · прикласти: 1) ref-me

```
Vertical 4:5. Theory day of a brow training course in a bright, stylish classroom inside her salon. The woman from image 1 (cream silk blouse, light beige blazer, long glossy hair) stands next to a large screen showing a brow shape diagram and a color wheel of brow pigments (no readable text), explaining with a pen in her hand. Five female students of different appearances sit at a long white table with notebooks, pigment swatches and brow mapping tools, listening with interest. Confident, warm mentor energy, her face clearly visible. Keep her face exactly as in the attached reference (same face shape, eyes, brows, nose, lips, skin tone, hair color). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33, with a toned slim figure. Photorealistic beauty editorial photography, soft diffused light, glowing skin with natural texture, crisp detail on brows, clean airy look, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```

## Сцена 7 · 12:00 · прикласти: 1) ref-me

```
Vertical 4:5. Lunch with girlfriends in a beautiful restaurant with greenery and soft daylight. The woman from image 1 (cream silk blouse, light beige blazer, long glossy hair) and three friends who look clearly different from her (a blonde with a short bob, a brunette with curly hair, a redhead) sit at a round table with elegant plates, cups of coffee and glasses of prosecco. They laugh and share news; one friend shows travel photos on her phone. Relaxed, joyful mood, the woman's face clearly visible. Keep her face exactly as in the attached reference (same face shape, eyes, brows, nose, lips, skin tone, hair color). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33. Photorealistic beauty editorial photography, soft diffused light, glowing skin with natural texture, clean airy look, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```

## Сцена 8 · 13:30 · прикласти: 1) ref-me

```
Vertical 4:5. In her stylish salon (soft pink and beige interior, elegant furniture, shelves with cosmetics): the woman from image 1 (cream silk blouse, long glossy hair loose over her shoulders) has just finished brows for a long-time regular client, a young beautiful woman around 25 with long glossy dark-brunette wavy hair who looks clearly different from her. The client sits in a beauty chair and smiles at a small hand mirror; the woman stands beside her holding a brow brush, both laughing like old friends. No wall mirrors, no reflections. The woman's face clearly visible. Keep her face exactly as in the attached reference (same face shape, eyes, brows, nose, lips, skin tone, hair color). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33. Photorealistic beauty editorial photography, soft diffused light, glowing skin with natural texture, crisp detail on brows, clean airy look, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```

## Сцена 9 · 15:00 · прикласти: 1) ref-me

```
Vertical 4:5. Self-care time in a calm luxury spa: the woman from image 1 lies face down on a massage table, covered with a white towel up to the shoulders, her long glossy hair gathered in a loose bun, eyes closed, deeply relaxed and smiling slightly. Her head is turned toward the camera so her face is clearly visible. A massage therapist's hands rest on her shoulders, the therapist mostly out of frame. Candles, eucalyptus, soft warm light. Keep her face exactly as in the attached reference (same face shape, eyes, brows, nose, lips, skin tone, hair color). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33. Photorealistic beauty editorial photography, soft diffused light, glowing skin with natural texture, clean airy look, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```

## Сцена 10 · 16:30 · прикласти: 1) ref-me, 2) ref-daughter

```
Vertical 4:5. Golden afternoon by a lake: the woman from image 1 (cream silk blouse, beige trousers, long glossy hair moving in the breeze) crouches at the shore and hugs her 4-year-old daughter from image 2. They feed ducks from a small paper bag of grain, laughing; ducks on the calm water, reeds, warm golden light. Tender, joyful mother-and-daughter moment, both faces clearly visible. Keep both faces exactly as in the attached references (same face shape, eyes, brows, nose, lips, skin tone, hair color). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33, with a toned slim figure. Photorealistic beauty editorial photography, soft diffused light, glowing skin with natural texture, clean airy look, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```

## Сцена 11 · 18:00 · прикласти: 1) ref-me

```
Vertical 4:5. Cozy home office in the early evening: the woman from image 1 (soft cream knit top, long glossy hair) sits at a desk with a laptop that shows an online community page with a grid of students' brow work photos (no readable text). A ring light and a small microphone stand on the desk; she is recording a video review and points at one brow photo on the screen with a stylus, focused and kind. Warm table lamp, plants, shelves with books. Her face clearly visible. Keep her face exactly as in the attached reference (same face shape, eyes, brows, nose, lips, skin tone, hair color). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33. Photorealistic beauty editorial photography, soft diffused warm light, glowing skin with natural texture, clean look, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```

## Сцена 12 · 19:00–22:00 · прикласти: 1) ref-me, 2) фото чоловіка, 3) ref-daughter, 4) фото Емочки, 5) scene-03

```
Vertical 4:5. Evening at home with the whole family in a cozy living room with warm lamplight. The woman from image 1 (soft cream knit cardigan, long glossy hair loose) and her husband from image 2 sit close together on a large sofa; their 4-year-old daughter from image 3 laughs on her dad's lap; the dog from image 4 lies at their feet. The husband always wears his eyeglasses: exactly the same frames as in image 2 (if image 2 shows none, simple thin dark-rimmed eyeglasses). Image 5 is an earlier photo of the same family: the husband must look exactly like the man in image 5 (face, hair, eyeglasses). An open kitchen with a just-finished family dinner softly blurred behind. Calm, happy, loving mood, all faces clearly visible. Keep every face exactly as in the attached references (same face shape, eyes, brows, nose, lips, skin tone, hair color), and the dog exactly as in image 4 (breed, size, coat color and markings). She has fair skin, blue-grey eyes and light-brown hair, exactly as in image 1. The woman always wears her eyeglasses: exactly the same frames as in image 1 (same shape and color). The woman is 33. Photorealistic beauty editorial photography, soft warm light, glowing skin with natural texture, pastel pink and champagne-gold color grading, high-end lifestyle magazine quality. Leave calm, uncluttered space at the top of the frame. No text, no watermark, no frames or borders.
```
