Задание 1 — div или span?
Для каждой ситуации выбери подходящий вариант и объясни почему.
A. Нужно объединить заголовок и два абзаца в одну группу. - <div>
B. Нужно выделить слово Python внутри предложения, чтобы позднее изменить его цвет через CSS. - <span>
C. Нужно сгруппировать список навыков и его заголовок. - <div>

Задание 2 — блочный или строчный?
Определи поведение по умолчанию для каждого элемента: блочный или строчный.
- <p> - строчный
- <div> - блочный
- <span> - строчный
- <a> - строчный
- <h1> - строчный
- <strong> - строчный

Задание 3 — найди проблему
Что не так с этой структурой?
<p>
    Я изучаю HTML.
    <div>Это мой контейнер.</div>
</p>


Объясни не только, как исправить код, но и почему исходная структура неправильная. - Контейнер внутри абзаца, нужно, чтобы абзац был внутри контейнера

Задание 4 — построй дерево
Для этого кода построй дерево с отступами и объясни, кто кому родитель:
<body>
    <div>
        <h1>Мой профиль</h1>
        <p>Я изучаю <span>HTML</span>.</p>
    </div>

    <div>
        <h2>Навыки</h2>
        <ul>
            <li>Python</li>
            <li>CSS</li>
        </ul>
    </div>
</body>
                |-h1
body --------div-
        |       |-p
        div
        |-h2
        |
        ul
    li-|-li



Задание 5 — профиль
<!DOCTYPE html>
<html>
    <head>
        <title>My profile</title>
    </head>
    <body>
        <div>
            <h1>My profile</h1>
            <p>This is my <span>profile's</span> description</p>
        </div>
        <div>
            <h2>My skills</h2>
            <ul>
                <li>Python</li>
                <li>JavaScript</li>
                <li>HTML/CSS</li>
                <li>C#</li>
            </ul>
        </div>
    </body>
</html>

🔥 Задание 6 — самостоятельная структура

<!DOCTYPE html>
<html>
    <head>
        <title>Favourite technologies</title>
    </head>
    <body>
        <div>
            <h1>Frontend</h1>
            <ul>
                <li>JavaScript</li>
                <li>HTML</li>
                <li>CSS</li>
            </ul>
        </div>
        <div>
            <h2>Backend</h2>
            <ul>
                <li>Python</li>
                <li>C#</li>
            </ul>
        </div>
    </body>
</html>