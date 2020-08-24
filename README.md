# IaC
Infrastructure as Code:

Project Udagram: Deploying a high availability web app using Cloudformation

YAML script(infra_setup.yml) includes code to deploy infrastructure - networking components, servers as well as Load Balancer, Launch Configuration, AutoScaling group with health check as per best practices, security groups and a Listener and Target Group.
Parameters are retrieved from json file (infra_parameters.json). 
Outputs are VPC ID and Load Balancer URL for Udagram app (http://udagr-udaap-1dzaubg4ezbr8-1827862307.us-west-2.elb.amazonaws.com/) . Attached are result and output files.

