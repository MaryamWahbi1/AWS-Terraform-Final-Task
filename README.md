# AWS Terraform Final Task

## Requierments :
We will create Terraform code for building the following environment:

[![](https://github.com/MaryamWahbi1/AWS-Terraform-Final-Task/blob/master/screenshots/environment.PNG?raw=true)](https://github.com/MaryamWahbi1/AWS-Terraform-Final-Task/blob/master/screenshots/environment.PNG?raw=true)


**It includes:**
- 2 Load Balancers - Internet Facing and Internal
- 4 Web Servers 
- 4 Application Servers 
- 1 RDS with two nodes (MySQL)
- 1 S3 Bucket

------------

## Implementation :
**1. Install Terraform on your computer**

[https://developer.hashicorp.com/terraform/downloads](https://developer.hashicorp.com/terraform/downloads)

**2. create an AWS access key**

- Create an IAM user, and then define that user's permissions as narrowly as possible.
- Create the access key under that IAM user.

**3. Initialising new Terraform project**

- Create a new directory for your Terraform project and change into it.
```
mkdir AWS-Terraform-Final-Task
```
- Create terraform file with the below command.
```
touch main.tf
```
**4. Now, to begin a new configuration, every Terraform project directory needs to be initialised, do this by running the command below.**

```
terraform init
```
**5. Deploying your configuration**

- First, verify your build plan with the following command.
```
terraform plan
```
- Next, deploy the configuration by executing the plan with the command below.
```
terraform apply
```
