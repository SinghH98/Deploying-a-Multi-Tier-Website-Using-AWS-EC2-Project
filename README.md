# Deploying a Multi Tier Website Using AWS EC2

Project Description : Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity in the Amazon Web Services (AWS) cloud. Using Amazon EC2 eliminates our need to invest in hardware up front so we can develop and deploy applications faster. We can use Amazon EC2 to launch as many or as few virtual servers as we need, configure security and networking, and manage storage. Amazon EC2 enables us to scale up or down to handle changes in requirements or spikes in popularity, reducing our need to forecast traffic.

Problem Statement:
Company ABC wants to move their product to AWS. They have the following things set up right now:
1. MySQL DB
2. Website (PHP)
The company wants high availability on this product, therefore wants Auto Scaling to be enabled on this website.

Steps To Solve:
- Launch an EC2 Instance
- Enable Auto Scaling on these instances (minimum 2)
- Create an RDS Instance
- Create Database & Table in RDS instance:
- Database name: intel
- Table name: data
- Database password: intel123
- Change hostname in website
- Allow traffic from EC2 to RDS instance
- Allow all-traffic to EC2 instance
