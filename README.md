# object 02

Сайт-портфолио студии object 02: дизайн и разработка сайтов, интерфейсов, графики и видео.

Статичный сайт без сборки: `index.html` + папка `assets/` (обложки, изображения, видео). Шрифт Geist Mono подключается с Google Fonts.

## Локально

Откройте `index.html` в браузере или запустите любой статичный сервер:

```bash
npx serve .
```

## Публикация на GitHub Pages

1. Создайте репозиторий и загрузите в него содержимое этой папки (`index.html`, `assets/`, `.nojekyll`, `README.md`).
2. В репозитории: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, ветка `main`, папка `/ (root)`.
3. Через минуту сайт будет доступен по адресу `https://<username>.github.io/<repo>/`.

Свой домен: добавьте файл `CNAME` с именем домена и настройте DNS по [инструкции GitHub](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Структура

```
index.html   — вся разметка, стили и скрипты
assets/      — изображения (jpg/webp), видео (mp4), og.jpg для превью ссылки
.nojekyll    — отключает обработку Jekyll на GitHub Pages
```
# studio-site
