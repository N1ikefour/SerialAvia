# Higgsfield — промпты и карта размещения для нового лендинга Serial Avia

## Как это работает

1. Рядом с файлом `index.html` создайте папку **`assets`**.
2. Генерируете в Higgsfield по промптам ниже → скачиваете → переименовываете файл **точно** как указано → кладёте в `assets/`.
3. Обновляете страницу — всё подхватится само. Пока файла нет, на его месте красивая тёмная заглушка, ничего не ломается.

Общие настройки: видео — **16:9**, лучшее качество, экспорт **MP4 (H.264)**. Фото — качество максимум, JPG/PNG (PNG переименуйте в `.jpg` — браузеру всё равно, либо поменяйте расширение в index.html).

Единый стиль всех генераций (уже вшит в промпты): cinematic, golden hour, тёмная премиальная цветокоррекция под дизайн сайта.

---

## 🎬 ВИДЕО №1 — главный экран (самое важное!)

**Файл:** `assets/hero.mp4` · 16:9 · 5–10 сек (зациклится сам)

```
Cinematic aerial drone shot slowly gliding over a turquoise tropical ocean
toward a paradise island with white sand beach and palm trees at golden hour,
warm sunlight glinting on gentle waves, a few overwater villas in the distance,
soft atmospheric haze, rich teal and amber color grade, dark moody premium
cinematography, smooth slow camera movement, photorealistic, 8k, no people,
no text, no watermarks
```

Совет: сгенерируйте 2–3 варианта и возьмите тот, где движение камеры самое плавное — это лицо сайта.

**Постер к видео (кадр-заставка):** `assets/hero-poster.jpg` — сгенерируйте фото тем же промптом (режим image), либо просто сделайте скриншот красивого кадра из видео.

---

## 🎬 ВИДЕО №10 — блок «Не нашли нужный тур?»

**Файл:** `assets/cta.mp4` · 16:9 · 5–8 сек

```
Cinematic slow motion shot from inside an airplane window at sunset, wing over
a sea of golden clouds, warm amber light flooding the cabin, dreamy travel
atmosphere, dark premium cinematic color grade, subtle camera drift,
photorealistic, no people, no text
```

---

## 📸 ФОТО — горящие туры (карточки 3:4 или 4:5, вертикальнее = лучше)

**№2 · Файл:** `assets/hot-turkey.jpg` — Турция

```
Luxury beach resort in Antalya Turkey at golden hour, infinity pool merging
with the Mediterranean sea, sun loungers with white umbrellas, dramatic warm
sunset light, dark premium cinematic color grade, professional travel
photography, photorealistic, no people, no text
```

**№3 · Файл:** `assets/hot-egypt.jpg` — Египет

```
Vibrant coral reef and crystal clear turquoise water of the Red Sea in Sharm
El Sheikh Egypt, luxury resort beach with jetty at sunset, desert mountains in
background, warm golden tones, dark premium cinematic color grade, professional
travel photography, photorealistic, no people, no text
```

**№4 · Файл:** `assets/hot-thailand.jpg` — Таиланд

```
Longtail boat floating in emerald water near limestone cliffs of Phuket
Thailand at golden hour, tropical Kata beach with palm trees, warm cinematic
sunset glow, dark premium color grade, professional travel photography,
photorealistic, no people, no text
```

---

## 📸 ФОТО — направления «Куда полетим?»

**№5 · Файл:** `assets/dest-maldives.jpg` — Мальдивы ⚠️ это самая большая карточка, генерируйте в **3:4 (портрет)**

```
Overwater villas on turquoise lagoon in the Maldives at dusk, wooden walkway
with warm lights, deep blue evening sky with golden horizon, luxurious serene
atmosphere, dark premium cinematic color grade, professional travel
photography, photorealistic, no people, no text
```

Остальные — **16:9 или 3:2 (горизонт)**:

**№6 · Файл:** `assets/dest-uae.jpg` — ОАЭ

```
Dubai skyline with Burj Khalifa at blue hour, golden city lights reflecting,
luxury futuristic atmosphere, dark premium cinematic color grade, professional
travel photography, photorealistic, no text
```

