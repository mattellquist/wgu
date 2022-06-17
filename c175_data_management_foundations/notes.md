# Database Foundations

### Keys and unique values

Keys refer to only one record.

- **Primary Key** is the most important key.  A table doesn't require a **primary key**.
	- Can also be referred to as a **Surrogate Key** or **Synthetic Key**.
- **Composite Key** is a key comprised of two or more fields taken together to act as a unique identifier.
- **Candidate Key** Any piece of data that uniquely represents a row is a candidate key, and if you have a value that occurs in the data naturally, that's a natural key.
- **Foreign keys** A foreign key is a column, or group of columns, that refer to a primary key. Non-NULL foreign key values must match some value of the primary key. The data types of the foreign and primary keys must be the same, but the names may be different. In this material, an empty circle (○) precedes foreign keys in table examples.

### Types of Database Relationships

- one-to-many
	- most common
	- associates one record in one table to many records in another table
- many-to-many
- one-to-one
	- least common

An associative (or linking) table relates foreign keys from different tables to associate their records.

### ACID and Transactions
**A**tomic - Means that something can't be broken down into smaller pieces. Here, atomicity means that the transaction behaves as one single action.
**C**onsistent - Consistency means that the transaction preserves the integrity of data in the database. There's another term for the idea that a transaction can't be treated as smaller pieces.
**I**solated
**D**urable - Durability requires that data changed by the transaction is written to the database.