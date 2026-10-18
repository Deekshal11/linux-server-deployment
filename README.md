# Linux Server Deployment on AWS EC2

## Project Overview
This project demonstrates how to launch and configure an Ubuntu Linux server on Amazon EC2 and deploy a static website using Nginx.

## Technologies Used
- Amazon Web Services (EC2)
- Ubuntu Linux
- Nginx
- SSH
- HTML and CSS

## Project Architecture
User's browser → EC2 public IP → AWS Security Group → Nginx → HTML website

## Implementation Steps
1. Launched an Ubuntu EC2 instance.
2. Configured an SSH key pair for secure server access.
3. Restricted SSH access through the EC2 security group.
4. Connected to the instance using SSH.
5. Updated Ubuntu packages.
6. Installed and enabled Nginx.
7. Created a custom HTML website.
8. Verified the website using `curl` and a web browser.

## Security Precautions
- Restricted SSH access to my IP address.
- Kept the SSH private key secure.
- Allowed HTTP traffic on port 80 for the website.
- Avoided uploading private keys or credentials to GitHub.

## Verification
The Nginx service was confirmed to be running, and the custom website was accessible through the EC2 public IP address.

## Screenshot
See `screenshots/custom-website.png` for the deployed website.

## Learning Outcomes
- Basic EC2 instance deployment
- Linux server administration
- SSH connectivity
- Nginx installation and service management
- Basic web hosting and firewall configuration

## Note
This is a learning project. The website is a static HTML page and does not display live EC2 monitoring metrics.
