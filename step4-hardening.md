# Step 4 - Hardening

## Fix 1 - Removed Bob's Privilege Escalation
- Detached AdministratorAccess from bob
- Bob restored to finance group permissions only
- Principle applied: Least Privilege

## Fix 2 - Removed Charlie's Over-Permission
- Detached AdministratorAccess from charlie
- Charlie restricted to AmazonS3ReadOnlyAccess only
- Principle applied: Need-to-Know

## Fix 3 - Removed Hardcoded Credentials
- Deleted credentials-exposed.md
- Created credentials-safe.md with best practices
- Added .gitignore to prevent future exposure
- Principle applied: Secure Credential Management

## Fix 4 - Password Policy (coming next)
