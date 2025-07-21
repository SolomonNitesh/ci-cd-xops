This project demonstrates the continuous integration and continuous deployment pipeline of a static website to an AWS EC2 Instance



This project module includes

Web App/

|-index.html

|-README.md

|-GitHub/

&nbsp; |-workflows/

&nbsp;   |-deploy.yml



deploy.yml represents the GitHub Actions workflow



What it does:

1. Host basic static website
2. Triggers GitHub Actions to every push to main branch
3. Uses SSH to connect to EC2 Instance
4. Publicly accessible via EC2 public IP on port 80
5. Restarts web server (nginx) on EC2



Technologies Used:

1. GitHub Actions-For CI/CD workflow automation
2. AWS EC2 (Ubuntu)-For hosting the website
3. Nginx (httpd)-Simple web server
4. PowerShell- Scripting and setup



