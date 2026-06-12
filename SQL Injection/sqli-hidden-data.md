# SQL Injection – Hidden Data Retrieval

## 📌 Lab Name

SQL injection vulnerability in WHERE clause allowing retrieval of hidden data

---

## 🎯 Objective

Exploit SQL injection to retrieve hidden product/data entries.

---

## 🔍 Vulnerability Type

Union/WHERE clause based SQL Injection

---

## ⚔️ Payload Used

```sql
' OR 1=1--
```

---

## 🧪 Methodology

1. Intercepted product/category request
2. Injected payload into URL parameter
3. Modified query logic to return all records
4. Observed hidden data displayed

---

## ✅ Result

* All hidden items became visible
* Access control at query level was bypassed

---

## 🧠 Key Learning

* WHERE clause injections can expose full database content
* Even simple conditions like filters can be bypassed
* Input validation is critical in search/filter features

---
