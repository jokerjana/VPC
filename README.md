## Ex.4 Deployment and configuration of a Private Cloud  in AWS
```
NAME: JANARTHANAN B
REG NO: 212223100014
```
## Aim:
To set up of a Private Cloud  in AWS.

## Setting up of a private cloud in AWS:

Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.

## Procedure:
## 1. Plan Your VPC:
## ● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
## ● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
## ● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
## ● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
## ● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.

## 3. Create Your VPC:
Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
 Choose "Create VPC": Initiate the VPC creation process.
Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
other necessary settings.
Create subnets: Define subnets within your VPC to isolate different parts of your
network.
Create route tables: Specify how traffic is routed within and outside the VPC.
 Create security groups: Define access control rules for your resources.

## 4. Deploying Resources:
Launch EC2 instances: Create and launch virtual machines within your VPC.
 Set up RDS instances: Deploy databases for your applications.
Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.
Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

## 5.Managing and Monitoring:
Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.
Configure logging and auditing: Track access and activity within your VPC for
security and compliance.
Implement security best practices: Regularly review and update your security
configuration.
Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

##  Output:

<img width="826" height="608" alt="image" src="https://github.com/user-attachments/assets/7421e258-6b27-496a-83fd-2747dafa87dd" />


<img width="831" height="611" alt="image" src="https://github.com/user-attachments/assets/f81207e4-daf3-4e6e-8770-debf237e54ec" />

<img width="837" height="633" alt="image" src="https://github.com/user-attachments/assets/b1f28823-2f10-48a5-ab42-44d6f85c29a1" />

<img width="833" height="608" alt="image" src="https://github.com/user-attachments/assets/915ed6e3-1fbf-4c4f-8634-e89b0d387447" />

<img width="833" height="608" alt="image" src="https://github.com/user-attachments/assets/810fbae8-6365-4f04-9517-845a1b3c009f" />

<img width="831" height="641" alt="image" src="https://github.com/user-attachments/assets/e775eb20-2863-4397-abd9-3aba13513083" />

<img width="842" height="647" alt="image" src="https://github.com/user-attachments/assets/5ce173e3-5486-4553-afe0-1c25a2ab2383" />


## Result:

Thus, a private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.

