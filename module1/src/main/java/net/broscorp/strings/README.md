# String

## Алгоритм выполнения

1.	Написать метод, который определяет, является ли слово палиндромом.
2.	Написать методы, которые из словосочетания "_Hello World_":
    1.	Оставляет только слово _Hello_.
    2.	Удаляет все буквы "_l_" в строке.
    3.	Меняет все буквы "_о_" на букву "_q_".
    4.	Выводит список слов и количество букв в соответствующем слове.
3.	Написать метод, который получает два числа – количество багов и количество куплетов и возвращает текст песни
```
%n little bugs in the code, 
%n little bugs in the code. 
Take one down, patch it around %m little bugs in the code.
```
Где _m = n - 10 + random.nextInt(20)_
Для следующего куплета обновляем _n = m_.
Чтоб результаты вызова метода были повторяемы – инициализировать __random__ произведением параметров метода.
4.	Покрыть весь код [тестами](https://github.com/Broscorp-net/traineeship/blob/master/tests.md).

## Источники для выполнения задания:
1.	https://www.vogella.com/tutorials/JUnit/article.html


