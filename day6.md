Задание 1. Выберите подходящий элемент
Для каждой ситуации напишите подходящий тег и коротко объясните почему.
1 Основная часть страницы, где находится содержание статьи.

+<main>

<footer>

<aside>



2 Блок ссылок «Главная», «Каталог», «Контакты».

+<nav>

<section>

<article>



3 Самостоятельная новость, которую можно прочитать отдельно от остальной страницы.

+<article>

<div>

<header>



4 Блок «Читайте также» рядом с основной статьёй.

+<aside>

<main>

<footer>



5 Группа элементов, объединённая по теме «Мои навыки».

+<section>

<nav>

<footer>


Задание 2. Объясните своими словами
Ответьте прямо в чате:
1 Чем section отличается от article? - article нужен для самостоятельных частей, а section для объединения по смыслу
2 Почему не стоит заменять абсолютно все семантические теги на div? - потому-что они помогают браузерам и других поисковым системам понимать структуру сайта
3 Может ли header находиться внутри article, а footer — внутри section? Почему? - По идее не могут, так как они описывают структуру всей страницы.

Задание 3. Практика — создаём структуру блога

<!DOCTYPE html>
<html>
    <head>
        <title>My blog</title>
    </head>
    <body>
        <header>
            <h1>My blog</h1>
        </header>
         <nav>
            <a href="#home">Home</a><br>
            <a href="#articles">Articles</a>
        </nav>
        <main>
            <section>
                <h2>Last articles</h2>

                <article>
                    <h3>Last updates</h3>
                    <p>This update was created for...</p>
                </article>
                <article>
                    <h3>New features</h3>
                    <p>New features allow make...</p>
                </article>
            </section>
        </main>
        <footer>© 2026 Мой блог</footer>
    </body>
</html>