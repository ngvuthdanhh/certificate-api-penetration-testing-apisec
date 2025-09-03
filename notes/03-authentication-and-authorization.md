# 03 – Authentication & Authorization in APIs

- **Authentication**: Who you are (API keys, OAuth, JWT).  
- **Authorization**: What you can do after authentication.  

**Common flaws**:  
- Long-lived or non-expiring tokens  
- Weak JWT algorithms (`none`, weak HS256 secrets)  
- Hardcoded API keys in apps  

**Testing checklist**:  
- Test brute force and credential stuffing  
- Analyze JWT claims & signatures  
- Attempt privilege escalation via IDOR/BOLA  
