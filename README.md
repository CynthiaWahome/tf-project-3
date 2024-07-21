# Create a NAT Gateway to Access the Internet for Instances in a Private Subnet Using Terraform

## Overview

This beginner-friendly project demonstrates how to create a NAT gateway to enable internet access for instances in a private subnet using Terraform. It involves setting up a VPC, public and private subnets, EC2 instances, and configuring a NAT gateway for private subnet internet connectivity.

## Prerequisites

- **Install Terraform on your local machine:**
  - To install Terraform using CLI, follow the [official guide by Hashicorp](https://learn.hashicorp.com/tutorials/terraform/install-cli).
  - To install Terraform by downloading, visit the [Terraform download page](https://www.terraform.io/downloads.html).

- **Download and Install Visual Studio Code editor:**
  - [Visual Studio Code download guide](https://code.visualstudio.com/download).

## Task Details

1. **Sign into AWS Management Console.**
2. **Create a Key Pair** for SSH access to EC2 instances.
3. **Setup Visual Studio Code** by following the installation guide.
4. **Create a variables file** to store configuration variables.
5. **Create a VPC** in the `main.tf` file.
6. **Create Public and Private Subnets** in the `main.tf` file.
7. **Create an Internet Gateway** in the `main.tf` file.
8. **Create a Public Route Table** and configure it in the `main.tf` file.
9. **Launch Public and Private EC2 Instances** in the `main.tf` file.
10. **Create an output file** to display relevant information.
11. **Confirm the installation of Terraform** by checking the version with `terraform -v`.
12. **Apply Terraform configurations** using `terraform apply`.
13. **Check the resources in AWS Console** to ensure they are created correctly.
14. **SSH into Public and Private EC2 instances** and test internet connectivity.
15. **Create a NAT Gateway** in the `main.tf` file.
16. **Update the Route Table** and configure the NAT Gateway in the `main.tf` file.
17. **Test internet connection** from an instance inside the Private Subnet.
18. **Delete AWS Resources** to avoid incurring unnecessary costs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Cost Considerations

Deploying AWS resources may incur costs. Ensure you delete the resources after completing the project to avoid unwanted charges.

## Documentation

- [Terraform Official Documentation](https://www.terraform.io/docs/index.html)
- [AWS Official Documentation](https://docs.aws.amazon.com/)

