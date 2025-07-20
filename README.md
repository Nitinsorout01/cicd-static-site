# CI/CD Static Website Deployment using AWS

## 🚀 Project Overview

This project demonstrates a CI/CD pipeline using **AWS services** to automatically deploy a static website to an S3 bucket.

## 🔧 Technologies Used

- AWS CodeCommit
- AWS CodePipeline
- AWS CodeBuild
- AWS S3 (Static Website Hosting)
- HTML/CSS

## 🧱 Project Structure

/cicd-static-site/
├── index.html
├── buildspec.yml
└── (other files)

markdown
Copy
Edit

## ⚙️ Pipeline Flow

1. Code is pushed to **AWS CodeCommit**.
2. **CodePipeline** is triggered.
3. **CodeBuild** runs using `buildspec.yml`.
4. Output is deployed to **S3 bucket** configured for static hosting.

## 🌐 Live Website

[View Deployed Website](http://cicd-static-site-us-east-1.s3-website-us-east-1.amazonaws.com)

## 🙋‍♂️ Author

**Nitin Sorout**