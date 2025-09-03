# 🛑 Lab – Broken Object Level Authorization (BOLA)

## Objective
Test for IDOR and privilege escalation via API endpoints.

## Steps
1. Enumerate object IDs (`/api/v1/user/123`).  
2. Replace IDs with unauthorized values.  
3. Check if sensitive data can be accessed.  
4. Attempt role-based privilege escalation.  

## Key Takeaways
- Enforce authorization checks at every endpoint.  
- Don’t rely only on hidden parameters.  
