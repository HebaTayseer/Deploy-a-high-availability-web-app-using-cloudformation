# Deploy-a-high-availability-web-app-using-cloudformation

In this project, I deployed web servers for a highly available web app using CloudFormation. 

The code creates and deploys the infrastructure and application for an app from the ground up. It creates a network that consists of a public and private network that has access to the internet through NAT and Internet Gateway, an autoscaling group with its security group, a load balancer to manage the traffic automatically and performe health checks in order to scale the group up or down.

URL : http://mysec-webap-1a6e3s7vjki56-497931599.us-east-1.elb.amazonaws.com/
