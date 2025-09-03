# 08 – Injection in APIs

- **SQL Injection**: Classic query manipulation  
- **NoSQL Injection**: MongoDB operators  
- **Command Injection**: OS-level execution via APIs  

**Example payloads**:  
```sql
' OR '1'='1 --
```
```json
{ "$ne": null }
```
