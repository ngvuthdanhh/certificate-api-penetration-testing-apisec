# 📊 GraphQL Queries & Security Cheatsheet

## Introspection
```graphql
{
  __schema {
    types { name }
  }
}
```
## Sensitive Queries

Identify admin-only fields.

Test nested queries for DoS (deep recursion).

Example:

```graphql

{
  user(id:1) {
    id
    username
    posts {
      comments {
        content
      }
    }
  }
}
```
## Security Tips

Disable introspection in production.

Enforce query depth & complexity limits.

Implement proper authentication middleware.
