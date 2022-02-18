# hse_hw1_meth

<h3>Ссылка на google colab 1</h3> 
https://colab.research.google.com/drive/1xvIXYF_4ba06MD1WWTgsKWZi_xfhk3-M?usp=sharing

<h3>Задание 1</h3> 

По результатам FastQC можно заметить такую особенность как GC состав. На 1-й картинке мы можем наблюдать два пика (красный график), что значительно отличается от нормального распределения и теоретического распределения, которое представлено синим графиком.
Это можно объяснить следующим: Бисульфит действует на одноцепочечную ДНК, превращая цитозин в урацил. Урацил в свою очередь представлен тимином (на втором графике видно, что его достаточно много). Если же этот цитозин метилирован, то есть к его пятому атому углерода присоединена метильная группа, то такой цитозин не подвергается превращению. Таким образом, бисульфит изменяет последовательность ДНК в зависимости от её паттерна метилирования, и после его воздействия можно установить, какие CpG-динуклеотиды были метилированы, сравнив измененную последовательность с исходной (бисульфитное секвенирование).

https://ru.wikipedia.org/wiki/%D0%91%D0%B8%D1%81%D1%83%D0%BB%D1%8C%D1%84%D0%B8%D1%82%D0%BD%D0%BE%D0%B5_%D1%81%D0%B5%D0%BA%D0%B2%D0%B5%D0%BD%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5 

|Per sequence GC content|Per base sequence content|
|---|---|
|![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/54f3ec8feaa96a175e76467a76bb20b4fc1be305/img/1.2.PNG)|![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/54f3ec8feaa96a175e76467a76bb20b4fc1be305/img/1.1.PNG)|

<h3>Задание 2</h3> 

| Стадия   | 11347700-11367700| 40185800-40195800 |Total number duplicated alignments removed|Total count of deduplicated leftover sequences|
|---|---|---|---|---|
|8_cell   | 1090 | 464 |18.31%|81.69%|
| ICM     | 1456 | 630 |9.08% |90.92%|
| Epiblast|2328  |1062 |2.92% |97.08%|

**M-bias plots**

Высокое значение в клетках epiblast. 

| 8_cell|ICM  | Epiblast |
|---|---|---|
| ![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/4ecf42fc7f14304c197661cf36984dbcaa2511aa/img/8%D1%81_1.PNG) | ![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/4ecf42fc7f14304c197661cf36984dbcaa2511aa/img/i_1.PNG) | ![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/4ecf42fc7f14304c197661cf36984dbcaa2511aa/img/ep_1.PNG) |
| ![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/4ecf42fc7f14304c197661cf36984dbcaa2511aa/img/8%D1%81_2.PNG) | ![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/4ecf42fc7f14304c197661cf36984dbcaa2511aa/img/i_2.PNG) | ![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/4ecf42fc7f14304c197661cf36984dbcaa2511aa/img/ep_2.PNG) |

**Гистограммы**

|   |
|---|
|![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/31c014a73c166de5aedd3ca646a723e437ac5e84/img/%D0%91%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20(1).png)|
|![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/31c014a73c166de5aedd3ca646a723e437ac5e84/img/%D0%91%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20(2).png)|
|![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/31c014a73c166de5aedd3ca646a723e437ac5e84/img/%D0%91%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.png)|

 **Уровень метилирования и покрытия для каждого образца**
 
 ![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/1d245f3ecf9dbed890521e156af2c876c96aefa3/img/%D1%83%D1%80%D0%BE%D0%B2%D0%B5%D0%BD%D1%8C%201.png)
 ![](https://github.com/ZhukovaJul/hse_hw1_meth/blob/1d245f3ecf9dbed890521e156af2c876c96aefa3/img/%D1%83%D1%80%D0%BE%D0%B2%D0%B5%D0%BD%D1%8C%202.png)
