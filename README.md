<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Erik Pizza & Grill & Kebab</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        .menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px;
        }
        .menu-item {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin: 10px;
            padding: 20px;
            width: 250px;
            text-align: center;
        }
        .menu-item h2 {
            margin: 10px 0;
        }
        .menu-item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
        }
        .contact-info {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .contact-info a {
            color: #4CAF50;
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        .footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
        }
        .menu-item p {
            font-size: 16px;
            margin: 5px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Erik Pizza & Grill & Kebab</h1>
    <p>أفضل الأطعمة الإيطالية والمشاوي!</p>
</header>

<div class="menu">
    <!-- Example menu items -->
    <div class="menu-item">
        <img src="pizza1.jpg" alt="Pizza Florida">
        <h2>Pizza Florida</h2>
        <p>السعر: €7.50 (صغير) | €18.00 (كبير)</p>
        <p>مكونات: Pomodoro, mozzarella, salsiccia, grana</p>
    </div>
    <div class="menu-item">
        <img src="pizza2.jpg" alt="Pizza Prosciutto">
        <h2>Pizza Prosciutto</h2>
        <p>السعر: €6.00 (صغير) | €17.00 (كبير)</p>
        <p>مكونات: Pomodoro, mozzarella, cotto</p>
    </div>
    <div class="menu-item">
        <img src="pizza3.jpg" alt="Pizza Focaccia">
        <h2>Focaccia</h2>
        <p>السعر: €6.00</p>
        <p>مكونات: Olio, sale, origano</p>
    </div>
    <!-- Add more items as needed -->
</div>

<div class="contact-info">
    <p>Per ordini o richieste, contattateci :</p>
    <p> Numero di telefono: <a href="tel:+3663279212">3663279212</a></p>
    <p> Numero di telefono: <a href="tel:+336741272">3663279212</a></p>
    <p> Numero di telefono: <a href="tel:+336741275">3663279212</a></p>
    <p>Numero Whatsapp: <a href="https://wa.me/3336741272">3336741272</a></p>
    <p>العنوان: <strong>SALTRIO (VA) - VIA CLIVIO, 39</strong></p>
</div>

<div class="footer">
    <p>© 2024 Erik Pizza & Grill & Kebab. جميع الحقوق محفوظة.</p>
</div>

</body>
</html>

