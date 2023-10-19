# Инструкция по работе с Git и удаленными репозиториями

## Что такое Git?
Git - это одна из реализаций распределенных систем контроля версий, имеющая как и локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Создание команд

### ***git init*** - Инициализация репозитория.

### ***git add "file_name"*** - Добавит файлу с названием __file_name__ вермионность.

### ***git reset "file_name"*** - Удалить у файла с названием __file_name__ версионность

### ***git add*** - Добавить всем файлам в папке версионность 

### ***git reset*** - Убрать у всех файлов в папке версионность 

### ***git commit -m "commit_massege"*** - Упрощенный вариант ввода комита

### ***git commit*** - Обычный вариант коммита (долгий)

### ***git commit -am*** - Если файл имеет состояние __modified__ (т.е был tracked ранее и мы его добавили с помощью git add ), то можно пропустить этап с коиандой __git add__ посредством использования данной команды 

### ***git checkout "hash_numder"*** - Переместить на коммит c хэшем "hash_number" (для того, чтобы вернуться git checkout master/main)

### ***git diff*** - Последние изменения (начиная от коммита)

### ***git merge*** - совместить две ветки 

### ***git branch -d*** - удалить ненуную ветку (черновик)

### ***git remote add origin (ссылка)*** - Команда git remote служит для управления списком удалённых репозиториев. Она позволяет сохранять длинные URL репозиториев в виде понятных коротких строк, например «origin», так что вам не придётся забивать голову всякой ерундой и набирать её каждый раз для связи с сервером.

### ***git archive*** - оманда git archive используется для упаковки в архив указанных коммитов или всего репозитория.

### ***git fast-import*** - Для других систем контроля версий, либо для импорта произвольно форматированных данных, вы можете использовать git fast-import, которая умеет преобразовывать данные в формат, понятный Git.

### ***git mv*** - Команда git mv — это всего лишь удобный способ переместить файл, а затем выполнить git add для нового файла и git rm для старого.

### ***git clean*** - Команда git clean используется для удаления мусора из рабочего каталога. Это могут быть результаты сборки проекта или файлы конфликтов слияний.


# Инструкция для работы с Markdown

## Заголовки

#. Заголовок первого уровня

##. Заголовок второго уровня

###. Заголовок третьего уровня

####. Заголовок четвёртого уровня

#####. Заголовок пятого уровня

######. Заголовок шестого уровня

_Например_

# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
#### Заголовок четвёртого уровня
##### Заголовок пятого уровня
###### Заголовок шестого уровня

# Параграфы и переносы строк

Это параграф. 

Чтобы создать новый параграф, оставьте пустую строку между двумя строками текста.

Это первая строка  
И это вторая строка, но они находятся в одном параграфе. Для переноса строки используйте два пробела в конце предыдущей строки.

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочками(*) или знаком нижнего подчеркивания ( _ ). _Например_, *вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания ( __ ). _Например_, **вот так** или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.

### Пример ###

*курсив*  
_курсив_

**жирный**  
__жирный__

***жирный курсив***  
___жирный курсив___

~~зачеркнутый~~

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком + .
*Например*, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4
* Элемент 5 

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать.
1. Первый пункт
2. Второй пункт
3. Третий пункт
4. Четвертый пункт

Чтобы добавить маркированные списки, необходимо пункты выделить(-). *Напрример*

- Первый пункт 
- Второй пункт 
- Третий пункт

Чтобы добавить вложенные списки, неоюходимо добавить 4 пробела перед пунктом
*Например*: 

1. Первый пункт
    - подпункт первый
2. Второй пункт 
    - подпункт первый

## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следущее: ![Привет это тефтелька!]
 
## Ссылки

[текст ссылки GeekBrain]

## Работа с таблицами

Уберите пробелы!

| Заголовок 1 | Заголовок 2 |

| ----------- | ----------- |

| Ячейка 1    | Ячейка 2   |

| Ячейка 3    | Ячейка 4   |

*Например*:

| Заголовок 1 | Заголовок 2 |
| ----------- | ----------- |
| Ячейка 1    | Ячейка 2   |
| Ячейка 3    | Ячейка 4   |

## Цитаты

Удалите /

/> Первый уровень цитирования

/>> Второй уровень цитирования

/>>> Третий уровень цитирования

*Например*: 

> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования

Таблица как HTML

Убрать в первой и воследней строчке (.), и убрать пробелы между строк

<table. > 

    <tr>

        <th>Заголовок 1</th>

        <th>Заголовок 2</th>

    </tr>

    <tr>
        <td>Ячейка 1.1</td>

        <td>Ячейка 2.1</td>

    </tr>

    <tr>

        <td>Ячейка 1.2</td>

        <td>Ячейка 2.2</td>

    </tr>

<table.  > 

*Например*:

<table>
    <tr>
        <th>Заголовок 1</th>
        <th>Заголовок 2</th>
    </tr>
    <tr>
        <td>Ячейка 1.1</td>
        <td>Ячейка 2.1</td>
    </tr>
    <tr>
        <td>Ячейка 1.2</td>
        <td>Ячейка 2.2</td>
    </tr>
</table>



## Заключение