# 1. Basics of Databases
---

## What is a Database?
A **database** is an organized collection of data that can be easily accessed, managed, and updated.  
It stores information in a structured way — usually in **tables** made up of **rows (records)** and **columns (fields)**.

### Example:
A *Student Database* might have a table like:

| Student_ID | Name     | Age | Course |
|-------------|----------|-----|--------|
| 101         | Nithin   | 20  | ISE    |
| 102         | Praphul  | 21  | CSE    |

---

## What is SQL?
**SQL** stands for **Structured Query Language**.  
It is a **programming language** used to **interact with databases** — to store, retrieve, update, and delete data.

---

## Functions of SQL
1. **Create** databases and tables  
   ```sql
   CREATE DATABASE School;

2. **Insert data**
   ```sql
   INSERT INTO Students VALUES (101, 'Nithin', 20, 'ISE');
   ```

3. **Retrieve data**
   ```sql
   SELECT * FROM Students;
   ```

4. **Update data**
   ```sql
   UPDATE Students SET Age = 21 WHERE Student_ID = 101;
   ```

5. **Delete data**
   ```sql
   DELETE FROM Students WHERE Student_ID = 101;
   ```
## In Short

**Database**	  A place where data is stored</br>
**SQL**     The language used to manage that data
