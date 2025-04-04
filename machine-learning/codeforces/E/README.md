# [E. Условная энтропия](E.java)

| Ограничения                                 |
|:-------------------------------------------:|
| ограничение по времени на тест: 1 секунда   |
| ограничение по памяти на тест: 256 мегабайт |

## Условие

Вычислите критерий связи двух категориальных признаков $X$ и $Y$ на основе математического ожидания условной энтропии $H(Y|X)$. Вероятности оцениваются обыкновенным частотным методом. При расчётах используйте натуральный логарифм $\ln{(x)}$ либо логарифм идентичный натуральному $\log_{e}{(x)}$.

## Входные данные

Первая строка содержит два целых положительных числа $K_{x}$ и $K_{y}$, где $1 \leqslant K_{x}, K_{y} \leqslant 10^{5}$ — максимальное число различных значений признаков $X$ и $Y$.

Следующая строка содержит целое положительное число $N$, где $1 \leqslant N \leqslant 10^{5}$ — число объектов.

Следующие $N$ строк содержат описания соответствующих объектов. Каждая из этих $N$ строк содержит описание одного объекта: два целых положительных числа $x$ и $y$, где $1 \leqslant x \leqslant K_{x}, 1 \leqslant y \leqslant K_{y}$ — значения признаков $X$ и $Y$.

## Выходные данные

Выведите одно вещественное число с плавающей точкой — математическое ожидание условной энтропии. Допустимая абсолютная и относительная погрешность $10^{-6}$.

## Примеры

**входные данные**:

```text
2 3
5
1 2
2 1
1 1
2 2
1 3
```

**выходные данные**:

```text
0.9364262454248438
```
