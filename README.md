<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин валюты FunTime Minecraft</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #1e293b, #64748b);
            color: #fff;
        }
        header {
            background-color: #0f172a;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
            color: #38bdf8;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        .currency-card {
            background-color: #1e293b;
            border-radius: 10px;
            padding: 20px;
            margin: 15px 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s;
        }
        .currency-card:hover {
            transform: translateY(-5px);
        }
        .currency-card h2 {
            margin: 0 0 10px;
            color: #38bdf8;
        }
        .currency-card p {
            margin: 5px 0;
            line-height: 1.5;
        }
        .currency-card .price {
            font-size: 1.5rem;
            color: #22c55e;
            font-weight: bold;
        }
        footer {
            text-align: center;
            padding: 15px;
            background-color: #0f172a;
            margin-top: 20px;
            color: #cbd5e1;
            font-size: 0.9rem;
        }
        button {
            background-color: #22c55e;
            border: none;
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #16a34a;
        }
        .shop-header {
            margin: 20px 0;
            text-align: center;
            font-size: 1.8rem;
            color: #cbd5e1;
        }
    </style>
</head>
<body>
    <header>
        <h1>Магазин валюты FunTime</h1>
    </header>

    <div class="container">
        <p class="shop-header">Покупайте игровую валюту для вашего Minecraft сервера FunTime!</p>

        <div class="currency-card">
            <h2>Пакет "Начальный"</h2>
            <p>Включает 1 миллион монет — идеально для старта.</p>
            <p class="price">2 гривны</p>
            <p>Начните с малого и исследуйте возможности сервера!</p>
            <button>Купить</button>
        </div>

        <div class="currency-card">
            <h2>Пакет "Игрок"</h2>
            <p>Включает 10 миллионов монет для увлекательной игры.</p>
            <p class="price">20 гривен</p>
            <p>Подходит для игроков, которые хотят улучшить свои игровые возможности.</p>
            <button>Купить</button>
        </div>

        <div class="currency-card">
            <h2>Пакет "Мастер"</h2>
            <p>Получите 50 миллионов монет и станьте легендой сервера!</p>
            <p class="price">100 гривен</p>
            <p>Для тех, кто стремится доминировать на сервере.</p>
            <button>Купить</button>
        </div>

        <div class="currency-card">
            <h2>Пакет "Безлимит"</h2>
            <p>100 миллионов монет для максимального удовольствия!</p>
            <p class="price">200 гривен</p>
            <p>Идеальный выбор для самых преданных игроков.</p>
            <button>Купить</button>
        </div>

        <div class="currency-card">
            <h2>Кит-набор "Убийца"</h2>
            <p>С этим китом вы будете непобедимы на сервере! Полный арсенал, который позволит вам уничтожать соперников и доминировать в любых сражениях.</p>
            <p class="price">250 гривен</p>
          <p>Идеальный выбор для игроков, стремящихся стать лучшими.</p>
            <button>Купить</button>
        </div>

        <p class="shop-header">Для покупки валюты свяжитесь с нами в Telegram: <a href="https://t.me/klarry9999" style="color: #38bdf8;">@klarry9999</a></p>
    </div>

    <footer>
        &copy; 2024 Магазин валюты FunTime Minecraft. Все права защищены.
    </footer>
</body>
</html>
