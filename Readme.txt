
Commands Run:

aws cloudformation create-stack  --stack-name DSChallenge13Mar22 --region us-west-2 --template-body file://network.yml --parameters file://network-parameters.json



aws cloudformation create-stack  --stack-name DSNServer13Mar22 --region us-west-2 --template-body file://serverNew13Mar22.yml --parameters file://server-parameters.json


aws cloudformation update-stack  --stack-name DSNServer13Mar22 --region us-west-2 --template-body file://serverNew13Mar22.yml --parameters file://server-parameters.json

Stack Name: DSNServer13Mar22

Public DNS URL:
http://dsnse-webap-1n8tk0nsncnzg-318467656.us-west-2.elb.amazonaws.com/

Output:
WellDone ! Udacity Demo Web Server Up and Running!