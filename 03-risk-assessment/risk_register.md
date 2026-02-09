# CloudGuard - Risk Register

|**RISK ID**|**ASSET**|**ISSUE**|**LIKELIHOOD**|**IMPACT**|**RISK LEVEL**|**RECOMMENDATION**|
|-|-|-|-|-|-|-|
|CR-001|HR-Records (S3)|Public bucket with high sensitivity data|High|High|Critical|Disable public access, enforce IAM restrictions|
|CR-002|Data-Analyst Role|No MFA enabled|Medium|High|High|Enforce MFA for all roles|
|CR-003|Intern Role|Access to production server|Medium|Medium|Medium|Restrict intern access to test environments|
|CR-004|Finance-Admin Role|Broad access to backup systems|Low|High|Medium|Apply least privilege|
|CR-005|Multi-Region Assets|No geo-access restrictions|Low|Medium|Low|Apply geo-restrictions.|



