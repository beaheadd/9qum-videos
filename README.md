# 9qum — видеоуроки Эльдара

Четыре курса, видео 720×1280 (9:16, H.264 + AAC, faststart — можно сразу встраивать в `<video>`), обложки 720×1280 JPG:

- **«Тогызкумалак с нуля»** — 24 урока на трёх языках (ru, en, kk)
  - `togyz/<lang>/<NN>.mp4` — урок NN (01…24), `<lang>` = `ru` | `en` | `kk`; `togyz/<lang>/<NN>.jpg` — обложка
- **«Шахматы с нуля»** — 28 уроков на русском
  - `chess/ru/<NN>.mp4` — урок NN (01…28); `chess/ru/<NN>.jpg` — обложка
- **«Овари с нуля»** — 28 уроков на русском
  - `oware/ru/<NN>.mp4` — урок NN (01…28); `oware/ru/<NN>.jpg` — обложка
- **«Мангала с нуля»** — 34 урока на русском
  - `mangala/ru/<NN>.mp4` — урок NN (01…34); `mangala/ru/<NN>.jpg` — обложка

`videos.json` — список всех уроков: `course` (`togyz` | `chess` | `oware` | `mangala`), язык, номер, `lesson_id` (как в программе курса на сайте: board, rook, knight, sow, capture…), модуль, название, описание для YouTube, длительность, прямые ссылки `video_url` и `cover_url`.

Прямые ссылки:
- `https://raw.githubusercontent.com/beaheadd/9qum-videos/main/togyz/ru/01.mp4`
- `https://raw.githubusercontent.com/beaheadd/9qum-videos/main/chess/ru/01.mp4`
- `https://raw.githubusercontent.com/beaheadd/9qum-videos/main/oware/ru/01.mp4`
- `https://raw.githubusercontent.com/beaheadd/9qum-videos/main/mangala/ru/01.mp4`

## welcome/ — «Что умеет 9qum» (приветствие с главной)
`welcome/<lang>.mp4` + `welcome/<lang>.jpg` для ru, kk, en, tr, fr, es, uz (720p, ~1 мин). Показывать каждому языку сайта свой ролик;
в `videos.json` — записи с `"course": "welcome"`, `"lang": "<код>"`.
