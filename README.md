# Seifeddin Cloud Project

This project is my first hands-on implementation of cloud infrastructure and deployment using AWS.

It includes setting up an EC2 instance, configuring a production-ready web server with Nginx, and implementing a deployment workflow using GitHub and Bash scripting. The goal of this project is to showcase practical experience in cloud infrastructure, deployment automation, and fundamental DevOps practices. 

---

## Live Demo

Hosted on an AWS EC2 instance using Nginx

Live: http://13.60.35.204

Public access via browser

---

## Tech Stack

* **AWS EC2** – Cloud server hosting
* **Nginx** – Web server
* **Linux (Ubuntu)** – Server environment
* **SSH** – Remote server access
* **Git & GitHub** – Version control
* **Bash Script** – Deployment automation

---

## What I Built

* Launched and configured an AWS EC2 instance
* Established secure remote access using SSH
* Installed and configured Nginx as a web server
* Deployed a static website to a live production environment
* Set up a GitHub for version control and code management
* Developed a custom Bash deployment script to automate updates to the live site

---

## Deployment Workflow

1. Update code in GitHub
2. Run deployment script on server:

```bash
sudo /var/www/deploy.sh
```

3. Website updates instantly

---

## Project Structure

```bash
/var/www/
│
├── cloud-project/      # GitHub repository clone
├── html/               # Live website files (served by Nginx)
└── deploy.sh           # Deployment script
```

---

## What I Learned

* Practical understanding of cloud infrastructure and server management 
* Hands-on experience deploying and maintaining a live production environment 
* Experience integrating GitHub with a live server for deployment workflows
* Basics of DevOps principles, including automation and scripting 

---

## Future Improvements

* Implement full CI/CD pipeline for automated deployments (no manual deploy needed)
* Custom domain (e.g. seifcloud.dev)
* HTTPS with SSL
* More advanced frontend (portfolio site)

---

## Author

**Seifeddin B**
Aspiring Cloud / DevOps Engineer

---

## Project Status

Completed – Version 1
Actively improving and expanding

