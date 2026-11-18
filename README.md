<img width="960" height="540" alt="Screenshot 2026-10-29 155252" src="https://github.com/user-attachments/assets/98abdee3-7b63-4e93-b24b-9b6f8da2a157" /><img width="960" height="540" alt="Screenshot 2026-10-29 153741" src="https://github.com/user-attachments/assets/a7651d73-8867-4eba-adba-18c29793208f" /># Deployment-and-configuration-of-a-Private-Cloud-in-AWS
Ex.4 Deployment and configuration of a Private Cloud  in AWS

Aim:
To set up of a Private Cloud  in AWS.
         Setting up of a private cloud in AWS:
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
Procedure:
1. Plan Your VPC:
● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.
2. Create Your VPC:
•	Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
•	 Choose "Create VPC": Initiate the VPC creation process.
•	Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
•	other necessary settings.
•	Create subnets: Define subnets within your VPC to isolate different parts of your
•	network.
•	Create route tables: Specify how traffic is routed within and outside the VPC.
•	 Create security groups: Define access control rules for your resources.
3. Deploying Resources:
•	Launch EC2 instances: Create and launch virtual machines within your VPC.
•	 Set up RDS instances: Deploy databases for your applications.
•	Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.
•	Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.
4.Managing and Monitoring:
•	Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.
•	Configure logging and auditing: Track access and activity within your VPC for
security and compliance.
•	Implement security best practices: Regularly review and update your security
configuration.
•	Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

Snap Shot:

 

Snapshot 1: Create VPC
<img width="959" height="539" alt="Screenshot 2026-10-29 152553" src="https://github.com/user-attachments/assets/6e248356-5b43-4cad-872d-5d6b4750d28c" />

 
Snapshot 2: Configuring Subnets
 <img width="960" height="540" alt="Screenshot 2026-10-29 153358" src="https://github.com/user-attachments/assets/ad455f2f-eecf-47f6-901a-eefff0711796" />


Snapshot 3: Configure Subnets
 <img width="960" height="540" alt="Screenshot 2026-10-29 153426" src="https://github.com/user-attachments/assets/7a65ade5-2c6d-498b-b265-24a5bcc00f86" />


Snapshot 4: Setting Internet gateway
<img width="960" height="540" alt="Screenshot 2026-10-29 153427" src="https://github.com/user-attachments/assets/bc837c9f-960f-47c5-836e-7682ad611c1f" />

 
Snapshot 5: Setting Internet gateway
<img width="960" height="540" alt="Screenshot 2026-10-29 153707" src="https://github.com/user-attachments/assets/b7a919b1-95f7-448a-9adb-1f5abaee97f8" />



 

Snapshot 6: Setting Internet gateway
<img width="960" height="540" alt="Screenshot 2026-10-29 153741" src="https://github.com/user-attachments/assets/d1d08c78-5d6b-48a7-8182-68af05c578e4" />


 
Snapshot 7: Creating route table
<img width="960" height="540" alt="Screenshot 2026-10-29 154349" src="https://github.com/user-attachments/assets/71d3fdc7-2738-43a3-920a-eccd0484ace8" />

 

Snapshot 8: Configuring route table

<img width="960" height="540" alt="Screenshot 2026-10-29 154753" src="https://github.com/user-attachments/assets/8891dadf-224b-442e-a880-ec6d21abc0f9" />
<img width="960" height="540" alt="Screenshot 2026-10-29 154601" src="https://github.com/user-attachments/assets/84275bd8-1e06-4682-b9d9-911298fb2e3f" />

 
Snapshot 9: Editing routes
<img width="960" height="540" alt="Screenshot 2026-10-29 155252" src="https://github.com/user-attachments/assets/7d27ea7e-0238-4955-9993-239106754d2e" />

 
Snapshot 10: Creating route table
<img width="960" height="540" alt="Screenshot 2026-11-02 123238" src="https://github.com/user-attachments/assets/b73eed39-ce98-4a66-8ed4-25cf66d4e8a4" />
<img width="960" height="540" alt="Screenshot 2026-10-29 160320" src="https://github.com/user-attachments/assets/f304db87-a1c9-4410-848b-27db4b7d465e" />




















Result:
Thus, a  private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.
 
