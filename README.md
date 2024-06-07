# Hosting-static-website-on-AWS-s3-
This project is a static website that features an aesthetic and colorful design, including interactive buttons.

1. Features
- Aesthetic and colorful design
- Navigation bar with links to different sections
- Interactive buttons with alert functionality

2. Technologies Used
- HTML
- CSS

3.Create an S3 Bucket
    - Open the AWS S3 Management Console
    - Create a new bucket named `my-static--website`.

4. Upload Website Files
    - Upload `index.html` and `styles.css` to the S3 bucket.
  
5.  - Configure Bucket Policy
    - Navigate to the "Permissions" tab of the bucket.
    - Click on "Bucket Policy" and paste the JSON policy code uploaded in the files section:

6.   Enable Static Website Hosting
    - Go to the "Properties" tab of the bucket.
    - Click on "Static website hosting".
    - Select "Use this bucket to host a website".
    - Set the index document to `index.html`.
    - Save the changes.
