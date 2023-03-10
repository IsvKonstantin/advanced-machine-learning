# Байесовская сеть

## Набор данных

Изучите существующие форматы представления Байесовских сетей.
Выберите любой из понравившихся вам форматов. Вы можете использовать
любую стороннюю библиотеку для чтения (разбора) Байесовских сетей.

Выберите любую Байесовскую сеть. Например их можно найти тут:
* http://www.bnlearn.com/bnrepository/
* http://www.cs.huji.ac.il/~galel/Repository/

## Задача
Реализуйте два алгоритма подсчёта вероятности по Байесовской сети. Они должны искать совместную вероятность комбинации из нескольких событий
(не обязательно всех). Например:  `P(A = ai & B = bj & D = dk)`, где событие C может быть любым.

* Первый алгоритм должен точно вычислять вероятность перебирая все возможные комбинации из значений пропущенных событий.
* Второй алгоритм должен случайно сэмплировать комбинации событий по распределению, которое задаёт Байесовская сеть,
и оценивать вероятность заданной комбинации событий частотным методом исходя из числа сэмплированных комбинации, которые содержат заданную.

Выберите комбинацию событий для запроса. Сравните значения вероятностей заданной комбинации, полученные первым и вторым алгоритмом.
Постройте график зависимости вероятности заданной комбинации, которую оценил второй алгоритм в зависимости от числа сэмплированных комбинаций.

## Примечание
Не стоит строго фиксировать набор данных и запрос. Код должен быть написан так, чтобы их можно было в любой момент поменять.
