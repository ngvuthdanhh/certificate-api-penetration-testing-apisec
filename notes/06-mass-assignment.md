# 06 – Mass Assignment

Occurs when API blindly maps input to backend objects.  

Example exploit:  
```json
{
  "username": "test",
  "role": "admin"
}
```
## Testing:

Add unexpected fields (isAdmin, balance)

Observe DB or API behavior changes
