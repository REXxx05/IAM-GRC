# Step 1 - Environment Setup

## Tools Installed
- Docker
- LocalStack (running in Docker mode)
- AWS CLI v2
- awslocal alias configured

## LocalStack Start Command
LOCALSTACK_ACKNOWLEDGE_ACCOUNT_REQUIREMENT=1 localstack start -d

## AWS CLI Configuration
- Endpoint: http://localhost:4566
- Region: us-east-1
- Credentials: test/test (LocalStack fake credentials)
