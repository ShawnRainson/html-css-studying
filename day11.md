Задание 1. Теория
Ответь своими словами:
1 Что такое CSS-селектор? - элемент свойства которого будут измененны
2 Как выбрать все элементы h2 на странице? - h2
3 Как в CSS обратиться к классу description? - .class
4 Как в CSS обратиться к id="footer"? - #footer
5 В чём главное отличие class от id? - стиль применяется ко всем объектам класса, стиль применяется к элементу с указанным id
6 Можно ли назначить один класс десяти разным элементам? - по идее да
7 Что означает запятая между селекторами? - групповой селектор
8 Что означает пробел между article и p в селекторе article p? - p внутри article
9 Что выбирает селектор *? - все элементы страницы

Задание 2. Определи селекторы
Посмотри на CSS:
h1 {
    color: red;
} - обычный, все h1

.card {
    color: blue;
} - классовый, объекты класса card

#main {
    color: green;
} - селектор оп идентификатору, элемент с id main

h2, p {
    color: purple;
} - групповой, все h2, p

article p {
    color: orange;
} - вложенный, p внутри article

* {
    font-size: 18px;
} - все элементы на страение


Для каждого правила напиши:
- какой это вид селектора;
- какие элементы он выбирает.

Задание 3. Разбираемся с HTML
Вот HTML-код:
<body>
    <h1 id="title">Мой сайт</h1>

    <p class="text">Первый абзац</p>
    <p>Второй абзац</p>

    <section class="content">
        <h2>Обо мне</h2>
        <p class="text">Третий абзац</p>

        <article>
            <p>Четвёртый абзац</p>
        </article>
    </section>

    <footer id="footer">
        <p>Подвал сайта</p>
    </footer>
</body>


Ответь:
1 Какие абзацы выберет .text? - Первый абзац
2 Какие элементы выберет #footer? - Подвал сайта
3 Какие абзацы выберет section p? - Третий абзац
4 Какие элементы выберет p? - Второй и Четвёртый
5 Какие абзацы выберет article p? - Четвёртый
6 Какие элементы выберет *? - Все

Задание 4. Пишем CSS самостоятельно
h1 {
    color: red;
}

.important {
    color: blue;
}

#special {
    color: green;
}

h2, p {
    font-size: 20px;
}

article p {
    color: orange;
}

* {
    color: black;
}

Задание 5. Найди и исправь ошибки
В HTML:
<h1 class="title">Мой сайт</h1>

<p id="description">Описание сайта</p>

<p class="note">Первая заметка</p>
<p class="note">Вторая заметка</p>


В CSS допущены ошибки:
.title {
    color: red;
}

#description {
    color: blue;
}

.note {
    color: green;
}


Найди все три ошибки и напиши исправленный CSS.

Задание 6. Мини-проект — оформляем профиль
<!DOCTYPE html>
<html>
    <head>
        <title>Profile</title>
        <meta charset="UTF-8">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <h1>ShawnDarkEyes</h1>
        <p class="description">My profile</p>

        <section class="skills">
            <h2>My skills</h2>

            <ul>
                <li>Python</li>
                <li>C#</li>
                <li>JavaScript</li>
            </ul>

            <article>
                <p>First</p>
                <p>Second</p>
            </article>
        </section>
        <footer id="footer">
            <p>Footer</p>
        </footer>
    </body>
</html>

h1 {
    color: red;
}

.description {
    color: blue;
}

#footer {
    color: yellow;
}

article p {
    color: gray;
}

h2, ul {
    color: orange;
}

* {
    background-color: white;
}