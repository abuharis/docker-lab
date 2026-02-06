# docker-lab
Deploys docker engine, connects to ECR and creates users with docker conf.

# Prerequisites
## On AWS
- IAM User with AmazonEC2ContainerRegistryFullAccess & AmazonEC2FullAccess Permissions
- EC2 with Ubuntu opened with 22 and 500 ports in Security Group. Add enough Volume
- ECR repository for docker images

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


