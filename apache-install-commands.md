# AWS EC2 Apache Web Server Lab

This lab demonstrates deploying a web server on an AWS EC2 instance.

## Steps Performed

1. Launch EC2 instance (Amazon Linux)

2. Configure Security Group
- SSH (Port 22)
- HTTP (Port 80)

3. Connect to EC2 instance

4. Install Apache

sudo yum update -y
sudo yum install httpd -y

5. Start Apache server

sudo systemctl start httpd
sudo systemctl enable httpd

6. Verify server is running

http://EC2-public-IP


## Result

Apache web server successfully displayed via the EC2 public IP address.
