Added the git Hub and AWS Credentials to Jenkins for authentication.

Created project files (Jenkinsfile and tf files) for build  and pushed them to GitHub.

In Build pipeline added stages to get the code from Git repository , build created parameters for terraform apply and destroy, created environment variable for AWS credentials.

In first stage given GIT checkout.

In second stage given command terraform init.

In third stage given Terraform plan.
in fourth stage given with parmeters Apply/destroy actions.
