# Kavárna & bar U mlsné kočky — статический сайт

Монохромный сайт кофейни и бара с аккуратной типографикой, плавными анимациями и чистой навигацией.

## Структура

- `index.html` — главная страница.
- `gallery.html` — галерея.
- `menu.html` — меню.
- `about.html` — о нас.
- `contact.html` — контакты.
- `styles.css` — стили и анимации.
- `script.js` — reveal-on-scroll, текущий год в футере.
- `assets/black-cat.svg` — логотип.

## Запуск

- Откройте `cafe-site/index.html` напрямую, или
- поднимите локальный сервер и перейдите по адресу:
  - Python: `python -m http.server 8080` → http://localhost:8080/cafe-site/
  - Node: `npx serve -p 8080`

## Кастомизация

- Цвета и отступы: правьте CSS‑переменные в `:root` файла `styles.css`.
- Галерея/сетки: используйте классы `masonry-grid`, `photo-*`, `span-col-2`, `span-row-2`.
- Тексты разделов: редактируйте соответствующие HTML‑файлы.