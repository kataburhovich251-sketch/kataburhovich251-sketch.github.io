<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Портфолио - Екатерина Б.</title>
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
            padding: 60px 20px 40px 20px;
        }

        /* Стили для фото */
        .avatar {
            text-align: center;
            margin-top: -50px;
            margin-bottom: 20px;
        }

        .avatar img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid white;
            object-fit: cover;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
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

        .works-container {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }

        .work-card {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 10px;
            flex: 1;
            min-width: 200px;
            transition: transform 0.3s;
        }

        .work-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }

        .work-card h3 {
            color: #764ba2;
            margin-bottom: 10px;
        }

        .work-card a {
            display: inline-block;
            margin-top: 10px;
            color: #667eea;
            text-decoration: none;
            font-weight: bold;
        }

        .work-card a:hover {
            text-decoration: underline;
        }

        .contact-item {
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
            .avatar img { width: 100px; height: 100px; }
        }
    </style>
</head>
<body>

    <!-- ФОТО (ДОБАВЛЕНО ОБРАТНО) -->
    <div class="avatar">
        <img src="фото.jpg" alt="Екатерина Б.">
    </div>

    <!-- ШАПКА САЙТА -->
    <header>
        <h1>Екатерина Б.</h1>
        <p>Веб-разработчик | Создаю красивые и удобные сайты</p>
    </header>

    <!-- РАЗДЕЛ "ОБО МНЕ" -->
    <section>
        <h2>Обо мне</h2>
        <p>Привет! Меня зовут Катя. Я создаю современные сайты, которые работают быстро и красиво выглядят на любых устройствах.</p>
        <p>Постоянно учусь новому и люблю решать интересные задачи. Сделаю ваш проект качественно и с душой.</p>
    </section>

    <!-- РАЗДЕЛ "МОИ РАБОТЫ" -->
    <section>
        <h2>Мои работы</h2>
        <div class="works-container">
            <div class="work-card">
                <h3>Сайт для кофейни</h3>
                <p>Красивый сайт с меню, картой и онлайн-заказом.</p>
                <a href="#">Смотреть →</a>
            </div>
            <div class="work-card">
                <h3>Лендинг фитнес-клуба</h3>
                <p>Продающий сайт с формой записи на тренировку.</p>
                <a href="#">Смотреть →</a>
            </div>
            <div class="work-card">
                <h3>Блог путешественника</h3>
                <p>Сайт со статьями, фотографиями и картой маршрутов.</p>
                <a href="#">Смотреть →</a>
            </div>
        </div>
    </section>

    <!-- РАЗДЕЛ "КОНТАКТЫ" -->
    <section>
        <h2>Свяжитесь со мной</h2>
        <div class="contact-item">📧 Email: kataburhovich@example.com</div>
        <div class="contact-item">💬 Telegram: @kataburhovich</div>
        <div class="contact-item">🐙 GitHub: github.com/kataburhovich251</div>
    </section>

    <!-- ПОДВАЛ -->
    <footer>
        <p>© 2026 Екатерина Б. Сделано с ❤️</p>
    </footer>

</body>
</html>
