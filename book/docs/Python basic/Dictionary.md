# Dictionary - словарь

***

Словарь - это коллекция, в которой храняться неупорядоченные, изменяемые и неповторяющиеся элементы. Словари хранят данные в виде ключ-значение. Также словари называют ассоциативными массивами или хеш-таблицами.
Словари записываются в фигурных скобках и имеют ключи и значнения.

## Методы создания словарей

- Создание с помощью литерала (введения значений):

```python
>>> book_prices = {'red book': 100, 'green book': 200, 'SQL Expert': 400}
>>> book_prices
{'red book': 100, 'green book': 200, 'SQL Expert': 400}
>>> type(book_prices)
<class 'dict'>

>>> empty_dict = {}
>>> empty_dict
{}
>>> type(empty_dict)
<class 'dict'>
```

- Создание словаря с помощью класса `dict`:

```python
>>> book_prices = dict(red_book=100, green_book=200, sql_expert=400)
>>> book_prices
{'red_book': 100, 'green_book': 200, 'sql_expert': 400}

>>> empty_dict = dict()
>>> empty_dict
{}
```

- Создание словаря с помощью метода `fromkeys` класса `dict`. Данный метод возвращает словарь с указанными ключами и указанным значением для всех записей словаря:

```python
>>> book_prices = dict.fromkeys(('red book', 'green book', 'SQL Expert'), 100)
>>> book_prices
{'red book': 100, 'green book': 100, 'SQL Expert': 100}

>>> empty_dict = dict.fromkeys(())
>>> empty_dict
{}
```

Синтаксис данного метода:

```python
dict.fromkeys(keys, value)
```

где  `keys` - список ключей, `value` - значение для всех ключей (если значение атриубута не указано, то он принимает значение `None`)

- Создание словаря с помощью генератора словарей:

```python
>>> squares = {num: num ** 2 for num in range(5)}
>>> squares
{0: 0, 1: 1, 2: 4, 3: 9, 4: 16}
```



```python

```

```python

```

```python

```

```python

```

```python

```

```python

```
