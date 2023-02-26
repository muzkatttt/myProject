# myProject
#### Условия задачи: Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
Примеры   [“hello”, “2”, “world”, “:-)”] → [“2”, “:-)”];
          [“1234”, “1567”, “-2”, “computer science”] → [“-2”];
          [“Russia”, “Denmark”, “Kazan”] → [];
## Ход выполнения задачи
#### 1. Инициализируем массив с заданным пользователем количеством строковых элементов.
 Для этого спросим у пользователя, какое количество строковых элементов он желает ввести в массив (с консоли необходимо ввести числовое значение). Пользователем с консоли осуществляется ввод элементов массива. Преобразуем введенные пользователем строки в массив для обработки.
#### 2. Вычисляем количество строковых элементов массива, длина которых меньше четырех. 
Для этого инициализируем дополнительную переменную j, равную нулю.  Через чикл проходим по каждой строке массива и вычисляем, длина элемента массива меньше 4-х или нет. Если длина элемента массива меньше 4-х, то запоминаем его для вывода в итоговом массиве в консоли, если же длина элемента больше 4-х, то пропускаем его. К счетчику прибаваляем + 1 элемент.
#### 3. Выводим итоговый массив с длиной элементов менее 4-х на консоль.

