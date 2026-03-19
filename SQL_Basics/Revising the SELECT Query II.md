# 📘 Revising the SELECT Query II

🔗 **Problem Link**  
https://www.hackerrank.com/challenges/revising-the-select-query-2/problem

---

## 📝 Question

Query the **NAME** field for all American cities in the **CITY** table with populations larger than **120000**.

- The `CountryCode` for USA is **'USA'**

---

## 📊 Table Structure: CITY

| Column        | Type     |
|--------------|---------|
| ID           | INT     |
| NAME         | VARCHAR |
| COUNTRYCODE  | VARCHAR |
| DISTRICT     | VARCHAR |
| POPULATION   | INT     |

---

## 💻 SQL Code

```sql
SELECT NAME
FROM CITY
WHERE COUNTRYCODE = 'USA'
  AND POPULATION > 120000;
