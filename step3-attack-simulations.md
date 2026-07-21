# Step 3 - Attack Simulations

## Attack 1 - Privilege Escalation
- User bob (finance) attached AdministratorAccess to himself
- Bob gained full admin control beyond his role
- Risk: CRITICAL

## Attack 2 - Over-Permissive Policy
- User charlie (developer/intern) given AdministratorAccess
- Violates least privilege principle
- Risk: HIGH

## Attack 3 - Credential Exposure
- Hardcoded AWS credentials committed to GitHub
- Anyone with repo access can steal credentials
- Risk: CRITICAL
