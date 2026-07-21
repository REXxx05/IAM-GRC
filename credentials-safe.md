# Secure Credential Management

## BAD Practice (what we demonstrated in Attack 3)
AWS_ACCESS_KEY_ID     = AKIAIOSFODNN7EXAMPLE  ← NEVER do this
AWS_SECRET_ACCESS_KEY = wJalrXUtnFEMI/K7MDENG ← NEVER do this

## GOOD Practice (use environment variables)
export AWS_ACCESS_KEY_ID=$(your-secret-manager)
export AWS_SECRET_ACCESS_KEY=$(your-secret-manager)

## Rules
- Never hardcode credentials in any file
- Never commit credentials to GitHub
- Always use environment variables or secret managers
- Add .env to .gitignore
