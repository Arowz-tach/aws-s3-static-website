# AWS S3 Static Website Hosting

## What I Built
A static personal website built with HTML and 
hosted on Amazon S3 — publicly accessible via 
a live URL.

## Live Website
http://dev-testngmybucket-0231111.s3-website-us-east-1.amazonaws.com/

## Tools & Technologies Used
- AWS S3 (Simple Storage Service)
- HTML
- AWS Console
- AWS CLI (attempted)
- IAM & Bucket Policies

## What I Learned
- Amazon S3 can host static websites without 
  needing an EC2 instance — making it simpler 
  and more cost effective for static content
- How to configure S3 bucket permissions and 
  public access settings
- How bucket policies control who can access 
  your files
- How system clock issues can cause AWS 
  authentication errors and how to fix them

## Errors Faced & How I Fixed Them
- Upload failed due to incorrect system time —
  fixed by syncing my Windows clock
- Permission errors — fixed by disabling Block 
  Public Access and adding a bucket policy

## Result
Successfully deployed a live static website 
on AWS S3 with GitHub and LinkedIn links.
