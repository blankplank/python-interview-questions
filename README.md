# **Python**

*Справка для собеседования*



#### Сколько времени вы программируете на Python?

​	...

#### Какой у вас уровень?

​	...

#### Какой вид задач выполняли? 

​	...

#### Почему решили выбрать именно Python?

​	...

#### Что вам нравится / не нравится в Python? 

​	...

#### Достоинства и недостатки языка. 

​	...

#### Версия Python на которой вы писали. 

​	...

#### Основные типы данных в Python

​	**Числовые типы данных в Python** (Numeric Types)

​		*int* - это целые числа `3, 76, 900_183`

​		*float* - вещественныечисла `2.16, 1.5e2, 10_231.32`

​		*complex* – комплексные числа `14 + 1j  .real .imag`

​		*decimal* - вещественные числа с фиксированной точностью

​		*fractions* -рациональные числа (дроби)

​		*long* (python 2) – для больших значений int 

​	**Логический тип bool** (True/False)

​	**Строки** (Text Sequence Type) 

​		*str* – строки `'abc'`

​	**NoneType** (None) – отсутствие значения

​	**Последовательности** (Sequence Types )

​		*Списки*  (list) - упорядоченные изменяемые коллекции объектов произвольных типов (почти

​		как массив, но типы могут отличаться) `[x, y, z ]`

​		*Кортежи* (tuple) – неизменяемый список `1,2,3,4 или (1,2,3,4)`

​		*Диапазон*(range)- неизменяемая последовательность целых чисел `range(1,5)`

​	**BinarySequence Types**

​		*bytes* – байтовые строки `b'.\xf0\xf1\xf2'`

​		*bytearray* – массив байт `bytearray(b'hello world!')`

​	**Множества** (Set Types)

​		*Множества* (set) - "контейнер", содержащий не повторяющиеся элементы в случайном

​		порядке ( {x,y,z} )

​		*frozenset* – неизменяемое множество `frozenset([x,y,z])`

​	**Mapping Types**

​		*Словари* (dict) - неупорядоченные коллекции произвольных объектов сдоступом по ключу. 

​		Их иногда ещё называют ассоциативными массивами или хеш-таблицами. `{key:value}`



#### Какая разница между tuple и list?

*tuple* – неизменяемый, *list* – изменяемый

*Списки*  (list) - упорядоченные изменяемые коллекции объектов произвольных типов (почти как массив, но типы могут отличаться) `[x, y, z ]`

*Кортежи* (tuple) – неизменяемый список `1,2,3,4 или (1,2,3,4)`



#### Для чего используется set?

*Множества* (set) - "контейнер", содержащий не повторяющиеся элементы в случайном порядке 

`{x,y,z}`



#### Какие стандартные библиотеки вы использовали?

...

(стоит почитать – data, регулярные выражения и т.д.)



#### PEP8. Нужно ли его использовать?

Документ описывает соглашение о том, как писать код для языка python, включая стандартную библиотеку, входящую в состав python. 

Ключевая идея такова: <u>код читается намного больше раз, чем пишется</u>. Рекомендации о стиле написания кода направлены на то, чтобы <u>улучшить читаемость кода и сделать его согласованным между большим числом проектов</u>. В идеале, весь код будет написан в едином стиле, и любой сможет легко его прочесть.

Это руководство о согласованности иединстве. Согласованность с этим руководством очень важна. Согласованность внутри одного проекта еще важнее. А согласованность внутри модуля или функции — самое важное. Но важно помнить, что иногда это руководство неприменимо, и понимать, когда можно отойти от рекомендаций. Когда вы сомневаетесь, просто посмотрите на другие примеры и решите, какой выглядит лучше.

Две причины для того, чтобы *нарушить* данные правила:

- Когда применение правила сделает код менее читаемым даже для того, кто привык читать код, 	который следует правилам.
- Чтобы писать в едином стиле с кодом, который уже есть в проекте и который нарушает правила (возможно, в силу исторических причин) — впрочем, это возможность переписать чужой код.



#### Swap 2 variables

```python
a, b = b, a
```



#### Отличия range и xrange?

Python2. range - хранит в памяти всю последовательность, xrange – только начальные и конечные значения (генератор)

Python 3. range = xrange из python 2



#### Простая задача на нахождения минимума / максимума в list.

```python
min([65,45,99])

max([65,45,99])
```



#### Удаление повторяющихся элементов в list

```python
list(set([7,7,21]))
```



#### Разделение строки по символу

```python
'a_b_c_d'.split('_')
```


