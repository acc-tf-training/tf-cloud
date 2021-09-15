# tf-cloud

Set Up the Environment

In the Github console fork the repo

Apply the Terraform configuration.

In the AWS Console, navigate to the IAM user and generate your Access key ID and Secret access key values.

Copy or download your key to use during the Terraform Cloud setup.

Set Up Your Terraform Cloud Workspace

Navigate to Terraform Cloud at https://app.terraform.io/session and create a free account (or log in if you have an existing account).

Create an organization named "YOUR_NAME".

Create a workspace named "yourname-east-tf"

Navigate to the Variables tab and add two environment variables: one named "AWS_ACCESS_KEY_ID" with a value of your Access key ID and one named "AWS_SECRET_ACCESS_KEY" with a value of your Secret access key.

Add Terraform Variables named region to us-east-1

Do a terraform run the terraform cloud console
