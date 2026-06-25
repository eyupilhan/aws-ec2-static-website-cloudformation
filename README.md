# AWS EC2 Static Website Deployment with CloudFormation

## Overview

This project demonstrates how to deploy a static website on an Amazon EC2 instance using **AWS CloudFormation** for infrastructure provisioning and **Apache HTTP Server** for web hosting.

The infrastructure is created automatically using an Infrastructure as Code (IaC) approach, while the application files are deployed through an EC2 User Data script during instance initialization.

---

## Architecture Components

* AWS CloudFormation
* Amazon EC2 (Amazon Linux 2)
* Apache HTTP Server
* EC2 User Data
* Security Groups
* Static HTML/CSS Website

---

## Repository Structure

```text
.
├── kittens-carousel-static-website.yml
├── static-web/
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

## Deployment Workflow

```text
CloudFormation Template
      │
      ▼
EC2 Instance Provisioning
      │
      ▼
User Data Script Execution
      │
      ▼
Apache Web Server Installation
      │
      ▼
Static Website Deployment
      │
      ▼
Public Website Access
```

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

## Project Preview

![Application Screenshot](project-101-snapshot.png)

---

## Learning Outcomes

Through this project, I practiced:

* Infrastructure as Code with AWS CloudFormation
* EC2 provisioning
* Security Group configuration
* Apache Web Server setup on Linux
* EC2 User Data automation
* Static website deployment on AWS

---

## Notes

This project is intended for learning and portfolio demonstration purposes.

It is not designed for production use without additional improvements such as HTTPS, domain configuration, automated security hardening, and monitoring.
