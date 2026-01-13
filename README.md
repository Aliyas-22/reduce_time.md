#What I Learned Today

Today’s learning was not only about Docker or Kubernetes. Before moving to these tools, it is important to understand cloud fundamentals, especially AWS.

Key Learnings
1. Importance of Cloud (AWS)

Before learning Docker and Kubernetes, we need a strong understanding of cloud services.

AWS plays a major role in building, deploying, and automating applications.

2. Code Flow from GitHub to AWS

The application code is first uploaded to GitHub.

AWS services fetch the code directly from the GitHub repository.

3. Build Process Using AWS CodeBuild

AWS CodeBuild is used to pull the code from GitHub.

CodeBuild runs the build process.

During the build, a Docker image is created from the source code.

4. Automation Using Terraform

Instead of creating resources manually, Terraform is used for automation.

Terraform helps in managing the complete pipeline:

Build

Test

Deploy

5. Connecting AWS to the Terminal (CMD)

The AWS account is connected to the terminal using IAM (Identity and Access Management).

Proper access permissions are provided through IAM.

6. Terraform Commands Used

terraform init – Initializes Terraform

terraform plan – Shows the execution plan before applying changes

7. GitHub Token Integration

Terraform requires a GitHub token.

The token is created from GitHub Settings.

The generated token is entered in the terminal when prompted.

8. Automated Build, Test, and Deploy

After providing the GitHub token:

Terraform automatically handles build, test, and deployment.

No manual intervention is required.

9. Cost-Aware Deployment

Services like ELB and CloudWatch are used carefully.

CloudWatch is mainly used for logs and monitoring.

This approach helps avoid unnecessary AWS costs.

Summary

This session helped me understand how GitHub, AWS, Terraform, and CI/CD automation work together to build, test, and deploy applications efficiently.
