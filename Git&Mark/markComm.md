# Список основных команд Markdown

## **Заголовки**
---

# H1
## H2
### H3
#### H4
##### H5
###### H6

Кроме того, H1 и H2 можно обозначить подчеркиванием:

Alt-H1
======

Alt-H2

------



## **Выделение**
---

Курсив обозначается *звездочками* или _подчеркиванием_.

Полужирный шрифт - двойными **звездочками** или __подчеркиванием__.

Комбинированное выделение **звездочками и _подчеркиванием_**.

Для зачеркнутого текста используются две тильды . ~~Уберите это.~~

## **Списки**
---

1. Первый пункт нумерованного списка
2. Второй пункт
    - Ненумерованный вложенный список.
    * 2й
1. Сами числа не имеют значения, лишь бы это были цифры
    1. Нумерованный вложенный список
4. И еще один пункт.

(проще табуляцией)

⋅⋅⋅Внутри пунктов списка можно вставить абзацы с таким же отступом. Обратите внимание на пустую строку выше и на пробелы в начале (нужен по меньшей мере один, но здесь мы добавили три, чтобы также выровнять необработанный Markdown). 

⋅⋅⋅Чтобы вставить разрыв строки, но не начинать новый параграф, нужно добавить два пробела перед новой строкой.⋅⋅
⋅⋅⋅Этот текст начинается с новой строки, но находится в том же абзаце.⋅⋅
⋅⋅⋅(В некоторых обработчиках, например на Github, пробелы в начале новой строки не нужны.)

* Ненумерованный список можно размечать звездочками
- Или минусами
+ Или плюсами

## **Ссылки**
---

[Обычная ссылка в строке](https://www.google.com)

[Обычная ссылка с title](https://www.google.com "Сайт Google")

[Ссылка со сноской][Произвольный регистронезависимый текст]

[Относительная ссылка на Нормальный такой плэйлист -)))](https://open.spotify.com/album/4ydl8Ci7OsndhI2ALnrpIv?si=vzkwVBo0TGWFEcO-oXkLew)

[Для ссылок со сноской можно использовать цифры][1]

Или можно просто вставить ссылку в квадратные скобки [текст ссылки]

Произвольный текст, после которого можно привести ссылки.

[произвольный регистронезависимый текст]: https://www.mozilla.org
[1]: http://slashdot.org
[текст ссылки]: http://www.reddit.com

## **Изображения**
---

Вот наш логотип (наведите указатель, чтобы увидеть текст заголовка):

Внутри строки:  
![alt-текст](https://i.pinimg.com/originals/ba/8d/c9/ba8dc9593b181c8fe7fcbf68a0d62c52.jpg "Я пытался, но плейлист..... ссылка выше))")

В сноске:  
![alt-текст][logo]

[logo]: https://i.pinimg.com/originals/06/ff/a2/06ffa2eb0f2a2d1b29f0c09c6abd779a.jpg
"blueprint"


## **Подсветка кода и синтаксиса**
---

`Код` в строке обрамляется `обратными апострофами`

Блоки кода выделяются либо тремя обратными апострофами ``` либо четырьмя пробелами в каждой строке. Рекомендуется использовать три апострофа -- они проще и только они поддерживают подсветку синтаксиса.

```javascript
var s = "Подсветка JavaScript";
alert(s);
```
 
```python
s = "Подсветка Python"
print s
```
 
```
Язык не указан, синтаксис не подсвечен.
```


## **Таблицы**
---
>Таблицы не являются частью Markdown, но многие обработчики, например Markdown Here и Github, поддерживают их. Они позволяют легко добавить таблицы в электронное письмо -- в других случаях для этого нужно копировать их из другого приложения.

Вертикальные линии обозначают столбцы.

| Таблицы       | Это                | Круто |
| ------------- |:------------------:| -----:|
| столбец 3     | выровнен вправо    | $1600 |
| столбец 2     | выровнен по центру |   $12 |
| зебра-строки  | прикольные         |    $1 |

Внешние вертикальные линии (|) не обязательны, и они нужны только чтобы сам код Markdown выглядел красиво. Тот же код можно записать так:

Markdown | не такой | красивый
--- | --- | ---
*Но выводится* | `так же` | **клево**
1 | 2 | 3

## **Цитаты**
---
> С помощью цитат очень удобно в письме обозначать исходный текст.
> Эта строка - часть той же цитаты.

Разрыв цитаты.

> Это очень длинная строка, но она будет правильно процитирована даже при размещении на нескольких строках. Продолжаем писать, чтобы эта строка не вмещалась на одной строке в любом окне. Кстати, в цитаты можно *вставлять* даже **Markdown**.

## **Горизонтальные линии**

---

Дефисы

***

Звездочки
___

Подчеркивания

done