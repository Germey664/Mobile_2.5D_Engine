# Clasificator
Начальная версия программы по классификации параметров, для предсказания неизвестных результатов.
Предположим что стоит задача, решить совершать определенное действие или нет, в зависимости от входных параметров.
Связь между параметрами и необходимостью совершить действие не известна. Как решить подобную задачу.
Может перейти идея использовать упрошенную нейросеть. В процессе работы, она найдет зависимости и будет давать какие-то предсказания.
Мне это делать не хочется. Поэтому пойдем другим путем. Этот алгоритм должен составлять аппроксимированную функцию зависимости вероятности необходимости действия от значения параметра. Это также предполагает поиск связи между параметрами. (Отличие функции с одним параметром от функции группы параметров)

Результатом работы алгоритма должны быть данные достаточные для определения стратегии. Отдельно должны быть выделены особенные значения параметров, такие при которых вероятность однозначна. Точно да или точно нет.

0.1 Рабочая программа. Умеет находить зависимость вероятности от одной переменной (Условно). На тестовых данных дает результаты 75%. Но без уверенности.
Не умеет находить зависимости между переменными. Дает сильно искаженную вероятность. 