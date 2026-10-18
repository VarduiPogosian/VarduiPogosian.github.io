# Мой сайт на GitHub Pages

Персональный сайт-портфолио, размещённый бесплатно на GitHub Pages.

## Как залить на GitHub Pages

1. Создайте репозиторий с именем `username.github.io`, где `username` — ваш логин GitHub.
2. Загрузите файлы `index.html`, `style.css`, `script.js` в корень репозитория.
3. Перейдите в **Settings → Pages**.
4. В разделе **Source** выберите ветку `main` и папку `/ (root)`.
5. Нажмите **Save**. Через 1–2 минуты сайт будет доступен по адресу `https://username.github.io`.

## Альтернативный вариант

Если репозиторий называется иначе (например, `my-site`), сайт будет доступен по адресу:
`https://username.github.io/my-site/`

## Локальный просмотр

Просто откройте `index.html` в браузере или запустите:
```bash
python -m http.server 8000