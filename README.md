# node-app

To start Node Application:
**"npm install"
"npm start"**

**Your Task**
Launch two EC2 instances (Ubuntu 22.04) and install Node.js and Git on both instances.
SSH into each instance and clone the Node.js application repository from your GitHub (or create one).
Navigate to the application directory and run **npm install** to install the dependencies.
Start the application using **npm start**.


**Set Up the Load Balancer**
Create an Elastic Load Balancer (ELB) in the AWS Management Console.
Register both EC2 instances with the ELB.
Ensure the ELB health checks are configured correctly to check the health of your Node.js application.

**Configure Auto Scaling**
Create a launch configuration or a launch template for the EC2 instances.
Define the Auto Scaling group and attach the ELB to it.
Set the desired, minimum, and maximum number of instances for the Auto Scaling group.
Configure the scaling policies based on CPU utilization or other metrics.

**Test the Setup**
Access the application through the Load Balancer's DNS name to ensure it is working.
