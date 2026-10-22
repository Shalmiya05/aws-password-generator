# Password Generator — AWS S3 & CloudFront

## Project Overview
This project is a simple web-based Password Generator built using HTML, CSS, and JavaScript. It generates a 10 character password containing uppercase letters, lowercase letters, numbers, and special characters, with an option to copy the generated password.

The website is being deployed using Amazon S3 for static file storage and Amazon CloudFront for content delivery.

## Features
- Generate a random 10 character password.
- Include uppercase and lowercase letters, numbers, and special characters.
- Copy the generated password using the Copy button.
- Simple, browser based interface.

## Technologies Used
- HTML5
- CSS3
- JavaScript
- Amazon S3
- Amazon CloudFront
- GitHub

## AWS Architecture
**User → Amazon CloudFront → Amazon S3**

Amazon S3 stores the static website files, while CloudFront delivers the website content through its content delivery network.

## Project Structure

```text
aws-password-generator/
├── index.html
├── error.html
├── css/
│   ├── Style.css
│   ├── all.min.css
│   └── bootstrap.min.css
├── js/
│   └── site.js
├── screenshots/
└── README.md
```


## AWS Deployment Steps
1. Created an Amazon S3 bucket to store the website files.
2. Uploaded the website files and required assets to S3.
3. Configured Amazon CloudFront with S3 as the origin.
4. Configured the required origin access permissions.
5. Tested the website using the CloudFront distribution URL.


## Key Learnings
- Static website hosting using Amazon S3.
- Content delivery using Amazon CloudFront.
- Basic JavaScript functions and DOM manipulation.
- AWS origin access configuration and troubleshooting.

## Author
**Shalmiya S.**

Computer Science Graduate | Aspiring Cloud & DevOps Engineer

## Project Status

Completed as a hands on AWS learning project. The website was tested using Amazon S3 and CloudFront. AWS resources may be stopped or deleted to avoid ongoing charges.

## Screenshots

![Amazon S3 configuration](screenshot_1.png)

![CloudFront Distribution](screenshot_2.png)

![Password Generator Website](screenshot_3.png)
