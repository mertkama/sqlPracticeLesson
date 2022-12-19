# sqlPracticeLesson

Now that we know the database is empty, let’s create a new celebs table.

In the code editor, type:

```
CREATE TABLE celebs (
  id INTEGER,
  name TEXT,
  age INTEGER
);
```

We will learn how to view this table in a later exercise after we have added some data to it.

The `INSERT` statement inserts a new row into a table.
We can use the `INSERT` statement when you want to add new records. The statement below enters a record for `Justin Bieber` into the celebs table.

INSERT INTO is a clause that adds the specified row or rows.
celebs is the table the row is added to.
(id, name, age) is a parameter identifying the columns that data will be inserted into.
VALUES is a clause that indicates the data being inserted.
(1, 'Justin Bieber', 22) is a parameter identifying the values being inserted.
'Justin Bieber': text that will be added to name column
22: an integer that will be added to age column.

Add three more celebrities to the table. Beneath your previous INSERT statement type:
```
INSERT INTO celebs (id, name, age) 
VALUES (2, 'Beyonce Knowles', 33); 
 
INSERT INTO celebs (id, name, age) 
VALUES (3, 'Jeremy Lin', 26); 
 
INSERT INTO celebs (id, name, age) 
VALUES (4, 'Taylor Swift', 26); 
```
Look at the Database Schema. How many rows are in the celebs table now?

<--there are 4 rows-->