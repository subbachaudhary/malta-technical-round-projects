# malta-technical-round-projects
1. Challenge1
- For the first question i used create challenge1 and used terraform to create infrastructure in different environment.
- we can use in dev, stage and prod. 
-  we can also use workspace of terraform to create in different environment.
- to run terraform code please install terraform in local and connect with AWS by 
AWS Config command line
- please clone this Github repo and goto Challenge1 and to tun please stay in common-infra-too directory and run 
- terraform init
- terraform validate
- terraform plan 
- terraform apply
- terraform destroy # please don't use this command more in production with --auto-approve command.

2. For the Challenge2 
-> i created python file i.e query-meta.py and for this we must login aws with 
- aws config command
- must be boto3 install in local pc
- must be some instances created in aws account.
- run python query-meta.py to see output

3. for the challenge3 
-> i created key-value.js file and for this file run 
- must install nodejs in local.
- and to run please apply 
- node key-value.js