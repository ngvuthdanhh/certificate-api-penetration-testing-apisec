# 07 – Security Misconfiguration

Common cases:  
- Missing security headers (CORS, CSP)  
- Verbose error messages with stack traces  
- Debug endpoints exposed in production  

**Testing**:  
- Check HTTP response headers  
- Fuzz for hidden routes (`/debug`, `/swagger`)  
