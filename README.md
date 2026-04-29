<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Мои ссылки</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        body {
            font-family: system-ui, -apple-system, sans-serif;
            padding: 20px;
            margin: 0;
            background: var(--tg-theme-bg-color);
            color: var(--tg-theme-text-color);
        }
        .button {
            display: block;
            width: 100%;
            padding: 14px;
            margin: 10px 0;
            background: var(--tg-theme-button-color);
            color: var(--tg-theme-button-text-color);
            border: none;
            border-radius: 10px;
            font-size: 16px;
            cursor: pointer;
            text-align: center;
        }
        .title {
            text-align: center;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <h2 class="title">📌 Полезные ссылки</h2>

<button class="button" onclick="openLink('https://docs.google.com/your-doc')">
    Заполнить договор
</button>

<button class="button" onclick="openLink('https://disk.yandex.ru/your-file.pdf')">
    Скачать договор
</button>

<button class="button" onclick="openLink('https://ваш-сайт.com/documents')">
    Все документы
</button>

</body>
</html>
