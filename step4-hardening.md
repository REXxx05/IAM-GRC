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

## Fix 4 - Password Policy Applied
- Minimum password length: 14 characters
- Requires: symbols, numbers, uppercase, lowercase
- Password expires every 90 days
- Prevents reuse of last 12 passwords
- Principle applied: Access Control
