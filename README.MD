# Terraform AWS EC2 Module

## Input:

* ami_id (optional): ami_id is optional. Default value is ami-090252cbe067a9e58
* security_group_ids (optional): list of security group ids.default is sg-09fb62fc0a39eb931
* instance_type(optional): Default value is t3.micro.
* tags(optional): Default value is empty.

## outputs:
* public_ip: outputs the public IP of the instance created.
* private_ip: outputs the private IP of the instance created.
* instance_id: outputs the instance ID created.