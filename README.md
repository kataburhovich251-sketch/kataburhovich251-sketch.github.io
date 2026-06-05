<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Портфолио - Екатерина Бурхович</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f4f4f4;
        }
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-align: center;
            padding: 60px 20px;
        }
        header h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }
        header p {
            font-size: 20px;
            opacity: 0.9;
        }
        section {
            max-width: 1100px;
            margin: 40px auto;
            padding: 20px;
            background: white;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        section h2 {
            color: #667eea;
            margin-bottom: 20px;
            font-size: 32px;
            border-left: 5px solid #764ba2;
            padding-left: 15px;
        }
        .projects {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        .card {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 10px;
            flex: 1;
            min-width: 200px;
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        .card h3 {
            color: #764ba2;
            margin-bottom: 10px;
        }
        .contact-info p {
            background: #f0f0f0;
            padding: 10px;
            margin: 10px 0;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
            margin-top: 40px;
        }
        @media (max-width: 768px) {
            header h1 { font-size: 32px; }
            section h2 { font-size: 24px; }
            section { margin: 20px; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Екатерина Бурхович</h1>
        <p>Веб-разработчик | Дизайнер | Создаю красивые сайты</p>
    </header>

    <div style="text-align: center; margin-top: -30px;">
        <img src="https://randomuser.me/api/portraits/women/1.jpg" alt="Моё фото" style="width: 150px; height: 150px; border-radius: 50%; border: 4px solid white; object-fit: cover;">
    </div>

    <section>
        <h2>Обо мне</h2>
        <p>Привет! Меня зовут Катя. Я создаю современные сайты, которые работают быстро и красиво выглядят на любых устройствах.</p>
        <p>Люблю учиться новому и решать сложные задачи.</p>
    </section>

    <section>
        <h2>Мои работы</h2>
        <div class="projects">
            <div class="card">
                <h3>Сайт для кофейни</h3>
                <p>Красивый сайт с меню, картой и онлайн-заказом.</p>
            </div>
            <div class="card">
                <h3>Лендинг фитнес-клуба</h3>
                <p>Продающий сайт с формой записи на тренировку.</p>
            </div>
            <div class="card">
                <h3>Блог путешественника</h3>
                <p>Сайт со статьями, фотографиями и картой маршрутов.</p>
            </div>
        </div>
    </section>

    <section>
        <h2>Свяжитесь со мной</h2>
        <div class="contact-info">
            <p>📧 Email: kate@example.com</p>
            <p>📱 Telegram: @kate_dev</p>
            <p>💻 GitHub: github.com/katerina</p>
        </div>
    </section>

    <footer>
        <p>© 2026 Екатерина Бурхович. Сделано с ❤️</p>
    </footer>
</body>
</html>
