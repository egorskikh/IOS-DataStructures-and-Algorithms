# IOS-Data-Structures-and-Algorithms

## 1. Complexity

* Сложность времени - это мера времени, необходимого для запуска алгоритма при увеличении размера входных данных.
* Вы должны знать о постоянном времени, логарифмическом времени, линейном времени, квазилинейном времени и квадратичном времени и уметь упорядочивать их по стоимости.
* Сложность пространства - это мера ресурсов, необходимых для работы алгоритма.
* Обозначение Big O используется для представления общей формы временной и пространственной сложности.
* Сложность во времени и пространстве - это высокоуровневые меры масштабируемости; они не измеряют фактическую скорость самого алгоритма.
* Для небольших наборов данных временная сложность обычно не имеет значения. Квазилинейный алгоритм может быть медленнее линейного алгоритма.

## 2. Set, Dictionary, Array

* Такие функции, как insert (at :) для Array, обладают характеристиками производительности, которые могут снизить производительность при случайном использовании. Если вам нужно часто использовать insert (at :) с индексами в начале массива, вы можете рассмотреть другую структуру данных, такую как связанный список.
* Dictionary лишен возможности поддерживать порядок своих элементов для быстрой вставки и поиска.
* Set гарантирует уникальность набора значений. Набор оптимизирован по скорости и лишен возможности сохранять порядок элементов.

## 3. Stack

* Стек - это структура данных LIFO, принцип «последний пришел - первый ушел».
* Несмотря на свою простоту, стек является ключевой структурой данных для многих проблем.
* Единственные две важные операции для стека - это метод push для добавления элементов и метод pop для удаления элементов.

## 4. LinkedList 

* Связанные списки бывают линейными и однонаправленными. Как только вы переместите ссылку с одного узла на другой, вы не сможете вернуться назад.
* Связанные списки имеют временную сложность O (1) для вставки заголовком. Массивы имеют временную сложность O (n) для вставок заголовком.
* Соответствие протоколам сбора Swift, таким как Sequence и Collection, предлагает множество полезных методов для довольно небольшого количества требований.
* Поведение копирования при записи позволяет достичь семантики значения.
