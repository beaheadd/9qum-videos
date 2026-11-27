# 9qum — видеоуроки Эльдара

Два курса, видео 720×1280 (9:16, H.264 + AAC, faststart — можно сразу встраивать в `<video>`), обложки 720×1280 JPG:

- **«Тогызкумалак с нуля»** — 24 урока на трёх языках (ru, en, kk)
  - `togyz/<lang>/<NN>.mp4` — урок NN (01…24), `<lang>` = `ru` | `en` | `kk`; `togyz/<lang>/<NN>.jpg` — обложка
- **«Шахматы с нуля»** — 28 уроков на русском
  - `chess/ru/<NN>.mp4` — урок NN (01…28); `chess/ru/<NN>.jpg` — обложка

`videos.json` — список всех уроков: `course` (`togyz` | `chess`), язык, номер, `lesson_id` (как в программе курса на сайте: board, rook, knight, castling…), модуль, название, описание для YouTube, длительность, прямые ссылки `video_url` и `cover_url`.

Прямые ссылки:
- `https://raw.githubusercontent.com/beaheadd/9qum-videos/main/togyz/ru/01.mp4`
- `https://raw.githubusercontent.com/beaheadd/9qum-videos/main/chess/ru/01.mp4`
