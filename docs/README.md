# Geometric lib
Решение, позволяющее вычислять площадь и периметр различных геометрических фигур
## Описание функций
###  ${\color {green} \textbf{area()}  }$ 
Используется для нахождения площади фигур
<details>
<summary>${\color {yellow} Для \ прямоугольника \ - \ area(a, b) \ в \ файле \ rectangle.py}$ </summary>
Использует формулу S = a * b.

Принимает 2 целых числа:
  - a (int): длина одной стороны прямоугольника
  - b (int): длина соседней стороны

Возвращает целое число:
  - area (int): площадь искомого прямоугольника

Пример вызова: area(2, 4) -> 8
</details>

<details>
<summary>${\color {yellow} Для \ квадрата - area(a)\ в\ файле\ square.py}$ </summary>

Использует формулу S = a^2.

Принимает целое число:
  - a (int): длина стороны квадрата

Возвращает целое число:
  - area (int): площадь искомого квадрата

Пример вызова: area(2) -> 4

</details>


<details>
  <summary>${\color {yellow} Для \ треугольника\ -\ area(a, h)\ в\ файле\ triangle.py }$ </summary>
Использует формулу S = (a * h) / 2.

Принимает 2 целых числа:
  - a (int): длина одной из сторон треугольника
  - h (int): длина перпендикулярной ей высоты

Возвращает целое число:
  - area (int): площадь искомого треугольника

Пример вызова: area(4, 2) -> 4
</details>
<details> <summary>${\color {yellow} Для \ круга\ -\ area(r)\ в\ файле\ circle.py}$ </summary>
Использует формулу S = $\pi$ * (r ^ 2).

Принимает целое число:
  - r (int): радиус круга

Возвращает дробное число:
  - area (float): площадь искомого круга

Пример вызова: area(4) -> 50.26548245743669
</details>

### ${\color {green} \textbf{Perimeter()}}$
Используется для нахождения периметра фигур

<details>

<summary>${\color {yellow} Для \  прямоугольника\ -\ perimeter(a, b)\ в\ файле\ rectangle.py }$</summary>
Использует формулу S = (a + b) * 2.
Принимает 2 целых числа:
  - a (int): длина одной стороны прямоугольника
  - b (int): длина соседней стороны

Возвращает целое число:
  - perimeter (int): периметр искомого прямоугольника

Пример вызова: perimeter(2, 4) -> 12
</details>

<details>
<summary>${\color {yellow} Для \  квадрата\ -\ perimeter(a)\ в\ файле\ square.py}$ </summary>

Использует формулу S = a * 4.

Принимает целое число:
  - a (int): длина стороны квадрата

Возвращает целое число:
  - perimeter (int): периметр искомого квадрата

Пример вызова: perimeter(2) -> 8

</details>


<details>
  <summary>${\color {yellow} Для \  треугольника\ -\ perimeter(a, b, c)\ в\ файле\ triangle.py }$ </summary>
Использует формулу S = (a * h) / 2.

Принимает 3 целых числа:
  - a (int): длина первой стороны треугольника
  - b (int): длина второй стороны треугольника
  - c (int): длина третьей стороны треугольника

Возвращает целое число:
  - perimeter (int): периметр искомого треугольника

Пример вызова: perimeter(4, 2, 3) -> 9
</details>
<details> <summary> ${\color {yellow} Для \  окружности\ -\ perimeter(r)\ в\ файле\ circle.py }$ </summary>
Использует формулу S = 2 * $\pi$ * r.

Принимает целое число:
  - r (int): радиус окружности

Возвращает дробное число:
  - perimeter (float): длина искомой окружности

Пример вызова: area(4) -> 25.132741228718345
</details>

## Last changes (commits)
* 550faf4 (HEAD -> new_features_465976) bug fixed
* 159f7da added rectangle.py
* d078c8d (origin/main, origin/HEAD, main) L-03: Docs added
* 8ba9aeb L-03: Circle and square added

