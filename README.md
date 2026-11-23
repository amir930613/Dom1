# Дом — 3D-прогулка

Сайт разбит на небольшие файлы, каждый меньше 25 МБ (лимит загрузки через сайт GitHub).

- `index.html` — страница
- `assets/style.css`, `assets/meta.js`, `assets/app.js` — оформление и код
- `assets/sky.hdr` — небо
- `assets/dom.glb.part1`, `assets/dom.glb.part2` — 3D-модель дома (склеивается в браузере)

Открывать через GitHub Pages (Settings → Pages → Branch: main, папка / root).
При двойном клике по index.html на компьютере модель не загрузится — браузер блокирует загрузку файлов с диска. Для локальной проверки: `python -m http.server` в этой папке и открыть http://localhost:8000
