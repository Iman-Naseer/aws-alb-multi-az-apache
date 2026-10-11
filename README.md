# aws-alb-multi-az-apache
Highly available web tier on AWS: two Apache (httpd) EC2 servers across two Availability Zones, launched via user data and balanced by an Application Load Balancer with a Target Group. Security Groups are locked down so the servers are reachable only through the ALB.
