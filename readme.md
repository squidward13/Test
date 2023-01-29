# Инструкция для работы с Markdown

## Начало работы

1. git init - **инициализация репозитория**
2. git add имя_файла.расширение - **добавить файл в репозиторий**
3. git commit -m(флаг комментария) 'Комментарий' - **сохранение файла с комментарием**
4. git diff - **просмотр изменений**
5. git log - **список всех _commit_ в данной ветке**
6. git checkout имя_ветки - **переход на другую ветку**

## Заголовок
Для того чтобы написать заголовок в Markdown, необходимо использовать знак # (хэш). Если необходимо несколько уровней заголовков, h1 — h6, нужно изменить количество хэшей (#) перед текстом заголовка. Например,
#### Вот так

Альтернативные теги для H1 и H2 (знаки равно или минусы под заголовком + пустая строчка над загаловком). Например,

Вот так
===

## Выделение текста

Чтобы выделить текст курсивом, необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания. Например, *вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания. Например, **вот так** или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.

## Списки
Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком (+). Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать.
Например, вот так:
1. Первый пункт
2. Второй пункт

## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следующее:
![Привет, это кот!](cat.jpg)

## Ссылки

## Работа с таблицами

Здесь должна быть информация о таблицах.

## Цитаты

## Заключение