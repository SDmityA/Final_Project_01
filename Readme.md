## Итоговая работа

Задача:
Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Алгоритм:
https://github.com/SDmityA/Final_Project_01/blob/aea1ad7dfad2d1cc45d20ddc261967e3678a5cbf/Alg.JPG

Описание алгоритма:

Запрашиваем у пользователя сколько элементов он хочет задать и просим ввести нужное количество элементов с использованием цикла, так заполняется стартовый массив элементами.
Далее проходим по стартовому массиву в цикле и проверяем, подходит ли элемент условию "длина символов (len) <= 3". Если элемент подходит под данное условие, то мы добавляем его в новый массив, используя при этом  счетчик ind, чтобы элементы в новом массиве заполнялись последовательно.
