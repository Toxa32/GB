# GB
Задача: Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры: ["hello", "2", "world", ":-)"] -> ["2", ":-)"] ["1234", "1567", "-2", "computer science"] -> ["-2"] ["Russia", "Denmark", "Kazan"] -> []

Решение задачи

Создаем блок ввода исходных данных, согласно заданию и вывода на экран полученного массива. Создаем функция определения количества элемента массива длина которых меньше какой-то заданной длины length Для наглядности выводим его на экран с помощью метода PrintArray.

Через цикл с счетчиками result = 0 и i = 0 ищем и считаем элементы длина которых меньше либо равна 3 символадлина которых меньше либо равна 3 символа. для данной операции создаем функцию CheckArray.

Задаем numbers новую переменную в которую будем присваивать вычесленный элемент массива меньше либо равна 3 символа с помощью метода CheckArray

Задаем новый массив строк newArrayStrings, который формировуется перебором элементов массива arrayStrings, размером, равным переменной numbers

Формируем новый массива строк с помощью метода NewArray . Cравнением количества их элементов с переменной length и добавлением в массив newArray элемента, удовлетворяющего условию.

На выходе метода получается заполненный массив строк newArrayStrings, удовлетворяющий условию, что и является решением задачи. Для наглядности выводим его на экран с помощью метода PrintArray.
