## Задача :
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Описание алгоритма решения:
Сначало объявляются два массива: изначальный и новый массивы одинаковой длины. Затем метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия: длина меньше либо равна 3-м символом, если да, то элемент первого массива заносится в count. Переменная count нужна, чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. После присвоения переменная count увеличивается на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.

## Нарисованная блок-схема метода находится в папке blok-shema.
## Алгоритм находится по пути task/Program.cs