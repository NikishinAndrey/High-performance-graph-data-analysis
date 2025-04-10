# Задача 2. Реализация подсчёта треугольников

##  Условие задачи

- [x] Используя `python-graphblas` реализовать наивный алгоритм, для матрицы смежности $A$ вычисляющий $A^3$ и возвращающий количество треугольников неориентированного графа.
  - Функция принимает представление неориентированного графа, удобное для неё (загрузка, конвертация и проверка неориентированности реализованы отдельно).
  - Функция возвращает число --- количество треугольников в графе.
- [x] Используя `python-graphblas` реализовать наивный алгоритм с маской, для матрицы смежности $A$ вычисляющий $A^2$ и возвращающий количество треугольников неориентированного графа.
  - Функция принимает представление неориентированного графа, удобное для неё (загрузка, конвертация и проверка неориентированности реализованы отдельно).
  - Функция возвращает число --- количество треугольников в графе.
- [x] Используя `python-graphblas` реализовать Сohen's algorithm, вычисляющий количество треугольников неориентированного графа.
  - Функция принимает представление неориентированного графа, удобное для неё (загрузка, конвертация и проверка неориентированности реализованы отдельно).
  - Функция возвращает число --- количество треугольников в графе.
- [x] Используя `python-graphblas` реализовать Sandia algorithm, вычисляющий количество треугольников неориентированного графа.
  - Функция принимает представление неориентированного графа, удобное для неё (загрузка, конвертация и проверка неориентированности реализованы отдельно).
  - Функция возвращает число --- количество треугольников в графе.
- [x] (+2 балла) Используя `python-graphblas` реализовать функцию, вычисляющую для каждой вершины неориентированного графа количество треугольников, в которых она участвует.
  - Функция принимает представление неориентированного графа, удобное для неё (загрузка, конвертация и проверка неориентированности реализованы отдельно).
  - Функция возвращает массив, где для каждой вершины указано, в скольки треугольниках она участвует.
- [x] Добавить тесты для проверки корректности полученных реализаций.
- [x] (+1 балл) Скачать 10 графов в формате `Matrix Market` с сайта [SuiteSparse Matrix Collection](https://sparse.tamu.edu/) и оценить время работы всех полученных реализаций. Сделать выводы.
  - В качестве фильтров для поиска графов на сайте использовать следующие значения: `Rutherford-Boeing Type` = `Binary`, `Special Structure` = `Symmetric`, `Nonzeros.Min` = 10000.
- [x] (+2 балла) Реализовать генератор случайных неориентированных графов, в котором можно задавать количество вершин и степень разреженности графа. Путём генерации случайных графов различного размера и с разной степенью разреженности, оценить время работы всех полученных реализаций и исследовать границы их применимости. Сделать выводы.
