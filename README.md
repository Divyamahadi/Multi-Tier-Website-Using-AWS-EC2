# Multi-Tier-Website-Using-AWS-EC2
Deploying a Multi-Tier Website Using AWS EC2

Project Statement:
Company ABC wants to move their product to AWS. They have the following
things set up right now:
1. MySQL DB
2. Website (PHP)
The company wants high availability on this product, therefore wants Auto
Scaling to be enabled on this website.
Steps To Solve:
1. Launch an EC2 Instance
2. Enable Auto Scaling on these instances (minimum 2)
3. Create an RDS Instance
4. Create Database & Table in RDS instance:
a. Database name: intel
b. Table name: data
c. Database password: intel123
5. Change hostname in website
6. Allow traffic from EC2 to RDS instance
7. Allow all-traffic to EC2 instance
   
<img width="254" alt="Screenshot 2023-10-21 224551" src="https://github.com/user-attachments/assets/7a7110a8-6bfe-4564-8063-6f6c9aa7f88c">

![VPC route map](https://github.com/user-attachments/assets/6b9fc185-9621-45d0-bc56-1889b4e2649a)
![VPC route map](https://github.com/user-attachments/assets/4580af31-b868-4a56-b1b3-af119f1fccc2)
![subnets](https://github.com/user-attachments/assets/64099ca9-53d9-4c14-9d6d-37a5ac32380d)
![Security groups](https://github.com/user-attachments/assets/a99a5f03-6221-404f-8dbd-46da47623274)
![Load balancer](https://github.com/user-attachments/assets/356aaa1b-9443-41f3-9f32-15aff012705f)
![Auto scaling group](https://github.com/user-attachments/assets/6285a6a6-9407-41d9-a151-df46cba566d0)
![instances created](https://github.com/user-attachments/assets/f35e5939-101b-4ad3-b0c8-a6f8b56f7eec)
![RDS created](https://github.com/user-attachments/assets/ca486678-602a-4132-836c-19e845632370)
![Subnet group](https://github.com/user-attachments/assets/bf44a7ba-4f43-4295-9c72-2ec556482c9b)
![Target group](https://github.com/user-attachments/assets/3a937b0b-9c93-4240-b3d8-41a5a77a2a16)
![traffic redirected](https://github.com/user-attachments/assets/01dee225-dcc5-4440-b55e-36b2fb337e95)
![RDS endpoint](https://github.com/user-attachments/assets/c30e49c4-49f7-4c40-b60f-aec3c37426e0)
![Git index](https://github.com/user-attachments/assets/f14e5105-934c-4041-93f9-8a4794d6c131)
![RDS security group](https://github.com/user-attachments/assets/c3b9ff4e-b9a0-44cd-afe1-ff60195f52a8)
![connecting](https://github.com/user-attachments/assets/31c3e293-5d66-44d9-a822-a70d0fca259a)
![record created](https://github.com/user-attachments/assets/0583d41f-7c89-44d5-a007-a25bb2a3530b)
![tables displyed](https://github.com/user-attachments/assets/ce8b1e9e-6727-478c-a891-260c04ab5b49)
![new data added](https://github.com/user-attachments/assets/200e138f-e3fc-4f01-b98f-5eb7a41a0d78)
![Capture](https://github.com/user-attachments/assets/5178fd6a-95d8-41df-b1d9-4580cda88fc0)
![new data added2](https://github.com/user-attachments/assets/3a0cc7aa-bba1-4e4a-8dbb-c43172ffaf21)
