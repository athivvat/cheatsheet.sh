# Google BigQuery

## Simple Queries

### Retrieving Rows by Using `SELECT`

```sql
SELECT
    column_1, column_2
FROM
    project_id.dataset.table_or_view

```

### Aliasing Column Names with `AS`
```sql
SELECT
    column_1, column_2 AS alias_name
FROM
    project_id.dataset.table_or_view
```

### Filtering with `WHERE`
```sql
SELECT
    column_1, column_2
FROM
    project_id.dataset.table_or_view
WHERE condition
```
Note: The `WHERE` clause operates on the columns in the `FROM` clause; thus, it is not posible to reference aliases from the `SELECT` list in the WHERE clause.

```sql
SELECT
    column_1, column_2 as alias_name
FROM
    project_id.dataset.table_or_view
WHERE alias_name < 10 -- CAN NOT REFERENCE ALIAS IN WHERE
```

