# aws_infra_ansible

This role can create a AWS VPC, Subnets, Route tables and associations, Security Groups, NACL, and EC2 instances. It can also delete them. 

## Vars:

workshop-prefix: Unique string appended to all resources that get created, helps to identify components for deletion as well.

number_master_nodes: Number of EC2 nodes to provision.

ami_id: AWS AMI id, if using Red Hat Cloud Access, store id in vault file.

