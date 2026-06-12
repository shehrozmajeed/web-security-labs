# SQL Injection – Login Bypass

## 📌 Lab Name

SQL injection vulnerability allowing login bypass

---

## 🎯 Objective

Bypass authentication using SQL injection to gain access without valid credentials.

---

## 🔍 Vulnerability Type

Authentication-based SQL Injection

---

## ⚔️ Payload Used

```sql
' OR 1=1--
```

---

## 🧪 Methodology

1. Opened login page
2. Entered payload in username field
3. Kept password empty
4. Server evaluated query as always true

---

## ✅ Result

* Authentication bypassed successfully
* Logged into application without valid credentials

---

## 🧠 Key Learning

* SQL queries can be manipulated if input is not sanitized
* Always use parameterized queries
* Authentication logic must never rely on raw input concatenation

---
