# MySQL Cheatsheet

A quick reference guide for MySQL commands. Perfect for beginners and experts who need a handy reference by their side.

## Contents

- [Database Commands](#database-commands)
- [Table Commands](#table-commands)
- [Data Manipulation Commands](#data-manipulation-commands)

### Database Commands

- **Create Database**
    ```sql
    CREATE DATABASE database_name;
    ```

- **Drop Database**
    ```sql
    DROP DATABASE database_name;
    ```

- **Use Database**
    ```sql
    USE database_name;
    ```

- **Show all Databases**
    ```sql
    SHOW DATABASES;
    ```

### Table Commands

- **Create Table**
    ```sql
    CREATE TABLE table_name (
        column1 datatype,
        column2 datatype,
        ...
    );
    ```

- **Drop Table**
    ```sql
    DROP TABLE table_name;
    ```

- **Show all Tables in a Database**
    ```sql
    SHOW TABLES;
    ```

- **Describe a Table**
    ```sql
    DESCRIBE table_name;
    ```

### Data Manipulation Commands

- **Insert into a Table**
    ```sql
    INSERT INTO table_name (column1, column2, ...) VALUES (value1, value2, ...);
    ```

- **Update a Table**
    ```sql
    UPDATE table_name SET column1 = value1, column2 = value2 WHERE condition;
    ```

- **Delete from a Table**
    ```sql
    DELETE FROM table_name WHERE condition;
    ```

- **Select from a Table**
    ```sql
    SELECT column1, column2 FROM table_name WHERE condition;
    ```

- **Join Two Tables**
    ```sql
    SELECT column_names FROM table1 JOIN table2 ON table1.column_name = table2.column_name;
    ```

Remember to replace `database_name`, `table_name`, `column1`, `column2`, `value1`, `value2`, `datatype`, and `condition` with your own values. For `datatype`, you can use types like INT, VARCHAR, DATE, etc. Always back up your data before performing operations that modify it!

For a more in-depth guide, refer to the [official MySQL documentation](https://dev.mysql.com/doc/).

Happy coding!
