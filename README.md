# ec2-nginx-web-server

This project is to provision and configure a single EC2 instance to run a basic web server.

## Description
A simple infrastructure-as-code project that automates the deployment of an NGINX web server on an Amazon EC2 instance.

## Features
* Automated EC2 instance provisioning
* NGINX web server installation and configuration
* Security group configuration for web traffic
* Basic web server setup with minimal configuration

## Prerequisites
* AWS CLI configured with appropriate credentials
* Valid AWS account with necessary permissions
* Basic understanding of EC2 and NGINX

## Installation
1. Clone this repository
2. Configure AWS credentials
3. Run the provisioning scripts
4. Access the web server using the EC2 public IP


## Security Considerations
* Only necessary ports are opened (80/443)
* Security group rules follow least privilege principle
* Regular security updates enabled
