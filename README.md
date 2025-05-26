# using-Terraform-to-deploy-on-AWS
Deploying S3 bucket, Dynamo DB, VPC AND EKS Cluster on AWS


To create DynamoDB and S3 Bucket Using Terraform Backend Code

Git clone https://github.com/iam-veeramalla/ultimate-devops-project-aws.git


CREATE ACCESS KEY & SECRET ACCESS KEY
AWS CONSOLE
Access key: 
Secret acess key: 

On terminal
Run
Aws configure
ADD THE BOTH KEY

Then enter your keys and region:
AWS Access Key ID [None]: YOUR_ACCESS_KEY_ID
AWS Secret Access Key [None]: YOUR_SECRET_ACCESS_KEY
Default region name [None]: us-east-1         ← or your region
Default output format [None]: json


git clone https://github.com/iam-veeramalla/ultimate-devops-project-aws.git
cd ultimate-devops-project-aws
Ls
cd eks-install/

ls
Cd backend
ls main.tf
nano main.tf

To Initialise terraform
terraform init

To see the configuration, Run
Terraform plan

Run
Terraform apply

Option
Choose yes



AWS DynamoDB and S3 bucket will be created.
cd ..
ls main.tf
nano main.tf
Change the following s3 bucket, dynamo db, region us-west-2
Save

Terraform init
Terraform plan
Terraform apply


return to AWS console to view
vpc
eks cluster
s3
dynamo db


after delete from terminal by running this 

terraform destroy


