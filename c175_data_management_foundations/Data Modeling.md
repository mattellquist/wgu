# Data Modeling

An entity is an object or event in our environment that we want to keep track of. A person is an entity. So is a building, a piece of inventory sitting on a shelf, a finished product ready for sale, and a sales meeting (an event).

An attribute is a property or characteristic of an entity. Examples of attributes include an employee’s employee number, the weight of an automobile, a company’s address, or the date of a sales meeting.

#### One-to-One
one-to-one (1-1) binary relationship, which means that a single occurrence of one entity type can be associated with a single occurrence of the other entity type and vice versa

Example: A particular salesperson is assigned to one office. Conversely, a particular office (in this case they are all private offices!) has just one salesperson assigned to it.

#### One-to-Many
A single occurrence of one entity type can be associated with man occurrence of the other entity type.

Example: a one-to-many (1-M) binary relationship between salespersons and customers; one sales person can have many customers.

#### Many-to-Many
A salesperson is authorized to sell many products; a product can be sold by many salespersons.


#### Modality
Modality, the minimum number of entity occurrences that can be involved in a relationship

![[Pasted image 20220416180257.png]]

