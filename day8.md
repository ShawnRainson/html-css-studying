Задание 1. Теоретическая проверка
Ответьте своими словами:
1 Для чего нужен form? - контейнер формы
2 В чём разница между input и textarea? - первый однострочное поле ввода, второе многострочное
3 Зачем нужен label? - привязанная надпись к элементу
4 Как связать label с input? - for и id
5 В чём разница между checkbox и radio? - первый проверяет поставлена ли галочка, а второе не помню
6 Для чего используются select и option? - выпадающее меню
7 Что делает атрибут required? - делает ввод обязательным
8 Чем отличаются button type="submit" и button type="button"? - первое это кнопка отправки, а вторая обычная кнопка

Задание 2. Найдите и исправьте ошибки
Посмотрите на код:
<form>
    <label for="user">Имя:</label>
    <input type="text" id="user" name="username">

    <label for="email">Почта:</label>
    <input type="email" id="email" name="email">

    <label for="message">Сообщение:</label>
    <input type="textarea" id="message" name="message">

    <button type="submit">Отправить</button>
</form>


Найдите минимум четыре проблемы и исправьте код.
