#### INNER JOIN
Это дефолтный join. Объединяет только те строки в которых у join-колонки таблицы 1 совпадение с join-колонкой таблицы 2.

```ad-hint
collapse: open
title: Пример 
~~~~~
SELECT 
  t1.column1, 
  t2.column2 
FROM 
  table1 t1 
  INNER JOIN table1 t2 ON t1.id = t2.id;
~~~~~ 
```

#### LEFT JOIN
Взять все строки из таблицы 1, а также объединить строки в которых у join-колонки таблицы 1 совпадение с join-колонкой таблицы 2.

```ad-hint
collapse: open
title: Пример 
~~~~~
SELECT 
  t1.column1, 
  t2.column2 
FROM 
  table1 t1 
  LEFT JOIN table1 t2 ON t1.id = t2.id;
~~~~~ 
```


