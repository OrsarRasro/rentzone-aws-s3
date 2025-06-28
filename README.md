RentZone Car Rental System - AWS Deployment

Project Overview
This repository contains deployment scripts and documentation for setting up a RentZone car rental application on AWS infrastructure using S3 for file storage.

Architecture

EC2 instance running Amazon Linux 2
S3 bucket for application files storage
MySQL database (local or RDS)
Apache web server with PHP 7.4
Features

Complete car rental management system
Multiple vehicle types (cars, bikes, motorcycles)
Branch location management
User authentication and role-based access
Responsive design for all devices
Deployment Instructions
The repository includes detailed scripts for:

Setting up the EC2 environment
Installing and configuring Apache, PHP, and MySQL
Downloading application files from S3
Configuring the application
Setting up the database with migrations and seed data
Requirements

AWS account with EC2 and S3 access
S3 bucket containing the RentZone application files
MySQL database (can be installed locally or use RDS)
Security Considerations

Proper security group configuration
Database credential management
File permission settings
HTTPS configuration for production environments
Maintenance

Regular updates from S3 source
Database backups
Log monitoring and rotation
License
© 2024 Emmanuel Orsar. All Rights Reserved.
