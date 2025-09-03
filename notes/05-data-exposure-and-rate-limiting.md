# 05 – Excessive Data Exposure & Lack of Rate Limiting

**Excessive Data Exposure**  
- API leaks sensitive or internal fields in responses.  
- Example: returning password hashes in JSON.  

**Lack of Rate Limiting**  
- Allows brute force and automated abuse.  

**Checklist**  
- Inspect responses for unnecessary fields  
- Send high-volume requests to test rate limiting  
