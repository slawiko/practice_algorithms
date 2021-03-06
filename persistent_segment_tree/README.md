# Персистентное дерево отрезков

> Имя входного файла: стандартный ввод

> Имя выходного файла: стандартный вывод

> Ограничение по времени: 2 с

> Ограничение по памяти: 256 МБ

Дан массив A из N элементов. Необходимо обработать Q запросов. i-й запрос состоит из четырех чисел li, ri, xi, yi. Ответом на i-й запрос является одно целое неотрицательное число — количество чисел на отрезке [li, ri], которые не меньше xi и не превышают yi.

### Формат входного файла

Первая строка входного файла содержит два натуральных числа N и Q (1 ≤ N, Q ≤ 2 ⋅ 105) — размер массива и количество запросов соответственно.

Вторая строка содержит n чисел ai (1 ≤ ai ≤ 109) — элементы массива A.

Далее следует Q строк, каждая содержит по 4 числа. В i-й строке расположены четыре числа li, ri, xi, yi (1 ≤ li ≤ ri ≤ N, 1 ≤ xi ≤ yi ≤ 109).

### Формат выходного файла

Выведите Q строк — ответы на запросы.

### Примеры

|входные данные|выходные данные|
|---|---|
|5 3|5|
|1 2 3 4 5|4|
|1 5 1 5|2|
|1 5 2 100|
|2 5 1 3|
|---|---|
|10 12|3|
|3 2 15 2 15 6 14 14 3 6|2|
|1 6 2 5|2|
|8 10 2 6|1|
|7 10 2 6|0|
|5 9 4 8|0|
|7 7 5 6|3|
|5 8 2 3|1|
|2 4 2 15|1|
|3 4 2 5|4|
|6 9 2 5|0|
|4 10 2 7|1|
|6 9 5 5|
|6 6 3 7|
