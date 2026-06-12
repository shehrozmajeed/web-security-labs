# SQL Injection – XML Filter Bypass

## 📌 Lab Name

SQL injection with filter bypass via XML encoding

---

## 🎯 Objective

Bypass input filtering using XML encoding to exploit SQL injection.

---

## 🔍 Vulnerability Type

Filtered SQL Injection (encoded payload bypass)

---

## ⚔️ Payload Used

```sql
' OR 1=1--
```

Encoded as XML entity:

```
&#39; OR 1=1--
```

---

## 🧪 Methodology

1. Identified input filtering on application
2. Normal SQL payload blocked
3. Converted payload into XML encoding
4. Sent request via Burp Suite
5. Filter bypassed successfully

---

## ✅ Result

* SQL injection executed despite filtering
* Hidden data exposed / lab solved

---

## 🧠 Key Learning

* Input filters are not real security
* Encoding can bypass weak protections
* Always sanitize at backend, not just frontend

---
