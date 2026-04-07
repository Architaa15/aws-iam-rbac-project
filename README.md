# aws-iam-rbac-project

# PROJECT TITLE

## Create an IAM User with EC2 Access Through Policy and S3 Access Through Group

# PROJECT DESCRIPTION

This project demonstrates the creation of an IAM user in AWS with controlled access permissions. The IAM user is provided EC2 access directly through an attached policy and S3 access through a group.


# AWS SERVICES USED

- AWS IAM
- Amazon EC2
- Amazon S3

# IMPLEMENTATION STEPS

1. Logged in to AWS Management Console
2. Opened IAM service
3. Created a group named S3Group
4. Attached AmazonS3FullAccess policy to the group
5. Created a new IAM user
6. Attached AmazonEC2FullAccess policy directly to the user
7. Added the IAM user to S3Group
8. Enabled AWS Management Console access
9. Signed in using IAM user credentials
10. Verified EC2 and S3 access permissions


# PROJECT OUTPUT

- IAM user was created successfully
- EC2 access was provided through direct policy attachment
- S3 access was provided through group membership
- Other AWS services remained restricted
- Role-Based Access Control was implemented successfully

---

# YOUTUBE DEMONSTRATION LINK

https://youtu.be/3jewkOllRu0
