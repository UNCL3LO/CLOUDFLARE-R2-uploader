Cloudflare R2 Uploader Documentation

Table of Contents

Introduction
Setup Instructions
Testing Process
Troubleshooting
Feedback and Support
1. Introduction

Thank you for choosing the Cloudflare R2 Uploader! This document will guide you through setting up and testing the uploader on your environment. The Cloudflare R2 Uploader is a simple tool designed to help you upload files to Cloudflare R2 object storage easily.

2. Setup Instructions

To get started with the Cloudflare R2 Uploader, follow these steps:

Step 1: Download the Files

Download the provided index.php and upload.php files to your local machine.
Step 2: Configure Cloudflare R2 Details

Open the upload.php file in a text editor.
Locate the placeholders for Cloudflare R2 details: your-account-name, your-api-key, and your-bucket-name.
Replace these placeholders with your actual Cloudflare R2 account details.
Step 3: Server Setup

If you have a web server, upload the files to a folder accessible via a URL.
If you don't have a web server, you can use a local server environment like XAMPP or Node.js' http-server.
3. Testing Process

Follow these steps to test the Cloudflare R2 Uploader:

Step 1: Access the Application

Open your web browser and navigate to the URL where you placed the index.php file.
Step 2: Upload a File

Click the "Choose File" button and select a test file from your computer.
Click the "Upload File" button to initiate the upload.
Step 3: Verify Upload

After the upload completes, you should see a success message along with the uploaded file's URL.
4. Troubleshooting

If you encounter any issues during testing, follow these tips:

cURL Errors: If you see a cURL error, it might be related to network connectivity or Cloudflare R2 configuration. Check your API key and endpoint settings.

Upload Errors: If the file doesn't upload successfully, ensure the selected file is within the allowed size and format limits.

5. Feedback and Support

We value your feedback! If you encounter any issues, have suggestions, or need assistance, feel free to reach out to us at [your contact information].

Congratulations, you've successfully set up and tested the Cloudflare R2 Uploader! We appreciate your trust in our tool. If you have any questions or need further assistance, don't hesitate to contact us. Your feedback helps us improve the tool and provide better solutions in the future.
