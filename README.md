# AWS-infrastructure-deployment-with-Terraform
 Creating Infrastructure on AWS using IaC tool called Terraform

In this project which was carried out at Altschool Africa, we were required to create 3 EC2 instances, provision a load balancer for these instances and a Route53 service pointing to the load balancer.

I made use of the automation tool Ansible to deploy Nginx on the web servers (EC2 Instances) and to also change the default index.html to display Instance IP addresses.

I use Terraform init to initialize, Terraform plan to view infrastructure and terraform apply to deploy infrastruction.
