# 💉 Lab – Injection Attacks in APIs

## Objective
Test for SQLi, NoSQLi, and command injection via API parameters.

## Steps
1. Identify input fields (`search`, `id`, `query`).  
2. Inject payloads:
   - `' OR 1=1--` (SQLi)  
   - `{ "$gt": "" }` (NoSQLi)  
   - `; ls -la` (Command injection)  
3. Observe server responses and log anomalies.  

## Key Takeaways
- Sanitize and validate all API inputs.  
- Use parameterized queries.  
