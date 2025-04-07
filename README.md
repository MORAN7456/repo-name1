<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мое Портфолио</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        section {
            margin: 20px 0;
            padding: 20px;
            background: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        .project {
            background: #efefef;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: #fff;
        }
    </style>
</head>
<body>

<header>
    <h1>Мое Портфолио</h1>
    <p>Добро пожаловать! Я -  Попова Карина , и вот мои работы.</p>
</header>

<div class="container">
    <section>
        <h2>Обо мне</h2>
        <p>Я - учусь на программиста, занимаюсь отдельо от этой професии музыкальными хобби.</p>
    </section>

    <section>
        <h2>Мои проекты</h2>
        <div class="projects">
            <div class="project">
                <h3>Проект 1</h3>
                <p>Описание проекта 1.</p>
                <a href="https://example.com" target="_blank">Смотреть проект</a>
            </div>
            <div class="project">
                <h3>Проект 2</h3>
                <p>Описание проекта 2.</p>
                <a href="https://example.com" target="_blank">Смотреть проект</a>
            </div>
            <div class="project">
                <h3>Проект 3</h3>
                <p>Описание проекта 3.</p>
                <a href="https://example.com" target="_blank">Смотреть проект</a>
            </div>
            <!-- Добавьте больше проектов по мере необходимости -->
        </div>
    </section>
</div>

<footer>
    <p>Контакты: karina_daz5@mail.ru</p>
</footer>

</body>
</html>
