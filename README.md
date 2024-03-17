
# Deploying a Website on an EC2 Instance with Terraform

Welcome to your step-by-step guide on deploying a website using an Amazon EC2 instance with Terraform. This tutorial assumes you have a basic understanding of AWS and have Terraform installed on your machine.

## Prerequisites

- An AWS account.
- Terraform installed on your computer.

## Step 1: Create Your Project Folder

Start by creating a directory for your Terraform project. This helps in organizing your project files.

```bash
mkdir terraform-ec2-website && cd terraform-ec2-website
```

## Step 2: Prepare Your Terraform Configuration

1. Create a file named `main.tf` in your project directory.
2. Open the `main.tf` file with a text editor of your choice.
3. Copy the Terraform configuration provided separately and paste it into your `main.tf` file.

## Step 3: Initialize Your Terraform Project

Run the following command in your project directory to initialize the Terraform workspace. This step prepares Terraform to manage your infrastructure by downloading necessary plugins and setting up the environment.

```bash
terraform init
```

## Step 4: Apply Your Configuration

Deploy your infrastructure with Terraform using the following command. Terraform will show you a plan and ask for confirmation before making any changes to your AWS resources.

```bash
terraform apply
```

Confirm the action by typing `yes` when prompted.

## Step 5: Access Your Website

After Terraform successfully creates the resources:

1. Go to your AWS Management Console.
2. Locate the EC2 instance created by Terraform.
3. Use the Public IP address of the instance to access your website in a web browser.

Congratulations! You've successfully deployed a website on an EC2 instance using Terraform. Explore further configurations and customize your deployment as needed.



## License

The code within this project is dual-licensed under the GLINCKER LLC proprietary license and the MIT License. This means it is open for reference and educational purposes, allowing for use, modification, and distribution in accordance with the MIT License's terms, while also respecting the proprietary rights and restrictions under the GLINCKER LLC license.

### MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
