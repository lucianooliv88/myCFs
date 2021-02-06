# myCFs
web-servers.yml template
Description: Create EC2 instances in AZs- A and C using AWS CloudFormation, installing Apache, a webpage, docket with tomcat image and SSM agent installation.

This is assuming the Entire VPC is already in and including SG as well.
Security consideration is not applied as it is open 0.0.0.0

VPC_with_pub_priv_subnets.yaml template
deploy an entire VPC from 0 - pub and priv subnets also attachs internet gateway and create 3 nat gateways for each subnet including the table routes
