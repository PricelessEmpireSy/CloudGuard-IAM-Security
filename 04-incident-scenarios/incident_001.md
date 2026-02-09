# Incident 001 – Public S3 Data Exposure

## Summary

A misconfigured S3 bucket (HR-Records) was publicly accessible, exposing sensitive employee data.

## Detection

Security scan flagged public access on a high-sensitivity storage bucket.

## Impact

- Exposure of personal and payroll records  
- Regulatory and reputational risk  

## Root Cause

Public access enabled and lack of access reviews.

## Containment

- Disabled public access immediately  
- Revoked unnecessary permissions  

## Lessons Learned

- Enforce continuous access monitoring  
- Require MFA and least privilege
