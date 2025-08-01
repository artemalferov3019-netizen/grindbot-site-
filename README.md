<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GrindBot+</title>
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      margin: 0;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #fff;
      text-align: center;
      overflow-x: hidden;
    }
    h1 {
      font-size: 2.5rem;
      margin-top: 50px;
      text-shadow: 0 0 10px #00fff2;
      animation: fadeInDown 1s ease-out;
    }
    .section, .stats, .reviews, .video-section {
      margin: 50px auto;
      max-width: 800px;
      padding: 0 20px;
      animation: fadeInUp 1.2s ease-out;
    }
    .btn {
      margin: 20px 10px;
      background: #00fff2;
      color: #000;
      padding: 14px 24px;
      border: none;
      border-radius: 10px;
      font-size: 1.2rem;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
      transition: 0.3s ease;
      animation: fadeIn 2s ease-out;
    }
    .btn:hover {
      background: #00ccbf;
    }
    .stats {
      font-size: 1.1rem;
      color: #ddd;
    }
    .reviews {
      font-style: italic;
      color: #ccc;
    }
    .review {
      margin-bottom: 20px;
    }
    video {
      width: 100%;
      max-width: 720px;
      border-radius: 10px;
      box-shadow: 0 0 20px #000;
    }
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>
  <h1>GrindBot+ успешно запущен 🚀</h1>

  <div class="section">
    <p><strong>GrindBot+</strong> — это полностью автоматический бот для фарма в Path of Exile, способный приносить <strong>до 200 Divine Orbs в день</strong> с помощью билдов Venom Gyre на картах Dunes/Strand.</p>
    <p>Поддерживает мультибокс, авто-лут, авто-компасы, авто-фляги, мониторинг дохода и многое другое.</p>
  </div>

  <div>
    <a href="https://t.me/grindbot_plus_bot" class="btn" target="_blank">Купить сейчас</a>
    <a href="#video" class="btn">Смотреть видео</a>
  </div>

  <div class="stats">
    <p>🛒 <strong>Продано копий:</strong> 73</p>
    <p>💬 <strong>Отзывов получено:</strong> 25</p>
    <p>📈 <strong>Средний доход пользователей:</strong> 11.7 Divine/час</p>
  </div>

  <div class="reviews">
    <div class="review">“Запустил и забыл. День прошёл — 180 диванов на счёт. Красота.” — <strong>@poeTrader</strong></div>
    <div class="review">“GrindBot+ — это лучший бот, что я видел. Без бана, без багов.” — <strong>@shadowfarmer</strong></div>
    <div class="review">“Уже купил второй аккаунт — просто фармит и фармит.” — <strong>@goldmine2025</strong></div>
  </div>

  <div class="video-section" id="video">
    <h2>🎥 Как работает GrindBot+</h2>
    <video controls autoplay muted loop>
      <source src="farm-bot-quest-bot-map-bot-path-of-exile-bot-greedy-poe-bot-326-secrets-of_du5dnWYE.mp4" type="video/mp4" />
      Ваш браузер не поддерживает видео.
    </video>
  </div>
</body>
</html>
