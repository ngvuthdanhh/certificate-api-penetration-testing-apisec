# 04 – BOLA & Broken Authentication

**BOLA (IDOR)**:  
- Unauthorized access by modifying object IDs in requests  
- Example: `/api/users/1234` → `/api/users/1235`  

**Broken Authentication**:  
- Weak login mechanisms  
- Insecure session handling  

**Testing**:  
- Fuzz object IDs  
- Replay expired tokens  
- Test MFA enforcement  
