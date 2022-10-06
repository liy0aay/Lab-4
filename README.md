# Lab-3

## Лабораторная работа №3

>...Том, наконец, прекратил созерцать улицы и уныло вздохнул. С того момента, как он занял колокольню, снаружи лучше не становилось, зомби запрудили все окресности. Большинство стояли без дела, покачиваясь на ветру, но Том знал, что это обманчивое поведение, и лучше к ним не приближаться и лишний раз не шуметь. На колокольне было безопасно, но оставаться вечно тут было нельзя: Том уже давно планировал дойти до радиовышки, которую в хорошую погоду было видно в бинокль, и попробовать связаться с другими выжившими. Марш-бросок предстоял довольно сложный, и Том знал, что ему необходимо максимально облегчить свою ношу, чтобы добраться до вышки до захода солнца. Он скептически оглядел свои вещи, все они были ему нужны, но место было сильно ограничено...

| Предмет | Обозначение | Размер | Очки выживания |
| ------- | ----------- | ------ | -------------- |
| Винтовка | в | 3 ячейки | 25 |
| Пистолет | п | 2 ячейки | 15 |
| Боекомплект | б | 2 ячейки | 15 |
| Аптечка | а | 2 ячейки | 20 |
| Ингалятор | и | 1 ячейка | 5* |
| Нож | н | 1 ячейка | 15 |
| Топор | т | 3 ячейки | 20 |
| Оберег | о | 1 ячейка | 25 |
| Фляжка | ф | 1 ячейка | 15 |
| Антидот | д | 1 ячейка | 10* |
| Еда | к | 2 ячейки | 20 |
| Арбалет | р | 2 ячейки | 20 |

**Задание**

* Том имеет ограниченное количество места в своём рюкзаке и может взять далеко не всё. 
* Каждый предмет имеет определённую ценность, выраженную в очках выживания.
* Каждый предмет, взятый с собой, повышает общие очки выживания, но его отсутствие очки выживания вычитает. 
* Том может страдать от астмы или быть заражённым, ввиду чего **ингалятор** или **антидот** соответственно должны присутствовать обязательно. 
* Наш герой уже имеет некоторое количество очков выживания, и необходимо выполнить проверку на то, чтобы итоговый счёт был положительным.

Напишите программу, которая решит проблему Тома и избавит его от долгих раздумий. Результат представить в виде двумерного массива, заполненного обозначениями предметов, к примеру:

```
[в],[в],[в]  
[р],[р],[о]  
[а],[а],[н]  

Итоговые очки выживания: 5
```

**Варианты**

| Вариант | Ячейки | Болезнь | Очков выживания |
| ------- | ------ | ------- | --------------- |
| 1 | 2x4 | нет | 15 |
| 2 | 3x3 | астма | 10 |
| 3 | 2x4 | заражение | 10 |
| 4 | 3x3 | нет | 15 |
| 5 | 2x4 | астма | 20 |
| 6 | 3x3 | заражение | 15 |
| 7 | 2x4 | нет | 15 |
| 8 | 3x3 | астма | 15 |
| 9 | 2x4 | заражение | 20 |
| 10 | 3x3 | нет | 10 |

**Допзадание** 

Найти решение или доказать его отсутствие для случая с инвентарём в 7 ячеек.
Найти все комбинации вещей для вашего варианта, удовлетворяющие последнему условию задачи (общий счёт положительный).

**Дополнительно**

Описание задачи о рюкзаке: https://proglib.io/p/python-i-dinamicheskoe-programmirovanie-na-primere-zadachi-o-ryukzake-2020-02-04
