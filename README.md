🌐 Host a Website on Amazon S3

Welcome to the project where we harness the power of Amazon S3 to host a static website! This guide will walk you through each step, ensuring you have a live website by the end.

📋 Project Overview

In this project, we utilize Amazon S3 to host a static website. Amazon S3 (Simple Storage Service) is a scalable storage service that allows you to store and retrieve data from anywhere. By the end of this tutorial, you will have a publicly accessible static website.

🛠️ Steps Followed
1. Create an S3 Bucket
Creating an S3 bucket is the first step. Here's how:

Bucket Name: my-unique-bucket-name
Region: Selected eu-west-2 (London) for low latency
ACLs: Enabled Access Control Lists and allowed public access
Completion Screenshot:
![adb849d6-e064-4614-a41c-be1149a57e08](https://github.com/user-attachments/assets/35e36f39-9843-4daa-bbe9-36b91536e305)



2. Upload Website Files
Next, we upload the necessary files for the website:

Files Uploaded: index.html and a zip file containing additional assets
Completion Screenshot:
![d6b19210-a713-490b-844a-97377ef46bbe](https://github.com/user-attachments/assets/bc4f37b2-c2f0-41d9-be24-29c1e941fc37)



3. Configure Static Website Hosting
Configure the S3 bucket to serve static content:

Static Website Hosting: Enabled and set index.html as the index document
Completion Screenshot:

![dfcfad88-dbb3-43c9-b657-92e7e47d74fb](https://github.com/user-attachments/assets/1d7dacd1-b5e9-47ed-a380-64239ab9c7a7)


4. Set File Permissions
To ensure the website is accessible, set the permissions of the files to public:

File Permissions: Adjusted ACLs to make the contents public
Completion Screenshot:
![45b8277e-2191-49b5-b1b9-f9b89a06552b](https://github.com/user-attachments/assets/f64180c3-7062-442a-af7b-119dac5ab56f)


5. Access the Website
Finally, access the website via the generated bucket endpoint URL:

Completion Screenshot:
![3dced8d2-f4a5-4e95-86e0-96b5e4823cd6](https://github.com/user-attachments/assets/1177c8c6-08ec-40f7-a891-1eb3bb5292f8)


🎉 Conclusion
We successfully hosted a static website on Amazon S3. This project demonstrated the process of creating a bucket, uploading files, configuring static website hosting, and setting the necessary permissions to make the website publicly accessible.

✨ One Thing I Didn't Expect
One unexpected aspect was adjusting file permissions to ensure that the website's assets were publicly accessible.

⏱️ Project Duration
The project took about an hour as I took the time to understand each step deeply.

🏷️ Author
Mustafa Hassan
