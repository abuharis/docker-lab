# docker-lab
Deploys docker engine, connects to ECR and creates users with docker conf.

# Prerequisites
## On AWS
- IAM User with AmazonEC2ContainerRegistryFullAccess & AmazonEC2FullAccess Permissions
- EC2 with Ubuntu opened with 22 and 500 ports in Security Group. Add enough Volume
- Create an IAM Role with the permission AmazonEC2ContainerRegistryReadOnly. This is for the machine to access ECR to run containers
- ECR repository for docker images
- Install AWS CLI on Host Machine. https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html#getting-started-install-instructions

## On Github Secrets
```bash
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY
AWS_REGION
EC2_HOST
EC2_USER
EC2_SSH_KEY
ECR_REPO
```

# How to Run
1. Navigate to the Actions in Github.
2. CHoose the workflow you wanted to run
3. Enter the inputs if required
4. Wait for th retunr status.


