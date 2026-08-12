# AWS S3 Static Website Hosting

## Project Overview

This project demonstrates the deployment of a static website using
Amazon Simple Storage Service (Amazon S3).

The website is hosted using Amazon S3 Static Website Hosting and
is accessible through the S3 website endpoint.

## AWS Services Used

- Amazon S3
- S3 Static Website Hosting
- S3 Bucket Policy
- AWS Free Plan

## AWS Region

Asia Pacific (Hyderabad)

## Architecture

User
  |
  v
Internet
  |
  v
Amazon S3
  |
  +-- HTML files
  +-- CSS
  +-- Images
  +-- Other website resources

## Implementation

1. Created an Amazon S3 bucket.
2. Configured the bucket in the Asia Pacific (Hyderabad) region.
3. Enabled static website hosting.
4. Configured index.html as the index document.
5. Configured error.html as the error document.
6. Configured public access settings.
7. Created an S3 bucket policy allowing public read access.
8. Uploaded the website files.
9. Tested the website using the S3 website endpoint.

## Troubleshooting

### Issue: Policy has invalid resource

While configuring the S3 bucket policy, an invalid resource error
was encountered.

### Solution

The bucket ARN was corrected to:

arn:aws:s3:::ummiya-ststic-website/*

After correcting the bucket name in the ARN, the bucket policy
was successfully saved.

## Result

The website was successfully deployed and accessed through the
Amazon S3 static website endpoint.

## Skills Demonstrated

- Amazon S3
- Static website deployment
- AWS permissions
- S3 bucket policies
- Resource ARNs
- Public access configuration
- Basic AWS troubleshooting
