<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Сайт, созданный ИИ</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, sans-serif;
            background: linear-gradient(120deg, #f4f6f8, #e8ecf1);
            color: #333;
        }
        header {
            background: linear-gradient(120deg, #2c3e50, #34495e);
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
        nav {
            margin-top: 20px;
        }
        nav button {
            margin: 5px;
        }
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        h2 {
            color: #2c3e50;
        }
        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 16px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.12);
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card img {
            width: 100%;
            border-radius: 12px;
            margin-bottom: 10px;
        }
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 30px 20px;
        }
        button {
            background: #3498db;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 15px;
        }
        button:hover {
            background: #2980b9;
        }
    </style>
</head>
<body>

<header>
    <h1>Создание сайтов с помощью ИИ</h1>
    <p>Экспериментальный сайт, созданный искусственным интеллектом</p>
    <nav>
        <button onclick="document.getElementById('about').scrollIntoView()">О проекте</button>
        <button onclick="document.getElementById('ai').scrollIntoView()">Возможности ИИ</button>
        <button onclick="document.getElementById('contact').scrollIntoView()">Контакты</button>
        <button onclick="document.getElementById('creation').scrollIntoView()">Как создавался сайт</button>
    </nav>
</header>

<section id="about">
    <h2>О проекте</h2>
    <p>
        Этот сайт демонстрирует, как искусственный интеллект может участвовать
        в создании веб‑страниц: от структуры до дизайна.
    </p>
</section>

<section id="ai">
    <h2>Возможности ИИ</h2>
    <div class="cards">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1526378722484-bd91ca387e72" alt="Дизайн">
            <h3>Дизайн</h3>
            <p>Подбор цветовой схемы, шрифтов и визуального стиля.</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1518770660439-4636190af475" alt="Структура">
            <h3>Структура</h3>
            <p>Логичное размещение блоков и удобная навигация.</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c" alt="Код">
            <h3>Функционал</h3>
            <p>Кнопки, интерактивность и адаптивность под устройства.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Контакты</h2>
    <p>Нажмите кнопку ниже, чтобы перейти на другую вкладку.</p>
    <a href="https://google.com" target="_blank">
<button>Перейти на сайт</button>
</a>
</section>

<section id="creation">
    <h2>Как создавался этот сайт</h2>
    <p>
        Сайт был создан поэтапно с помощью искусственного интеллекта. Сначала
        была сгенерирована базовая HTML‑структура, затем добавлены стили CSS
        для визуального оформления. После этого ИИ предложил навигацию,
        интерактивные кнопки и изображения. Человек выступал в роли
        редактора, корректируя идеи и улучшая итоговый результат.
    </p>
</section>

<footer>
    <p>© 2026 | Сайт создан с помощью ИИ</p>
</footer>

</body>
</html>
