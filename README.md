<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мій профіль</title>
</head>
<body>
    <style>
        body {
            font-family: "Poppins", sans-serif;
            background: linear-gradient(135deg, #b2fefa, #0ed2f7);
            color: #222;
            margin: 0;
            padding: 0;
            transition: all 0.3s ease;
        }

        h1 {
            text-align: center;
            background-color: #009688;
            color: white;
            padding: 25px 0;
            margin: 0;
            font-size: 2.2em;
            letter-spacing: 1px;
            text-transform: uppercase;
            box-shadow: 0 3px 15px rgba(0, 0, 0, 0.3);
        }

        img {
            display: block;
            margin: 30px auto;
            width: 220px;
            height: 220px;
            object-fit: cover;
            border-radius: 50%;
            box-shadow: 0 0 20px rgba(0,0,0,0.4);
            transition: transform 0.4s ease, box-shadow 0.3s ease;
        }

        img:hover {
            transform: scale(1.1);
            box-shadow: 0 0 30px rgba(0,0,0,0.6);
        }

        p {
            max-width: 800px;
            margin: 15px auto;
            text-align: center;
            line-height: 1.8;
            font-size: 18px;
            color: #222;
        }

        h2 {
            text-align: center;
            color: #004d40;
            margin-top: 40px;
            font-size: 1.8em;
            position: relative;
        }

        h2::after {
            content: "";
            display: block;
            width: 60px;
            height: 3px;
            background-color: #009688;
            margin: 10px auto 0;
            border-radius: 2px;
        }

        ul {
            list-style-type: none;
            max-width: 350px;
            margin: 20px auto;
            padding: 0;
        }

        ul li {
            background-color: white;
            margin: 10px 0;
            padding: 12px;
            border-radius: 12px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        ul li:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 15px rgba(0,0,0,0.2);
        }

        table {
            margin: 25px auto;
            border-collapse: collapse;
            width: 70%;
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            transition: transform 0.3s ease;
        }

        table:hover {
            transform: scale(1.03);
        }

        th, td {
            padding: 12px 18px;
            text-align: center;
        }

        th {
            background-color: #009688;
            color: white;
        }

        tr:nth-child(even) {
            background-color: #f2f2f2;
        }

        tr:hover {
            background-color: #e0f2f1;
            transform: scale(1.01);
        }

        a {
            display: block;
            text-align: center;
            margin: 25px 0;
            color: #00695c;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
            transition: transform 0.3s ease, color 0.3s ease;
        }

        a:hover {
            color: #004d40;
            transform: scale(1.1);
        }

        form {
            max-width: 420px;
            margin: 40px auto;
            padding: 25px;
            background-color: white;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        form:hover {
            transform: scale(1.02);
            box-shadow: 0 6px 20px rgba(0,0,0,0.25);
        }

        label {
            font-weight: bold;
            display: block;
            margin-top: 10px;
            color: #004d40;
        }

        input {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #009688;
            border-radius: 8px;
            transition: box-shadow 0.3s ease, transform 0.3s ease;
        }

        input:focus {
            outline: none;
            box-shadow: 0 0 10px #009688;
            transform: scale(1.02);
        }

        button {
            margin-top: 20px;
            width: 100%;
            padding: 12px;
            background-color: #009688;
            color: white;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bolder;
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        button:hover {
            background-color: #00695c;
            transform: scale(1.05);
        }

        video{
            display: block;
            justify-content: center;
            align-items: center;
            height: 50vh;
            max-width: 90%;
            border-radius: 10px;
            margin: 20px auto;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #004d40;
            color: white;
            font-size: 14px;
            margin-top: 50px;
        }

        blockquote {
            text-align: center;
            font-style: italic;
            font-size: 18px;
            color: #004d40;
            margin: 30px auto;
            max-width: 600px;
        }
    </style>
    <h1>Гнатишин Денис</h1>
<nav>
   <ul>
        <li><a href="#Hobby">Мої хобі</a></li>
        <li><a  href="#Anime">Улюблені аніме</a></li>
        <li><a href="Social network">Мої соцмережі</a></li>
    </ul>
</nav>
    <img src="dr stone.webp" alt="Dr Stone">

    <p>Привіт! Я студент <strong>Фахового коледжу економіки та інформаційних технологій</strong> у місті Самбір. 
    Навчаюсь за спеціальністю <strong>Інженерія програмного забезпечення</strong>, адже мене завжди цікавив світ технологій, інтернету та створення програм, які можуть полегшувати життя людям.</p>

    <p>У вільний час я вдосконалюю свої навички у веброзробці — вивчаю HTML, CSS, JavaScript, а також пробую себе у створенні простих проєктів і сайтів. 
    Люблю дізнаватися нове, працювати над дизайном і розвивати логічне мислення через програмування.</p>

    <blockquote>“Кожна помилка — це ще один крок до успіху.” 💡</blockquote>
    
    <h2 id="Hobby">Мої хобі</h2>
    <ul>
        <li>🎮 Відео ігри</li>
        <li>🎣 Рибалка</li>
        <li>💻 Програмування</li>
        <li>📱 Створення сайтів</li>
        <li>🎧 Музика та подкасти</li>
    </ul>
    
    <h2 id="Anime">Улюблені аніме</h2>
    <table>
        <tr><th>Назва</th><th>Жанр</th></tr>
        <tr><td>Dr Stone</td><td>Наукове, пригодницьке</td></tr>
        <tr><td>Black Clover</td><td>Фентезі, бойове</td></tr>
        <tr><td>Attack on Titan</td><td>Драма, екшн</td></tr>
        <tr><td>One Piece</td><td>Пригоди, комедія</td></tr>
    </table>

    <h2>Мої улюблені технології</h2>
    <p>💻 Мені подобається працювати з такими мовами програмування, як <strong>C++, Python, JavaScript</strong>.  
    У веброзробці я використовую <strong>HTML5, CSS3</strong> і поступово освоюю <strong>React</strong> для створення сучасних сайтів.  
    Також цікавлюся дизайном інтерфейсів і штучним інтелектом.</p>

    <h2 id="Social network">Мої соцмережі</h2>
    <a href="https://uk.wikipedia.org/wiki/Dr._Stone" target="_blank">🔗 Wikipedia</a>
    <a href="https://www.instagram.com/denusgnatishin?igsh=N2dnMWNnZWk1czg5&utm_source=qr">📸Instagram</a>
    <video src="Dr. STONE SCIENCE FUTURE Part 2 _ Official Trailer _ Crunchyroll.mp4" controls autoplay muted loop>
        Трейлер не підтримується вашим браузером.
    </video>

    <h2>Зворотний зв'язок</h2>
    <p>Якщо хочеш зв’язатися зі мною або маєш пропозицію — заповни форму нижче 👇</p>

    <form>
        <label>Ім'я</label>
        <input type="text" placeholder="Введіть ім'я">

        <label>Email</label>
        <input type="email" placeholder="example@gmail.com">

        <label>Повідомлення</label>
        <input type="text" placeholder="Ваше повідомлення...">

        <button>Надіслати</button>
    </form>

    <footer>
        © 2025 Гнатишин Денис | Розроблено з ❤️ для навчання
    </footer>
</body>
</html>

