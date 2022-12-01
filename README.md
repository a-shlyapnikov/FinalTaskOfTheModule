# Итоговая проверочная работа
## Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

### Алгоритм решения задачи:
1. Перебираем значений исходного массива
2. Проверка каждого значение массива на соотвествие условию
3. Если строка удовлетворяет требованиям, присваиваем значения в новый массив
4. Повтор пунктов 2 и 3 до окончания исходного массива
5. Вывод нового заполненного массива


### Блок-схема решения задачи:
![Диаграмма](/diagram//Diagram.png)
### Программа:
Для запуска зайдите в папку `TaskProgram` и активируйте программу введя в консоль: **dotnet run**

Далее вводите строки через пробел, например:
```
hello 2 world :-)
```
Пример вывода программы:
```
[hello, 2, world, :-)] -> [hello, 2, world, :-)]
```
