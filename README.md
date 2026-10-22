# AWS WordPress Deployment and Monitoring Using CloudFormation

## Project Overview

This project demonstrates how AWS services can be used to deploy and monitor WordPress environments for an organisation.

The project was completed as part of my AWS Solutions Architect – Associate level practical training.

The organisation publishes blogs and provides documentation services. The requirement was to create a live WordPress environment for publishing content and a separate development and testing environment so that changes could be tested without affecting the live website.

The development and testing environment was designed to be available only during business hours (9 AM–6 PM).

## Objectives

- Set up a live WordPress instance for publishing blogs
- Create a separate WordPress environment for development and testing
- Prevent development work from affecting the live environment
- Use AWS CloudFormation to provision AWS resources
- Use Amazon EC2 to host the WordPress instances
- Monitor the deployed infrastructure
- Design the development environment around business-hour availability

## Technologies and Tools Used

- Amazon Web Services (AWS)
- AWS Management Console
- AWS CloudFormation
- Amazon EC2
- Amazon CloudWatch
- WordPress
- Infrastructure as Code (IaC)

## Key Features and Functionalities

### Production WordPress Environment

A live WordPress environment was configured to support the organisation's blog publishing requirements.

### Development and Testing Environment

A separate WordPress environment was used for development and testing.

This separation helps ensure that testing and development activities do not directly affect the live WordPress environment.

### Infrastructure Provisioning with CloudFormation

AWS CloudFormation was used to provision and manage the required AWS infrastructure using an Infrastructure as Code approach.

### EC2 Hosting

Amazon EC2 instances were used to provide the compute resources required for the WordPress environments.

### Monitoring

The deployed resources were monitored to observe infrastructure health and performance.

### Business-Hour Development Environment

The development and testing environment was designed around the requirement that it only needed to be available during business hours from 9 AM to 6 PM.

This approach can help reduce unnecessary resource usage outside the required operating period.

## My Role and Contributions

I completed the AWS configuration and testing activities required for this project.

My responsibilities included:

- Working with the AWS Management Console
- Configuring the WordPress environments
- Using AWS CloudFormation for infrastructure provisioning
- Working with Amazon EC2 instances
- Separating the live and development/test environments
- Configuring monitoring for the AWS resources
- Testing the deployed environments
- Documenting the implementation

## Implementation Steps

1. Signed in to the AWS Management Console.
2. Reviewed the infrastructure requirements for the WordPress environments.
3. Used AWS CloudFormation to provision the required resources.
4. Deployed the live WordPress environment.
5. Created a separate development and testing WordPress environment.
6. Verified that development/testing activities were separated from the live environment.
7. Configured the development environment according to the required business-hour availability.
8. Configured monitoring for the deployed resources.
9. Verified the status and performance of the infrastructure.
10. Tested the WordPress environments.

## How to Reproduce the Project

To reproduce a similar environment:

1. Sign in to the AWS Management Console.
2. Prepare or select an appropriate CloudFormation template.
3. Create a CloudFormation stack.
4. Configure the required parameters.
5. Deploy the required EC2 resources.
6. Configure the WordPress environment.
7. Create separate production and development/testing environments.
8. Configure monitoring for the deployed resources.
9. Configure the required operating schedule for non-production resources.
10. Test both environments and verify that they operate independently.

## Project Outcome

The project demonstrated how AWS can be used to provision and manage separate WordPress environments for production and development/testing purposes.

It also provided practical experience with AWS CloudFormation, Amazon EC2, infrastructure monitoring, environment separation, and cloud resource management.

## Key Learnings

Through this project, I gained practical experience with:

- AWS CloudFormation
- Amazon EC2
- Amazon CloudWatch
- WordPress deployment
- Infrastructure as Code
- AWS resource monitoring
- Production and development environment separation
- Cloud infrastructure management
- AWS Management Console
- Cloud cost-awareness through controlled resource availability
