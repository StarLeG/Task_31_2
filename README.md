# Задача 2. Реализация класса графа


## Что нужно сделать:
Прочитайте, что такое графы в дискретной математике, как граф можно представить в программе, что такое матрицы смежности и списки смежности. Ссылки на источники даны в «Рекомендациях».
Вам дан базовый интерфейс для представления ориентированного графа. Напишите две реализации интерфейса:
ListGraph, хранящий граф в виде массива списков смежности.
MatrixGraph, хранящий граф в виде матрицы смежности.
Реализуйте конструктор, принимающий IGraph. Такой конструктор должен скопировать переданный граф в создаваемый объект. Обратите внимание, что иногда в одну реализацию графа копируется другая. Реализуйте в том числе все конструкторы копий и операторы присваивания, если это необходимо.


## Рекомендации
Во всех алгоритмах поиска вам потребуются рёбра для вершин. Для этого используйте std::unordered_set и его метод contains.