# Static Website Deployment using AWS S3 and CloudFront

This project demonstrates how to deploy a static website using **AWS S3** for storage and **AWS CloudFront** as a content delivery network (CDN). The goal of the project is to host a static webpage and make it accessible through a CloudFront distribution.

## Project Overview

The static website files were uploaded to an Amazon S3 bucket and configured for static website hosting. A CloudFront distribution was then created to securely deliver the website content globally.

## Steps Performed

1. Created an Amazon S3 bucket with a unique name.
2. Enabled public access to bucket objects through the S3 object URL.
3. Configured a bucket policy to allow `GetObject` API calls for public read access.
4. Uploaded the static website files to the S3 bucket.
5. Enabled static website hosting in the S3 bucket properties.
6. Copied the bucket ARN for use in the CloudFront configuration.
7. Tested the S3 static website endpoint.
8. Created a CloudFront distribution using the S3 bucket as the origin.
9. Verified the deployment using the CloudFront DNS URL.
10. Captured screenshots of:

* The S3 ARN showing the deployed webpage
* The CloudFront DNS displaying the website
* Successful upload of files to the S3 bucket

11. Stored the screenshots inside the `images` folder in this repository.
12. Performed cleanup operations to avoid unnecessary AWS charges.

## Deployed Website

You can access the deployed static website here: http://riel-st40-2026-784.s3-website.eu-north-1.amazonaws.com

**Website URL:**
*Paste your S3 or CloudFront URL here*

## Project Structure

```
.
├── static-website-files
├── images
│   ├── s3-arn.png
│   ├── cloudfront-dns.png
│   └── s3-upload.png
└── README.md
```

## Technologies Used

* Amazon S3
* Amazon CloudFront
* AWS Management Console
* Git & GitHub
