# AWS-Terraform-Project-
Terraform Project to deploy a static website on AWS S3



**Interactive Terraform + AWS Static Website Deployment Project**

This project provisions AWS infrastructure using Terraform and deploys a
static website (HTML portfolio page). It is ideal to get hands on with
Terraform and AWS services.

------------------------------------------------------------------------


------------------------------------------------------------------------

## 🚀 Features

-   Deploys an AWS S3 bucket configured for static website hosting
-   Uploads a sample **portfolio HTML page**
-   Infrastructure‑as‑Code using Terraform
-   Clean, modular Terraform files (variables, outputs, provider)
-   Includes Steps to Clone and deploy the apllication.

------------------------------------------------------------------------

## 📁 Repository Structure

    ├── main.tf
    ├── provider.tf
    ├── variables.tf
    ├── outputs.tf
    ├── index (1).html        # Portfolio page you can upload to S3
    ├── error.html
    └── README.md

------------------------------------------------------------------------

## 🧪 Getting Started

### Prerequisites

-   Terraform installed
-   AWS CLI configured
-   AWS account with S3 + IAM permissions

------------------------------------------------------------------------

## 🛠️ Steps to Deploy

1️⃣ Clone the repo

    git clone https://github.com/<your-username>/<your-repo>.git
    cd AWS-Terraform-Project

2️⃣ Initialize Terraform

    terraform init

3️⃣ Preview infra

    terraform plan

4️⃣ Apply changes

    terraform apply

5️⃣ After provisioning, upload the **index.html** file to your S3 bucket
(if not automated).

------------------------------------------------------------------------

## 🧹 Destroy Infra

    terraform destroy

------------------------------------------------------------------------

## ⚙️ Extending This Project

-   Add CloudFront CDN for global caching
-   Attach domain via Route 53
-   Enable HTTPS using ACM
-   Add GitHub Actions for Terraform CI/CD
-   Add multi‑environment support (dev/stage/prod)

------------------------------------------------------------------------

## 🧑‍💻 Portfolio Demo Page

A ready‑to‑use static portfolio page is included in this repo
(`index.html`).\
You can modify it and upload it to your S3 bucket.

------------------------------------------------------------------------

## 💬 Contributions

Feel free to submit PRs or raise issues.

------------------------------------------------------------------------

## 📄 License

For learning & demonstration only.

------------------------------------------------------------------------

Happy automating! ☁️⚡