**№7 · Файл:** `assets/dest-vietnam.jpg` — Вьетнам

```
Emerald limestone karsts of Ha Long Bay Vietnam at golden hour, traditional
boat on calm water, misty atmosphere, warm sunset light, dark premium cinematic
color grade, professional travel photography, photorealistic, no text
```

**№8 · Файл:** `assets/dest-srilanka.jpg` — Шри-Ланка

```
Sri Lanka coastal train on ocean cliff at sunset, palm trees and turquoise
waves below, lush green tea plantation hills in distance, warm golden light,
dark premium cinematic color grade, professional travel photography,
photorealistic, no text
```

**№9 · Файл:** `assets/dest-russia.jpg` — Россия

```
Lake Baikal Russia with dramatic mountain shore at golden hour, crystal clear
water, epic siberian nature, warm sunset tones against deep blue sky, dark
premium cinematic color grade, professional landscape photography,
photorealistic, no people, no text
```

---

## 📸 ФОТО №11 — фон блока «Наши услуги»

**Файл:** `assets/services-bg.jpg` · **21:9 или 16:9 (максимально широкий)**

```
Dark minimalist world map made of tiny glowing dots on deep navy background,
elegant thin golden flight route lines connecting continents with small plane
icons, subtle warm glow at connection points, premium dark aesthetic,
lots of empty dark space, very subtle and low contrast, no text, no watermarks
```

Картинка вставится полупрозрачной (22%) с затемнением по краям — карточки услуг останутся читаемыми. Если получится слишком пёстро, перегенерируйте с добавкой «even darker, more minimal».

---

## 📸 ФОТО №12 — блок «О компании»

**Файл:** `assets/about.jpg` · **3:4 или 1:1**

```
Stylish travel planning flat lay on dark wooden desk: passport with boarding
passes, vintage compass, small globe, sunglasses, camera and a handwritten
travel journal, warm golden ambient light, cozy premium atmosphere, dark
cinematic color grade, professional photography, top-down view, no people,
no text, no watermarks
```

---

## Чек-лист файлов

| # | Файл | Тип | Формат |
|---|------|-----|--------|
| 1 | `assets/hero.mp4` + `assets/hero-poster.jpg` | видео + фото | 16:9 |
| 2 | `assets/hot-turkey.jpg` | фото | 3:4 |
| 3 | `assets/hot-egypt.jpg` | фото | 3:4 |
| 4 | `assets/hot-thailand.jpg` | фото | 3:4 |
| 5 | `assets/dest-maldives.jpg` | фото | 3:4 |
| 6 | `assets/dest-uae.jpg` | фото | 16:9 |
| 7 | `assets/dest-vietnam.jpg` | фото | 16:9 |
| 8 | `assets/dest-srilanka.jpg` | фото | 16:9 |
| 9 | `assets/dest-russia.jpg` | фото | 16:9 |
| 10 | `assets/cta.mp4` | видео | 16:9 |
| 11 | `assets/services-bg.jpg` | фото | 21:9 |
| 12 | `assets/about.jpg` | фото | 3:4 |

---

## ⚙️ Включить настоящий поиск туров (Tourvisor) — 30 секунд

1. Откройте https://serialavia.ru/podbor-tura → нажмите **Ctrl+U** (исходный код).
2. Найдите (Ctrl+F) слово **`tv-moduleid`** — рядом будет число, это ID вашего модуля.
3. В `index.html` внизу найдите `const TV_SEARCH_ID = '';` и впишите число: `const TV_SEARCH_ID = '12345';`
4. Если найдёте второй ID у блока горящих туров (`tv-hot`) — впишите его в `TV_HOT_ID`.

Готово — вместо демо-формы заработает реальный поиск по 80 туроператорам.

## 💡 Советы

- Видео для веба лучше сжать до ~5–8 МБ (например, на handbrake.fr или любом онлайн-компрессоре), иначе hero будет долго грузиться на мобильных.
- Если какой-то кадр не понравился — меняйте в промпте локацию/время суток, но оставляйте хвост про «dark premium cinematic color grade» — он держит единый стиль сайта.
- Страницу можно открыть просто двойным кликом по `index.html` — всё работает без сервера.
