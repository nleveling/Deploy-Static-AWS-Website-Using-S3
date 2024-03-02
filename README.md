# Deploy-Static-AWS-Website-Using-S3

## Project Overview
This demonstrates how to create an AWS Static Website using S3. This was done to share images with family located around the world of our new born. 

## File Summary
* index.html - The Index document for the website.
* error.html - Error document to re-direct to if site is down.
* /img - This is where images would go. It is empty because  I don't want to the childs images on the internet. (Place your images here to replicate)

## Project Steps
1. Create S3 bucket. Uncheck "Block All Public Access".
   ![Create S3 Bucket] (img/20230714_184302.jpg)

   
3. Upload the files and folders from your local computer to the your S3 bucket. (Index HTML, Error HTML, and Images)
  ![Upload to S3 bucket]


5. Under Bucket Properties Enable Static website hosting. Specify your Index and Error HTML documentation. 
   ![Enable Statc Website hosting]

   
   ![Index and Error HTML]

   
7. Navigate to the bucket Permissions, and update the bucket policy if you want to allow all public access.
    ![Bucket Policy JSON]

   
9. Navigate to the bucket properties > Static website hosting, and click on the Bucket website endpoint to view your website.
   ![Static Site Endpoint]
