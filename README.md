LAMP Stack AWS Deployment Template

This template provided a LAMP Stack (Linux, Apache, MySQL, PHP) setup on AWS for deploying a PHP-based website with high availability and scalability.
Architecture Overview
EC2 Instance (Ubuntu Linux): Hosts the PHP website with Apache web server.
MySQL (Amazon RDS): A managed relational database for storing application data.
Elastic Load Balancer (ELB): Distributes incoming traffic for high availability.

Security Groups:
EC2 Security Group: Allows internet-facing traffic.
RDS Security Group: Restricts access to the database.
ELB Security Group: Manages incoming load-balanced traffic, HTTP, and SSH from anywhere.

This LAMP stack template provides a production-ready environment for hosting PHP applications on AWS, ensuring scalability, security, and high availability.
