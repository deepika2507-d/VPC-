Ex-4 Deployment and configuration of a Private Cloud in AWS
DATE:
Name: DEEPIKA V
Reg. No.: 212224240030
Aim:
To set up of a Private Cloud in AWS.

Setting up of a private cloud in AWS: Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC), involves creating a logically isolated virtual network that you can use to launch AWS resources. This provides you with full control over your virtual networking environment, including resource placement, connectivity, and security. Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console. Next, add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.

Procedure:
Plan Your VPC:
● Determine your needs:

Define your use case, including application requirements, security needs, and compliance standards. ● Plan IP address ranges:

Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts. ● Select Availability Zones:

Decide which Availability Zones (AZs) you'll use for your resources, considering redundancy and performance. ● Plan internet connectivity:

Determine if you need public internet access and how to configure it. ● Define security:

Plan your security groups, network ACLs, and access controls to ensure a secure environment. Create Your VPC: • Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.

• Choose "Create VPC": Initiate the VPC creation process.

• Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings.

• Create subnets: Define subnets within your VPC to isolate different parts of your network.

• Create route tables: Specify how traffic is routed within and outside the VPC.

• Create security groups: Define access control rules for your resources.

Deploying Resources: • Launch EC2 instances: Create and launch virtual machines within your VPC.

• Set up RDS instances: Deploy databases for your applications.

• Configure networking: Connect your resources to the appropriate subnets, security groups, and route tables.

• Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

Managing and Monitoring: • Use AWS CloudWatch: Monitor your VPC and resources for performance and health.

• Configure logging and auditing: Track access and activity within your VPC for security and compliance.

• Implement security best practices: Regularly review and update your security configuration.

• Scale and adjust as needed: Adjust your VPC infrastructure to meet changing demands.

Output:
Snapshot 1: Create VPC image

<img width="709" height="412" alt="image" src="https://github.com/user-attachments/assets/2d6f0c44-f0b1-44ea-8ab6-f4b798a6bbdf" />

Snapshot 2: Configuring Subnets

<img width="706" height="353" alt="image" src="https://github.com/user-attachments/assets/612e50d7-ef40-4ed4-861c-d50b49083cc4" />

Snapshot 3: Configure Subnets

<img width="711" height="393" alt="image" src="https://github.com/user-attachments/assets/21941d7b-bec7-49ca-873c-6f6b76a2f9a4" />

Snapshot 4: Setting Internet gateway

<img width="713" height="369" alt="image" src="https://github.com/user-attachments/assets/33ef58b8-e96b-4b48-a6c9-37eae112c89b" />

Snapshot 5: Creating Internet gateway

<img width="1221" height="716" alt="image" src="https://github.com/user-attachments/assets/c4c4df60-adc1-4d48-a522-68765a04ccc9" />

Snapshot 6: Setting Internet gateway

<img width="617" height="314" alt="image" src="https://github.com/user-attachments/assets/ba8777cb-ddd7-42ee-9c1b-bfb07ccb9796" />

Snapshot 7: Creating route table

<img width="994" height="536" alt="image" src="https://github.com/user-attachments/assets/6f94d090-089a-473f-8696-48d993dea85a" />

Snapshot 8: Configuring route table

<img width="993" height="602" alt="image" src="https://github.com/user-attachments/assets/c7d922f0-ce17-4e2f-b3f3-a2739b9db39e" />

Snapshot 9: Editing routes

<img width="1167" height="589" alt="image" src="https://github.com/user-attachments/assets/cb051b8b-84d6-4eed-aa82-ab6438238623" />

Snapshot 10: Creating route table

<img width="1171" height="591" alt="image" src="https://github.com/user-attachments/assets/8b21a7c9-0b26-4f1c-b2d0-2da62ac00f84" />

Result:

Thus, a private cloud on AWS involves using VPCs has been created for a dedicated, isolated network where we can manage our resources and control access according to our requirements.
