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

    <button class="button" onclick="openLink('https://example.com/page1')">
        Заполнить договор
    </button>

    <button class="button" onclick="openLink('https://example.com/page2')">
        Скачать договор
    </button>

    <button class="button" onclick="openLink('https://example.com/page3')">
        Все документы
    </button>

    <script>
        // Инициализируем Telegram WebApp
        const tg = window.Telegram.WebApp;
        tg.ready();
        tg.expand(); // Растягиваем на весь экран

        function openLink(url) {
            // Открываем ссылку во внешнем браузере
            tg.openLink(url);
        }
    </script>
</body>
</html>
