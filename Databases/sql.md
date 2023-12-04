## My SQL commands 


### 1. **DDL** (Data Defintition Language) Commands

1) **CREATE** : To create new database objects
2) **ALTER** : To modfiy existing database objects
3) **DROP** : To delete existing database objects
4) **TRUNCATE** : To remove all rows from table


#### Commands for Databases

1) **CREATE**
2) **DROP**



Creating Database 

```
CREATE DATABASE db_name
```

```
CREATE DATABASE IF NOT EXISTS db_name
```

Deleting Database

```
DROP DATABASE db_name
```

```
DROP DATABASE IF EXISTS db_name
```

#### Commands for Tables

1) **CREATE**
2) **TRUNCATE**
3) **DROP**

Creating Table in the Database

```
CREATE TABLE table_name(
    col_name1 data_type,
    col_name2 data_type,
    col_name3 data_type
)
```

Truncating rows in the table in the database

```
TRUNCATE TABLE table_name
```

Droping the table in the database

```
DROP TABLE IF EXISTS table_name
```

#### Constraints 

1. **NOT NULL**
2. **UNIQUE**
3. **PRIMARY KEY**
4. **AUTO INCREMENT**
5. **CHECK**
6. **DEFAULT**
7. **FOREIGN KEY**

#### Referential Actions

1. **RESTRICT**
2. **CASCADE**
3. **SET NULL**
4. **SET DEFAULT**