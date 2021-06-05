# IOS-Data-Structures-and-Algorithms

### Key points
* [Complexity](https://github.com/egorskikh/IOS-Data-Structures-and-Algorithms#1-complexity)
* [Set, Dictionary, Array](https://github.com/egorskikh/IOS-Data-Structures-and-Algorithms#2-set-dictionary-array)
* [Stack](https://github.com/egorskikh/IOS-Data-Structures-and-Algorithms#3-stack) 
* [LinkedList](https://github.com/egorskikh/IOS-Data-Structures-and-Algorithms#4-linkedlist)
* [Queues](https://github.com/egorskikh/IOS-Data-Structures-and-Algorithms#5-queues)

## Section 1. Introduction
### 1. Complexity

 - [example](https://github.com/egorskikh/IOS-Data-Structures-and-Algorithms/blob/main/Section%201.%20Introduction/1.%20Complexity/Complexity.swift)
* Сложность времени - это мера времени, необходимого для запуска алгоритма при увеличении размера входных данных.
* Вы должны знать о постоянном времени, логарифмическом времени, линейном времени, квазилинейном времени и квадратичном времени и уметь упорядочивать их по стоимости.
* Сложность пространства - это мера ресурсов, необходимых для работы алгоритма.
* Обозначение Big O используется для представления общей формы временной и пространственной сложности.
* Сложность во времени и пространстве - это высокоуровневые меры масштабируемости; они не измеряют фактическую скорость самого алгоритма.
* Для небольших наборов данных временная сложность обычно не имеет значения. Квазилинейный алгоритм может быть медленнее линейного алгоритма.

### 2. Set, Dictionary, Array

* Такие функции, как insert (at :) для Array, обладают характеристиками производительности, которые могут снизить производительность при случайном использовании. Если вам нужно часто использовать insert (at :) с индексами в начале массива, вы можете рассмотреть другую структуру данных, такую как связанный список.
* Dictionary лишен возможности поддерживать порядок своих элементов для быстрой вставки и поиска.
* Set гарантирует уникальность набора значений. Набор оптимизирован по скорости и лишен возможности сохранять порядок элементов.

## Section 2. Elementary Data Structures
### 3. Stack
- [example](https://github.com/egorskikh/IOS-Data-Structures-and-Algorithms/blob/main/Section%202.%20Elementary%20Data%20Structures/2.%20Stacks/Stacks.playground/Sources/Stack.swift)
* Стек - это структура данных LIFO, принцип «последний пришел - первый ушел».
* Несмотря на свою простоту, стек является ключевой структурой данных для многих проблем.
* Единственные две важные операции для стека - это метод push для добавления элементов и метод pop для удаления элементов.

### 4. LinkedList 
 - [example](https://github.com/egorskikh/IOS-Data-Structures-and-Algorithms/blob/main/Section%202.%20Elementary%20Data%20Structures/3.%20LinkedList/LinkedList.playground/Sources/LinkedList.swift)
* Связанные списки бывают линейными и однонаправленными. Как только вы переместите ссылку с одного узла на другой, вы не сможете вернуться назад.
* Связанные списки имеют временную сложность O (1) для вставки заголовком. Массивы имеют временную сложность O (n) для вставок заголовком.
* Соответствие протоколам сбора Swift, таким как Sequence и Collection, предлагает множество полезных методов для довольно небольшого количества требований.
* Поведение копирования при записи позволяет достичь семантики значения.

### 5. Queues
 - [example](https://github.com/egorskikh/IOS-Data-Structures-and-Algorithms/blob/main/Section%202.%20Elementary%20Data%20Structures/4.%20Queues/Queue.playground/Sources/Queue.swift)
* Очередь использует стратегию FIFO, элемент, добавленный первым, также должен быть сначала удален.
* Enqueue вставляет элемент в конец очереди.
* Dequeue удаляет элемент в начале очереди.
* Элементы в массиве размещаются в непрерывных блоках памяти, тогда как элементы в связанном списке более разбросаны, что может привести к промахам в кэше.
* Реализация на основе кольцевой буферной очереди хороша для очередей с фиксированным размером.
* По сравнению с другими структурами данных, использование двух стеков улучшает
dequeue (_ :) временная сложность до амортизированной операции O (1).
* Реализация двойного стека превосходит Linked-list с точки зрения пространственной локализации.
