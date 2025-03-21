# minecraft-resource-packs-
“Магазин ресурс-паков для Minecraft, доступный для покупки через Visa и FunPay.”
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин ресурс-паков для Minecraft</title>
    <style>
        body {
            background-color: #3a0a45;
            font-family: Arial, sans-serif;
            color: #fff;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            text-align: center;
            padding: 20px;
            border-radius: 10px;
            background-color: #5b0b66;
        }
        h1 {
            font-size: 2.5rem;
        }
        .buy-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        .buy-button {
            background-color: #ff4c4c;
            padding: 15px 30px;
            font-size: 1.2rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            color: white;
            transition: background-color 0.3s;
        }
        .buy-button:hover {
            background-color: #ff3333;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Добро пожаловать в магазин ресурс-паков для Minecraft!</h1>
        <p>Выберите, что хотите купить:</p>
        <div class="buy-buttons">
            <button class="buy-button" onclick="window.location.href='https://www.visa.com'">Оплатить через Visa</button>
            <button class="buy-button" onclick="window.location.href='https://www.funpay.com'">Оплатить через FunPay</button>
        </div>
    </div>
</body>
</html>
