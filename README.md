**Static Portfolio Website with Terraform on AWS**
Welcome to my portfolio project! This project demonstrates my ability to deploy a static website using AWS S3 with infrastructure managed through Terraform.
![image alt]()
![image alt]()
![image alt]()

**Overview**
This repository contains the files for a simple static website consisting of:

index.html: The homepage of my portfolio website.
error.html: A custom error page.
styles.css: The CSS file to style the portfolio.
The website is hosted on AWS S3 and managed through Terraform for infrastructure automation.

**Features**
Terraform Infrastructure:

Creates an S3 bucket for hosting the static website.
Configures the S3 bucket with the necessary settings for static website hosting.
Simple Portfolio:

Includes a clean, responsive portfolio page with information about my skills, projects, and background.
Custom Error Page:

If you go to a non-existent URL, the custom error.html page will be displayed.
Setup Instructions
Prerequisites
Terraform
AWS Account (with appropriate IAM permissions to create S3 buckets)
Steps
Clone this repository:

**bash**
Copy
Edit
git clone https://github.com/your-username/portfolio-website.git
Navigate to the Terraform directory:

**bash**
Copy
Edit
cd portfolio-website/terraform
Initialize Terraform:

**bash**
Copy
Edit
terraform init
Apply the Terraform configuration to create the infrastructure:

**bash**
Copy
Edit
terraform apply
This will create an S3 bucket, configure it for static website hosting, and upload the necessary files (index.html, error.html, styles.css).

Visit the URL provided in the output to view your portfolio website live!

**Clean Up**
To clean up your AWS resources and avoid unnecessary charges, you can run:

bash
Copy
Edit
terraform destroy
**Technologies Used**
HTML: For building the portfolio structure.
CSS: For styling the website.
Terraform: For automating the AWS infrastructure deployment.
AWS S3: For hosting the static website.
**Why This Project?**
This project reflects my ability to integrate cloud infrastructure with web development skills, showcasing my understanding of AWS and Terraform for automating and deploying resources in the cloud.
