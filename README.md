\# AWS DevOps Engineer Intern Assignment



\## EC2 Setup



1\. Created Ubuntu EC2 instance.



2\. Created and configured a Security Group:

&#x20;  - Allowed Port 22 (SSH)

&#x20;  - Allowed Port 80 (HTTP)



3\. Installed Nginx.



4\. Hosted a custom HTML webpage.



5\. Commands used:

&#x20;  - `sudo apt update`

&#x20;  - `sudo apt install nginx -y`

&#x20;  - `sudo systemctl start nginx`

&#x20;  - `sudo systemctl status nginx`

&#x20;  - `sudo systemctl restart nginx`

&#x20;  - `df -h`

&#x20;  - `free -h`

&#x20;  - `ps -aux`



\## Bonus Task



\### Docker



\- Downloaded and installed Docker by following the official Docker documentation.

\- Started a hello-world Docker Container:



&#x20; - `sudo docker run hello-world`



\### Shell Script



Created a shell script to restart Nginx.



\*\*restart-nginx.sh\*\*



```bash

\#!/bin/bash

sudo systemctl restart nginx

echo "Nginx restarted successfully."

