# Ecommerce Web App - My Azure Version

This repository contains a simple e-commerce web application designed to showcase the advantages of Load Balancer (LB) and Auto Scaling in creating a highly available and secured network environment.

## Features

- The web application demonstrates the key features of an e-commerce website, such as product browsing, cart management, and checkout.
- It is designed to handle a large number of concurrent users and ensure high availability.
- The deployment architecture includes the use of Azure Load Balancer and Auto Scaling to achieve scalability and fault tolerance.

## Prerequisites

Before deploying and running the e-commerce web app, ensure that you have the following prerequisites:

1. Azure Account: Access an Azure account to deploy the application.
2. Create a Subscription, Resource Group, Virtual Network (VNet)
3. Azure CLI: The Azure Command Line Interface (CLI) is installed and configured with the appropriate credentials.
4. VM Instances: Existing VM instances with the necessary setup and configurations for the web application.
5. Load Balancer: An Load Balancer configured to distribute traffic among the VM instances.
6. Auto Scaling Group: An Auto Scaling group configured to adjust the number of VM instances based on demand automatically.

## Deployment Steps

Follow these steps to deploy the e-commerce web app:

1. Clone the Repository: `https://github.com/Michaelgwei86/wanda-ecommerce-web-app.git`
2. Configure VM Instances: Set up your VM instances with the necessary software and configurations for the web application.
3. Configure Load Balancer: Create and configure a Public Load Balancer to distribute traffic among the VM instances.
4. Configure Auto Scaling: Set up an Auto Scaling group to automatically adjust the number of EC2 instances based on demand.
5. Deploy the Application: Copy the web application files to the appropriate location on the EC2 instances.
6. Test the Application: Access the load balancer's DNS or IP to test the application and verify that the traffic is distributed among the instances.
7. Monitor and Scale: Monitor the application's performance and scale the instances up or down as needed based on demand.

## Resources

Here are some helpful resources for understanding and implementing Elastic Load Balancer and Auto Scaling:

- [Elastic Load Balancing Documentation](https://docs.aws.amazon.com/elasticloadbalancing/)
- [Auto Scaling Documentation](https://docs.aws.amazon.com/autoscaling/)

Note: Contact me to set up documentation of VNet, Load balancer, and Autoscaling!

Happy learning 😊
