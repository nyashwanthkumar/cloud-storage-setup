# Cloud Storage Setup – AWS S3

This repository shows the basic setup of cloud storage using Amazon S3.  
The goal was to create a bucket, upload sample files, and configure access settings using the AWS Management Console.

## What was done

An S3 bucket named **yash-bucket-task1** was created in AWS.  
While creating the bucket, the recommended default settings were used to ensure proper security and reliability.

Server-side encryption (SSE-S3) was enabled, and the bucket was configured under the standard storage class in the selected AWS region.

Sample files were then uploaded to verify object storage functionality. The uploads were confirmed through the S3 console under the Objects section.

Access permissions were reviewed and configured at the bucket level following AWS best practices to ensure controlled access to stored objects.

## Tools Used

- Amazon Web Services (AWS)
- Amazon S3
- AWS Management Console

## Result

The setup demonstrates a working S3 storage configuration with object upload and access management successfully implemented.

<img width="1918" height="512" alt="bucket-created" src="https://github.com/user-attachments/assets/b96c87ec-54f8-4e96-84cf-4f09ec8b1a2e" />

<img width="1902" height="764" alt="objects-uploaded" src="https://github.com/user-attachments/assets/d160a2e4-a13c-4bbf-be57-6037f800b233" />

<img width="1541" height="512" alt="permissions" src="https://github.com/user-attachments/assets/c6cf3bac-9f49-4c32-b0d6-8dd33e27e031" />

