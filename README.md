## **Задача :**
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа.
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма.
При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

## **Описание алгоритма решения:**
1) Объявляем два массива.

2) Затем создаем метод, а в нем цикл, который равен длинне массива. 

3) Внутри цикла проверка условия, элементов должно быть меньше или равно трем. Если условие соблюдается, то  элемент первого массива заносится в count элемент второго массива.

4) Переменная count нужна для того,чтобы поочередно сохранять значения из первого массива во второй. 

5) После присвоения переменная count увеличивается на 1 и возвращается к циклу for в котором i увеличивается на 1.

6) Так продолжаем до тех пор, пока не пройдем всю длинну.
