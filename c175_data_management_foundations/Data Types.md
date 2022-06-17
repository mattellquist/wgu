# Data Types
- **Integer** data types represent positive and negative integers. Several integer data types exist, varying by the number of bytes allocated for each value. Common integer data types include INT, implemented as 4 bytes of storage, and SMALLINT, implemented as 2 bytes.

 -  **Decimal** data types represent numbers with fractional values. Decimal data types vary by number of digits after the decimal point and maximum size. Common decimal data types include FLOAT and DECIMAL.

-  **Character** data types represent textual characters. Common character data types include CHAR, a fixed string of characters, and VARCHAR, a string of variable length up to a specified maximum size.

- **Time** data types represent date, time, or both. Some time data types include a time zone or specify a time interval. Some time data types represent an interval rather than a point in time. Common time data types include DATE, TIME, DATETIME, and TIMESTAMP.

- **Binar**y data types store data exactly as the data appears in memory or computer files, bit for bit. The database manages binary data as a series of zeros and ones. Common binary data types include BLOB, BINARY, VARBINARY, and IMAGE.

- **Spatial** data types store geometric information, such as lines, polygons, and map coordinates. Examples include POLYGON, POINT, and GEOMETRY. Spatial data types are relatively new and consequently vary greatly across database systems.

- **Document** data types contain textual data in a structured format such as XML or JSON.


![[Pasted image 20220419192141.png]]

---

# Tables Columns and Rows
All data in a relational database is structured in tables:

- A table is a collection of data organized as columns and rows.
- A column is a set of values of the same type. Each column has a name, different from other column names in the table.
    A row is a set of values, one for each column.
  -  A cell is a single column of a single row. In relational databases, each cell contains exactly one value.

A table must have at least one column and any number of rows. A table without rows is called an empty table.

# Structural rules

Tables obey three structural rules:
- **Tables are normalized** — exactly one value exists in each cell.
- **No duplicate column names** — duplicate column names are not allowed in one table. However, the same column name can appear in different tables.
- **No duplicate rows** — no two rows may have identical values in all columns.

NULL and aggregate functions

SQL statements also contain aggregate functions. An aggregate function operates on numeric values from multiple rows, including only rows selected by the WHERE clause. Aggregate functions include:

- **SUM**, which returns the total of selected values.
- **AVG**, which returns the average of selected values.
-  **MAX**, which returns the largest selected value.
- **MIN**, which returns the smallest selected value.

**SUM, AVG, MIN, and MAX** ignore **NULL** values.

