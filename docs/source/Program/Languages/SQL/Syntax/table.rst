============================================
Table
============================================

--------------------------------------------
Data Definition Language (DDL)
--------------------------------------------
* CREATE
* ALTER
* DROP

Create Table
--------------------------------------------
 ::

    CREATE TABLE 'DataBase_Name'.'Table_Name' (
        'Column_Name' DataType
    )

Add Column in Table
--------------------------------------------
 ::

    ALTER TABLE 'DataBase_Name'.'Table_Name' 
    ADD COLUMN 'Column_Name' DataType



Drop Column in Table
---------------------------------------------
 ::

    ALTER TABLE 'DataBase_Name'.'Table_Name'
    DROP COLUMN 'Column_Name'

---------------------------------------------
Data Manipulation Language (DML)
---------------------------------------------

Insert new data into Table
---------------------------------------------
 ::

    INSERT INTO 'DataBase_Name'.'Table_Name'
    VALUES (value1, value2, value3, ...);

