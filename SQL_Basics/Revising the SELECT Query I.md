# 🧩 Revising the SELECT Query I

## 📌 Question

Query all columns for all American cities in the **CITY** table with populations larger than `100000`.

### 🗂️ Table Structure: CITY

| Column Name | Data Type |
| ----------- | --------- |
| ID          | Number    |
| NAME        | Varchar   |
| COUNTRYCODE | Varchar   |
| DISTRICT    | Varchar   |
| POPULATION  | Number    |

### 🎯 Requirements

* Select **all columns**
* Filter cities where:

  * `COUNTRYCODE = 'USA'`
  * `POPULATION > 100000`

---

## 💻 SQL Code

```sql
SELECT *
FROM CITY
WHERE COUNTRYCODE = 'USA'
  AND POPULATION > 100000;
```

---

## 🧠 Explanation

* `SELECT *`
  → Retrieves **all columns** from the table.

* `FROM CITY`
  → Specifies the table we are querying.

* `WHERE COUNTRYCODE = 'USA'`
  → Filters records to include only cities in the **United States**.

* `AND POPULATION > 100000`
  → Further filters cities with a population greater than **100,000**.

---

## ✅ Key Concepts Used

* Basic **SELECT statement**
* **Filtering using WHERE clause**
* Combining conditions using **AND**

---

## 🚀 Output

The query returns all details of cities in the USA with population greater than 100,000.

---
