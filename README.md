*Задача*: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

1. Разработанная блок-схема решения задачи проедставлена в файле Block_diagram.drawio и файле .

2. Описание решения задачи:


Задаем массив *array* типа *string* и выводим его на печать. Также объявляем новый массив *newArray* типа *string*. Длины массивов равны. 
Заполнение массива *newArray* происходит с помощью метода *ToNewArray*.
В методе *ToNewArray* задаем переменную *index*, для поочередного присваивания значений из заданного массива в новый.
Для перебора индексов заданного массива применяем цикл For, соразмерный длине массива, внутри цикла проводится проверка требуемого условия *(является ли количество символов в значениях массива <=3)* c помощью оператра If. 
Если условие выполняется, элемент массива заносится в *index элемент* нового массива. После присвоения, переменная *index* увеличивается на 1 и возвращается к циклу for в котором *i* увеличивается на 1, проверка выполняется по всей длине заданного массива.
Далее для вывода на печать нового массива прибегаем к помощи метода PrintArray. В котором с помощью цикла For перебираем все значения нового массива *(i++)* и выводим их на печать.

