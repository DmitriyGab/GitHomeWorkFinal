# Инструкция по работе с MarkDown

## Создание заголовков

Для создания заголовков необходимо в начало строки поставить от одного до шести знаков #

Например:

# Заголовок 1

## Заголовок 2

### Заголовок 3

#### Заголовок 4

##### Заголовок 5

###### Заголовок 6


Альтернативный способ создания заголовков: после строки поставить знак = (по размеру заголовка H1) или - (по размеру заголовка H2)

Например:

Заголовок 1
=

Заголовок 1
===============

Заголовок 2
-

Заголовок 2
---------------

## Редактирование и выделение текста

Выделить текст можно, если по краям текста или слов ставить определенные символы.

Например:

_курсив_

*курсив*

__жирный__

**жирный**

___жирный курсив___

***жирный курсив***

_**жирный курсив**_

__*жирный курсив*__

*__жирный курсив__*

**_жирный курсив_**

~~зачеркнутый~~

## Создание списков

### Ненумерованные списки

Для создания ненумерованных списков необходимо использовать в начале строки символы: +, или  -, или *

Например

+ Элемент 1
+ Элемент 2
+ Элемент 3

- Элемент 1
- Элемент 2
- Элемент 3

* Элемент 1
* Элемент 2
* Элемент 3

Вложенные списки создаются путем введения четырех пробелов перед маркером. Например:

* Элемент 1

    - Элемент 1.1
    - Элемент 1.2
    - Элемент 1.3
* Элемент 2


### Нумерованные списки

Для создания нумерованных списков необходимо в начало строки поставить цифру с точкой. Например:

1. Элемент 1
2. Элемент 2
3. Элемент 3

Списки можно начинать с любого значения, но продолжаться список будет исходя из начального значения

56. Элемент 1
1. Элемент 2
105. Элемент 3

Вложенные нумерованные списки создаются подобно вложенным ненумерованными спискам с использованием четырех пробелов.
Пример:

10. Элемент 1
    1. Элемент 1
    5. Элемент 2
    15. Элемент 3
150. Элемент 2


## Добавление цитат

Для того, чтобы вставить цитату - в начале строки необходимо поставить знак >

Пример:

>### Заголовок 3
> Цитата 1
>
> Цитата 2
>
>> Вложенная цитата
>
>>> Цитата третьего уровня
>
> Продолжение основной цитаты

## Вставка ссылок

Чтобы вставить ссылку - ее неходимо заключить в угловые скобки.

Пример: <https://www.yandex.ru>

Чтобы вместо ссылки отображался текст или слово необходимо сначала написать текст в квадратных скобках, а потом ссылку указать в обычных скобках.

Пример:

[Geekbrains](https://gb.ru)

Дополнительно можно добавить всплывающую подсказку.

[Geekbrains](http://gb.ru "Получи образование онлайн")


## Вставка изображений

Для того, чтобы вставить изображение в содержимое файла необходимо поставить восклецательный знак, после него в квадратных скобках указать описательный текст изображения (если вдруг изображение не загрузится), а после в обычных скобках указать ссылку на изображение или название файла, из которого необходимо достать изображение (при его наличии в репозитории).

Пример:

![Мамонт](https://mamont.com)

Чтобы git не спрашивал про какой-то определенный файл необходимо добавить файл .gitignore. В этом файле указать расширение файла, который необходимо игнорировать (забыть).


## Добавление таблиц

Для добавления необходимо обрамить "ячейки" текста символами, обозначающими столбцы и строки.

Столбцы указываются символом |

Строки указываются сочетанием символов |-|

Пример:

|№ п/п|Фамилия|Дата Рождения|
|:----|:-----:|------------:|
|1|Иванов|01.01.2015|
|2|Петров|01.01.2016|
|3|Сидоров|01.01.1900|
|4|Оченьбольшаяфамилия|01.03.2000|
|5| |05.05.2005|
|Равнение по левому краю|Равнение по центру|Равнение по правому краю|

Чтобы пропустить ячейку, необходимо поставить пробел между двумя символами |

Для того, чтобы выровнять слово или текст в ячейке неоходимо строкой выше с определенной стороны поставить символ : в сочетании с символами | и -

Для выравнивания по центру необходимо поставить символы : с двух сторон
