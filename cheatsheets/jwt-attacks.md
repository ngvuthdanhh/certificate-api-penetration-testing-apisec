# 🔑 JWT Attacks Cheatsheet

## Common Vulnerabilities
- **None algorithm**:
  ```json
  { "alg": "none" }
  ```
Weak secret keys (brute force HMAC).

Key confusion attack → Using public key as HMAC secret.

## Exploitation

Crack weak secrets:

```bash
jwt-cracker -t jwt.txt -d wordlist.txt
```

Modify algorithm:

```bash
{ "alg": "HS256" }
```

## Defense

Always use strong algorithms (RS256 or ES256).

Rotate keys frequently.

Implement short expiration times.
