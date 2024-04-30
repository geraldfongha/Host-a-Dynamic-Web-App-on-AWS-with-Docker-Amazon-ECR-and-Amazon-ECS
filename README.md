![Alt text](/Host-a-Dynamic-Web-App-on-AWS-with-Docker-Amazon-ECR-and-Amazon-ECS.png)



# Host-a-Dynamic-Web-App-on-AWS-with-Docker-Amazon-ECR-and-Amazon-ECS
This DevOps project demonstrates the deployment and hosting of a dynamic website on AWS, utilizing various services and components to ensure high availability, scalability, security, and fault tolerance.

Technologies Used
Docker: Used to build the container image for the web application.
Git and GitHub: Used for version control and tracking changes to secure code and files.
AWS CLI: Used to interact with AWS services from the command line.
Flyway: Utilized for migrating SQL data into the Amazon RDS database.
Visual Studio Code (VS Code): Used for writing and editing scripts.
Amazon ECR (Elastic Container Registry): Used to store the Docker image.
Amazon ECS (Elastic Container Service): Utilized to containerize the web application on the AWS cloud.
Amazon RDS (Relational Database Service): Used for hosting the MySQL database.
ECS Fargate: Used to run the containerized application.
Application Load Balancer (ALB): Used to distribute web traffic to the ECS Fargate tasks.
Auto Scaling Group: Dynamically creates new ECS tasks based on demand.
Route 53: Used to register domain names and create record sets.
AWS S3: Utilized to store files containing environment variables for the container.
IAM Role: Grants permissions for ECS to execute tasks.
Bastion Host: Used to set up an SSH tunnel.
Security Group: Controls inbound and outbound traffic to resources.
Certificate Manager: Used to encrypt data in transit.
Deployment Steps
Setup Docker: Install and configure Docker on your local machine.
Git Repository Setup: Create a Git repository to track changes to the application code and Dockerfile. Use GitHub to manage the repository.
AWS CLI Setup: Install and configure AWS CLI to interact with AWS services.
Flyway Migration: Migrate SQL data into the Amazon RDS database using Flyway.
Development Environment: Use VS Code to write and edit scripts for the deployment process.
Amazon ECR Setup: Create an Elastic Container Registry to store the Docker image.
Amazon ECS Configuration: Configure Amazon ECS to containerize the web application.
VPC Setup: Set up a 3-tier VPC with public and private subnets across two availability zones.
Internet Gateway and NAT Gateways: Configure Internet Gateway to allow communication between VPC resources and the internet. Set up NAT Gateways to allow resources in private subnets access to the internet.
Amazon RDS Configuration: Set up Amazon RDS for hosting the MySQL database.
ECS Fargate Configuration: Configure ECS Fargate to run the containerized application.
ALB Configuration: Set up Application Load Balancer to distribute web traffic to ECS Fargate tasks.
Auto Scaling Group Configuration: Configure Auto Scaling Group to dynamically create new ECS tasks based on demand.
Route 53 Configuration: Use Route 53 to register domain names and create record sets.
AWS S3 Configuration: Set up AWS S3 to store files containing environment variables for the container.
IAM Role Configuration: Configure IAM Role to grant permissions for ECS to execute tasks.
Bastion Host Setup: Set up a Bastion Host to establish an SSH tunnel for secure communication.
Security Group Configuration: Configure Security Group to control inbound and outbound traffic to resources.
Certificate Manager Configuration: Use Certificate Manager to encrypt data in transit.
Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request in the GitHub repository.
