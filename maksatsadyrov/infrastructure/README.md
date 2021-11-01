# Ansible Collection - maksatsadyrov.infrastructure

Documentation for the collection.

1. "ec2" role creates 3no of t2.micro ec2 instances in us-east-region. To check this role run ec2.yaml playbook

2. "groups" role creates two AWS IAM users and one DevOps group in your AWS account. To check this role run groups.yaml

3. "backup" role installs R1Soft agent on remote machines. To check this role run backup.yaml with extra var indicating your R1Soft Server IP. 

4. wordpress.yaml uses following roles in sequence:   
    - apache
    - mariadb
    - php
    - wordpress
