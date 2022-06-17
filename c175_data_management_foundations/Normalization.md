# Normalization

### Normal Forms
**Normal forms** are rules for designing tables with less redundancy. Normal forms are numbered, first normal form through fifth normal form.  The six normal forms comprise a sequence, with each normal form allowing less redundancy than the prior normal form.

### 1st Normal Form (1NF)
- First normal form is the least restrictive normal form and allows the most types of redundancy.
- Tables with a primary key are in first normal form.

### 2nd Normal Form (2NF)
- A table is in second normal form when all non-key columns depend on the whole primary key. In other words, a non-key column cannot depend on part of a composite primary key. A table with a simple primary key is automatically in second normal form.
- Second normal form eliminates some redundancy.

### 3rd Normal Form (3NF)
- Redundancy can occur in a second normal form table when a non-key column depends on another non-key column. Informally, a table is in third normal form when all non-key columns depend on the key, the whole key, and nothing but the key.
- Third normal form eliminates most redundancy.

### Boyce-Codd
Redundancy occurs when a column depends on a non-unique column . Boyce-Codd normal form eliminates all such functional dependencies, and therefore all associated redundancy.

### 4th Normal Form (4NF)
Informally, a multivalued dependency occurs when two independent plural attributes are implemented in the same table. To achieve fourth normal form, independent plural attributes must be implemented in separate tables.

### 5th Normal Form (5NF)
No redundancy. Eliminates join dependencies and associated redundancy.

