#### creating a website on AWS. You will learn how to use the AWS Management Console to create a high-availability application on AWS. In Lab 1, we will use Amazon EC2 and Amazon RDS to create a single-instance WordPress website. In Lab 2, we will enhance the architecture even further by incorporating an Auto Scaling Group, an Application Load Balancer (Elastic Load Balancing), and a Content Distribution Network (AWS CloudFront), making the website more scalable, safe, and dependable.

![](https://general-webapp.workshop.aws/images/lab2-architecture.jpg)

LAB 1 - HOST A SINGLE-INSTANCE WEBSITE

##### In Lab 1, we will install the VPC using the CloudFormation template, then establish an Amazon RDS database and run an EC2 instance. Following that, we will configure the RDS-EC2 connection and deploy the WordPress website on the instance. Finally, we will begin running a basic WordPress website on an EC2 server and export the static assets to an S3 bucket.

![](https://general-webapp.workshop.aws/images/lab1-architecture.jpg)

STEP 1. CREATE A VPC CLOUDFORMATION STACK

STEP 2. CREATE A RDS MYSQL DATABASE

