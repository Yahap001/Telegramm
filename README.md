# Telegramm
Initialize with README
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Переход в Telegram</title>
  <style>
    body {
      background-color: #f4f4f4;
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    h1 {
      margin-bottom: 20px;
    }
    button {
      padding: 12px 24px;
      font-size: 18px;
      background-color: #0088cc;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    button:hover {
      background-color: #0070a8;
    }
  </style>
</head>
<body>
  <h1>Переход в Telegram-канал</h1>
  <button onclick="goToTelegram()">Канал</button>

  <script>
    function goToTelegram() {
      window.location.href = "https://t.me/androeed_games";
    }
  </script>
</body>
</html>

