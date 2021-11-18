# OTUS C++ Basic курс

## Задание "Расчёт статистических характеристик последовательности"

На вход (стандартный ввод) приложению подаётся последовательность (заранее неизвестного
размера) числовых значений. Приложение должно в ходе своей работы считать всю
последовательность из стандартного ввода и вывести на экран набор следующих статистических
характеристик:
- min – минимальное значение из последовательности
- max – максимальное значение из последовательности
- mean – арифметическое среднее, посчитанное на основе всех элементов последовательности
- std - среднеквадратическое отклонение

## Инструкция по сборке

Требуется компилятор с поддержкой C++17

Для сборки проекта необходимo выполнить следующие команды
```
mkdir build && cd build
cmake ..
cmake --build .
```