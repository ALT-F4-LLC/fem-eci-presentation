[![Frontend Masters](https://static.frontendmasters.com/assets/brand/logos/full.png)][fem]

This is a companion repo for the [Enterprise DevOps][fem] course on [Frontend Masters][fem].

## Course Instructions and Resources
A markdown file with the slide content can be found [in this repo](slides.md). Use the instructions below to setup the accounts required for this course.

### Doppler
Doppler helps sync, manage, and rotate secrets across applications and environments.

1. Create a [Doppler Account](https://dashboard.doppler.com/register).
2. Install the [Doppler CLI](https://docs.doppler.com/docs/cli).

### GitHub
GitHub will be used as the source of truth for the infrastructure created in the course. You will need a GitHub account with an SSH key and a fine-grained personal access token. The process of creating and adding an SSH key and fine-grained personal access token are covered in the **GitHub Configuration** lesson. 

### Terraform Cloud
Terraform creates the automation for provisioning and managing cloud resources. You will need a Terraform account and the Terraform CLI

1. Create a [Terraform Cloud account](https://app.terraform.io/public/signup/account)
2. Create an Organization using your name. You DO NOT need to create a workspace yet
2. Install the [Terraform CLI](https://developer.hashicorp.com/terraform/downloads)

### Amazon Web Services (AWS)
Network resources will be hosted on AWS. You will need an AWS account and the AWS CLI

1. Create an [AWS Account](https://portal.aws.amazon.com/billing/signup)
2. Install the [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)


## Other Instructions

### Add VCS Provider to Terraform
If you see `GitHub App (Installed)` when adding a VCS Provider in the **Configuring a Version Control Provider** lesson but you DO NOT see Terraform listed in your GitHub account under Settings > Applications > Installed GitHub Apps, follow the steps below:

1. In Terraform, go to **Projects  & Workspaces**
2. In your `fem-eci-project`, select the `fem-eci-tfe` workspace
3. In this workspace, go to Settings > Version Control and click on **Connect to version control**
4. Choose **Version Control Workflow**
5. Under GitHub, choose **GitHub App** (make sure allow popups)

You can stop at this step (you don't need to select any repositories). Once the VCS Provider is added, you can view it in your GitHub account under Settings > Application > Installed GitHub Apps. Later in the lesson you'll need the installation ID which can be found in the URL when you click on the **configure** button.


### Deleting Workspaces
Once you have completed the course, you may want to delete your workspaces to avoid going beyond the free tier. You can use the **Destroy Infrastructure** option in Terraform Cloud. Delete your workspaces in reverse order
1. fem-eci-product-service-prod
2. fem-eci-aws-cluster-prod
3. fem-eci-aws-network
4. fem-eci-github
5. fem-eci-tfe

For each workspace:
1. Click on the workspace you want to delete
2. Go to > Settings > Destruction and Deletion
3. Make sure **Allow destroy plans** is enabled
4. Click **Queue destroy plan**

### Veryify you are not accumulating costs
If you manually removed resources from AWS or want to ensure the Terraform Automation destroyed any cost-accumulating resources, you can monitor the **Cost Explorer** in AWS
1. Under the account menu in the upper right, navigate to **Billing Dashboard**
2. Select **Cost explorer** in the sidebar under Cost Mangement

Here you will find a cost summary. If you have other AWS services, but want to ensure the resources from this course are not accumulating costs use the **Report Parameters** on the right to group by the **Service** dimension.


[fem]: https://frontendmasters.com/courses/enterprise-devops
