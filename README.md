# korzun
a lil repo containing all the shit of our efforts

Задача 1 
1) [DONE]

Задача 2

2.1
1) Добавить комментарии о том, почему построили так [DONE]
2) Убрать жирный шрифт [DONE]
3) Упростить бнф в 2.1 (<предл>,<предл> - сложно и неэффективно). Например:
<предл> -> <простое предл> | <простое предл><предл> [DONE]
4) Придумать в 2.1 свои примеры "генерации" предложений через бнф и нарисовать для них деревья (eat with pleasure, eat some shit) [DONE]

2.2
- бнф с определением разбить на две строки, пояснить рекурсию [DONE]
- низкоуровневые бнф вниз списка [DONE]
- можно сделать вариант дерева с 0 прилагательных, добавить отсутствие прилагательных в бнф [skip xuini]

2.3
- [done]

Задача 3

Псевдомашинный код
1) Использование регистров - не понятно, что хранит каждый регистр. Указать это явно (double) [DONE]
2) Регистры не надо декларировать [DONE]
3) Команда mov - разделить mov для регистра, и для константы, и для памяти (переменных). Сделать три отдельные команды. [DONE]
4) Опечатка в div (ri) [DONE]
5) decl - убрать вообще [DONE: не надо]
Пример кода
1) В заголовке - пример, в предыдущем слайде - описание кода [DONE]
2) Вверху добавить само выражение [DONE]
3) Поправить decl, т.е. убрать вообще [DONE: не надо]
4) Указывать явные адреса для переменных - лучше в квадратных скобках [DONE: у нас в круглых, почти как в AT&T синтаксисе]
5) Комментарии правильные! Пиздато. [DONE]
6) Упомянуть, где будет финальный результат сохраняться. В регистре t0. [DONE]
Информационная таблица
1) Не видно, что в таблице строки есть, добавить с многоточиями [DONE: забили болт, нахер надо]
2) Номера строк [DONE]
3) Не использовать слово лексема. Заменить на операнды или аргументы арифметического выражения. [DONE: не надо]
4) 2- имя операнда, 3 - значение операнда [DONE: у нас 2 - значение, 3 - имя операнда, как в AT&T синтаксисе]
5) Пример должен быть сразу здесь 

в)
- описать, что должен делать анализатор(находить лексемы) [DONE]
- мало информации в списке [DONE]
- список, начинается с самых сущесвенных.
например...
обозночение: ID
атрибут...
действия при распознавании:
NUM
пример работы ЛА - по кадоровое выполнение. [DONE]
Поменять таблицу.
шаг два/три - не понятные
Процесс итеративный:
Нашёл лексемы - выполнил действие - добавил в таблицу.

г)
- буква в названии [DONE]
- комментарии БНФ - поменять
"используемый набор для записи выражений"
какие операции поддерживаются
<num> -> NUM
добавить таблицу на каждом кадре [DONE]
  
д)
- буква в названии [DONE]
- разбить на варианты [DONE: не понятно, но вроде есть]

Задача 4
- исправить регулярку (... | 11), новая схема ДКА + таблица
- Добавить поэтапное построение ДКА в 7.4 [DONE]
- Добавить обоснование верности ДКА в 7.4 [DONE]

Задача 5
1) [DONE]

Задача 6
1) (а) Цепочки которые не подходят возможно излишни. Самое важное понять описываемые цепочки.
Нужно обоснование, почему именно такие цепочки. Удобно сделать его схематичным описанием построения синтаксического дерева. В кроне дерева должны получить а...а + а...а. Дерево не для конкретного примера, а для общего случая (где-то в дереве будут многоточия).

2) (б) Должны быть итерации алгоритма поиска бесплодных символов с лекции. Добавить слайд с формальным алгоритмом и показать, что алгоритм не нашел бесплодные символы.

3) (в) Добавить слайд с формальным алгоритмом и показать, что он не нашел недостижимых вершин. Надо построить ориентированный граф,. как на лекции, и в этом графе убедиться что из начальной вершины есть путь до любого другого символа.
Устранение неоднозначности - забыть про исходную грамматику, и для множества цепочек а...а + а...а предложить набор бнф. Обосновать однозначность.
