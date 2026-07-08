# AWS DevOps Engineer Intern Assignment

## EC2 Setup

1. Created Ubuntu EC2 instance.

2. Created and configured a Security Group:
   - Allowed Port 22 (SSH)
   - Allowed Port 80 (HTTP)

3. Installed Nginx.

4. Hosted a custom HTML webpage.

5. Commands used:
   - `sudo apt update`
   - `sudo apt install nginx -y`
   - `sudo systemctl start nginx`
   - `sudo systemctl status nginx`
   - `sudo systemctl restart nginx`
   - `df -h`
   - `free -h`
   - `ps -aux`

## Bonus Task

### Docker

- Downloaded and installed Docker by following the official Docker documentation.
- Started hello-world Container:

  - `sudo docker run hello-world`

### Shell Script

Created a shell script to restart Nginx.

**restart-nginx.sh**

```bash
#!/bin/bash
sudo systemctl restart nginx
echo "Nginx restarted successfully."
