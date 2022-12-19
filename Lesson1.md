SELECT statements are used to fetch data from a database. In the statement below, SELECT returns all data in the name column of the celebs table.

```
SELECT name FROM celebs;
```

1. `SELECT` is a clause that indicates that the statement is a query. You will use `SELECT` every time you query data from a database.
2. `name` specifies the column to query data from.
3. `FROM` celebs specifies the `name` of the table to query data from. In this statement, data is queried from the celebs table.

You can also query data from all columns in a table with `SELECT`.

1. Let’s take a closer look at `SELECT` and retrieve all the names in the celebs table. In the code editor, type:

```
SELECT name FROM celebs; 
```

Delete your previous `SELECT` statement from the code editor.

To `SELECT` all the data in the `celebs` table, enter the following statement in the code editor using the `*` wildcard character: