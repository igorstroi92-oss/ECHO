Готовый пакет для быстрого развертывания лендинга ECHO на GitHub Pages.

Структура:
```
ECHO/
 ├─ index.html
 ├─ assets/
 │   ├─ logo.svg
 │   ├─ favicon.png
 │   ├─ style.css
 │   ├─ script.js
 │   └─ manifest.json
 └─ README.md
```

Инструкция:
1. Скачай и распакуй архив.
2. Создай репозиторий на GitHub (например `ECHO-landing`).
3. Залей файлы в корень репозитория.
4. Включи GitHub Pages: Settings → Pages → Branch: main, folder: / (root).
5. Через минуту сайт будет доступен по адресу `https://<твоё_имя>.github.io/<repo>/`.

Автор и бренд:
`Igor Stroi — Founder of ECHO`

Дополнительно:
- Можно заменить `assets/favicon.png` на более подходящий.
- Для подключённой формы используется простая отправка через JS alert. Для продакшена подключите Formspree или Netlify Functions.
