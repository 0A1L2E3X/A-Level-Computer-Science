
QUERY

- creating query
~~~sql
SELECT <'field name'>
FROM <'table name'>
WHERE <'condition'>;
~~~

- sort in order of
~~~sql
ORDER BY <'field name'>
~~~

- arrange into groups
~~~sql
GROUP BY <'field name'>
~~~

- join table using foreign keys
~~~sql
INNER JOIN
~~~


MAINTENANCE

- add data
~~~sql
INSERT INTO <'table name'> (
	'field 1',
	'field 2'...
)
VALUES ('val 1', 'val 2'...);
~~~

- delete data
~~~sql
DELETE FROM <'table name'>
WHERE <'condition'>;
~~~

- update a field to table
~~~sql
UPDATE <'table name'>
SET <'field name'> = <'value'>
WHERE <'condition'>
~~~


[[SQL Syntax]]