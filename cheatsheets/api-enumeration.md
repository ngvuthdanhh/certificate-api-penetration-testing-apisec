# 📑 API Enumeration Cheatsheet

## REST API Enumeration
- Look for common documentation endpoints:
  - `/swagger.json`
  - `/openapi.json`
  - `/api-docs`
- Use fuzzing to find hidden endpoints:
  ```bash
  ffuf -w wordlist.txt -u https://target.com/FUZZ
  ```
  ## GraphQL Enumeration

Run introspection query:

```graphql
{
  __schema {
    queryType { name }
    mutationType { name }
    types { name }
  }
}
```

## Useful Tools

Postman / Insomnia → Testing endpoints

Burp Suite / OWASP ZAP → Intercept & modify traffic

graphql-playground → Explore schemas
