# Описание репозитория

В данном репозитории находится решение задачи, условие которой приведено ниже:

* Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Решение:
1. Блок-схема алгоритма находится в файле Homework__1.jpg
2. Код программы на языке С# находится в файле Program.cs
3. Описание решения:
* Задаем два массива Array и Result, элементы которых имеют тип данных string;
* Массив Array - исходный массив, Result - результирующий массив;
* Используя цикл for и условие if обрабатываем исходный массив и сохраняем в результирующий только те значения, длины строк которых меньше или равны 3.