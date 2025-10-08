# 2. SQL Fundamentals
---

## 1️⃣ CREATE

### Used to create a new database or table.

#### 🏫 Create a new database
**CREATE DATABASE School;**

#### 🧾 Create a new table
```sql
CREATE TABLE Students (
  Student_ID INT PRIMARY KEY,
  Name VARCHAR(100),
  Age INT,
  Course VARCHAR(50)
);
```
---
## 2️⃣ INSERT

### Used to add new records (rows) into a table.

```sql
INSERT INTO Students (Student_ID, Name, Age, Course)
VALUES (101, 'Nithin', 20, 'ISE');
```
---
## 3️⃣ SELECT

### Used to retrieve data from a table.
```sql
SELECT * FROM Students;
```
---

## 4️⃣ UPDATE

### Used to modify existing records in a table.
```sql
UPDATE Students
SET Age = 21
WHERE Student_ID = 101;
```

---

## 5️⃣ DELETE

### Used to remove records from a table.
```sql
DELETE FROM Students

WHERE Student_ID = 101;
```
