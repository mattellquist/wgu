An SQL statement is a database command, such as a query that inserts, retrieves, updates, or deletes data:

    INSERT inserts rows into a table.
    SELECT retrieves data from a table.
    UPDATE modifies data in a table.
    DELETE deletes rows from a table.

# CRUD

## Insert
```sql
INSERT into account values (290, Matt Ell, 5000);
```

## Retrieve
```sql
SELECT name FROM account where balance > 3000;
```

## Update
```sql
UPATE account SET balance = 4500 WHERE ID = 1234;
```

## Delete
```sql
DELETE FROM account WHERE ID = 1234;
```


# Creating tables with SQL

The SQL CREATE TABLE statement creates a new table by specifying the table and column names. Each column is assigned a data type that indicates the format of column values. Data types can be numeric, textual, or complex. Ex:

    INT stores integer values.
    DECIMAL stores fractional numeric values.
    VARCHAR stores textual values.
    DATE stores year, month, and day.

```sql
CREATE TABLE Movie (
  ID INT,
  Title VARCHAR(100),
  Rating VARCHAR(5),
  ReleaseDate DATE
);
```

## Inserting into the new table

```sql
INSERT INTO Movie VALUES
  (1, 'Rogue One: A Star Wars Story', 'PG-13', '2016-12-10'),
  (2, 'Hidden Figures', 'PG', '2017-01-06'),
  (3, 'Toy Story', 'G', '1995-11-22'),
  (4, 'Avengers: Endgame', 'PG-13', '2019-04-26'),
  (5, 'The Godfather', 'R', '1972-03-14');
```
