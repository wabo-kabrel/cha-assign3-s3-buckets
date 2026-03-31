# Fireworks Composer - AWS S3 Deployment Project

## Project Overview

This project demonstrates the deployment of a static website to **Amazon S3**, a cloud storage service by AWS. The website, "Fireworks Composer," is a creative web application that has been successfully hosted on AWS S3, showcasing practical cloud deployment skills.

## Assignment Objectives

- Learn how to host and deploy static websites using Amazon Web Services (AWS)
- Understand AWS S3 bucket configuration and management
- Configure public access and permissions for a static website
- Deploy HTML, CSS, and JavaScript files to a cloud-based platform
- Gain hands-on experience with cloud infrastructure

## Technologies Used

- **HTML5** - Markup and structure
- **CSS3** - Styling and layout
- **JavaScript** - Interactivity and dynamic behavior
- **Amazon S3** - Cloud storage and static website hosting
- **AWS Management Console** - Cloud resource management

## Deployment Steps

1. **Prepare the Website Files**
   - Downloaded the static website project (HTML, CSS, JavaScript files)
   - Verified all files are properly structured and functional locally

2. **Create an AWS S3 Bucket**
   - Logged into the AWS Management Console
   - Created a new S3 bucket in the eu-north-1 region
   - Configured the bucket name and region settings

3. **Configure S3 Bucket Permissions**
   - Enabled public access to allow website visitors to view the content
   - Added bucket policy to permit public read access
   - Configured appropriate access control lists (ACLs)

4. **Upload Project Files**
   - Uploaded all website files to the S3 bucket
   - Maintained the project folder structure (2153_fireworks_composer/)

5. **Enable Static Website Hosting**
   - Configured the bucket for static website hosting
   - Set index.html as the default index document
   - Obtained the public S3 bucket endpoint URL

6. **Verify Deployment**
   - Tested the website accessibility through the S3 endpoint
   - Confirmed all resources (images, styles, scripts) load correctly

## Live Website

Access the deployed website here:  
🔗 [Fireworks Composer on AWS S3](https://cha-s3-buckets-assign1-397348546376-eu-north-1-an.s3.eu-north-1.amazonaws.com/2153_fireworks_composer/index.html)

## Project Structure

```
2153_fireworks_composer/
├── index.html                    # Main HTML file
├── tooplate-fireworks-style.css  # Stylesheet
├── tooplate-fireworks-composer.js# JavaScript functionality
└── ABOUT THIS TEMPLATE.txt       # Template information
```

## Key Learnings

- Static websites can be efficiently hosted on AWS S3 without running servers
- S3 provides a cost-effective and scalable solution for web hosting
- Proper bucket configuration is essential for security and accessibility
- AWS S3 is ideal for hosting portfolios, documentation, and static applications

## About the Template

This project uses the Fireworks Composer template, a creative web application designed to showcase interactive web design principles.

---

**Assignment Completed:** Cloud Deployment with AWS S3  
**Region:** eu-north-1 (Europe - Stockholm)