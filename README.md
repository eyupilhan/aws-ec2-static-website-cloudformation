# AWS EC2 Static Website Deployment with CloudFormation

## Overview

This project demonstrates how to deploy a static website on an Amazon EC2 instance using **AWS CloudFormation** for infrastructure provisioning and **Apache HTTP Server** for web hosting.

The infrastructure is created automatically using an Infrastructure as Code (IaC) approach, while the application files are deployed through an EC2 User Data script during instance initialization.

---

## Architecture Components

- AWS CloudFormation
- Amazon EC2 (Amazon Linux 2)
- Apache HTTP Server
- EC2 User Data
- Security Groups
- Static HTML Website

---

## Project Structure

```text
.
├── kittens-carousel-static-website.yml
├── static-web
│   ├── index.html
│   ├── cat0.jpg
│   ├── cat1.jpg
│   ├── cat2.jpg
│   └── cat3.png
├── project-101-snapshot.png
├── Pro_Project_101.png
└── README.md
```

---

## Features

* Infrastructure provisioning using AWS CloudFormation
* Automatic EC2 instance creation
* Apache Web Server installation via User Data
* Static website deployment during instance initialization
* Public HTTP access through Security Groups
* Infrastructure as Code (IaC) approach

---

## Technologies Used

* AWS CloudFormation
* Amazon EC2
* Amazon Linux 2
* Apache HTTP Server
* Bash
* HTML
* Git & GitHub

---

## Deployment

1. Deploy the CloudFormation template.
2. AWS provisions the required infrastructure automatically.
3. Apache HTTP Server is installed using the EC2 User Data script.
4. Static website files are deployed during instance initialization.
5. Access the application using the EC2 Public DNS or Public IP address.

---

## Project Preview

![Application Screenshot](project-101-snapshot.png)

## Architecture Diagram

![Architecture](Pro_Project_101.png)

---

## Repository Highlights

- Infrastructure as Code with AWS CloudFormation
- Automated EC2 provisioning
- Apache Web Server configuration via User Data
- Static website deployment
- Git version control

---

## Learning Outcomes

This project demonstrates practical experience with:

* Infrastructure as Code (IaC)
* AWS CloudFormation
* EC2 provisioning
* Apache Web Server configuration
* Linux User Data automation
* Static website deployment
* Git version control

---

## Author

Eyüp İlhan
