# MIN und MAX

<show-structure depth="2" />

## MIN

Die `MIN()`-Funktion gibt den kleinsten Wert eines Attributs zurück.

### MIN() - Syntax

````SQL
SELECT MIN(column_name)
FROM table_name
WHERE condition;
````

### MIN() - Beispiel

````SQL
SELECT MIN(Price) AS SmallestPrice
FROM Products;
````

## MAX

Die `MAX()`-Funktion gibt einem den grössten Wert eines Attributs zurück.

### MAX() - Syntax

````SQL
SELECT MAX(column_name)
FROM table_name
WHERE condition;
````

### MAX() - Beispiele

````SQL
SELECT MAX(Price) AS LargestPrice
FROM Products;
````
