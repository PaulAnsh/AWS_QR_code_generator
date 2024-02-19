## Documenatation

Working on creating AWS_qr_code_generator:

# Tech Specs:
  - AWS
  - AWS Lambda function
  - AWS S3 bucket
  - AWS CLI
  - VS code
  - Python and Terraform


# In details:
- **AWS Lambda function**: Lambda function is used to create the function which will run to create a qr code for the provided url. Deploying it using terraform.
-** AWS S3 bucket**: S3 is used to store the qr code data, so that the qr code is valid for certian period of time. Deploying it using terraform.
- **AWS CLI:** CLI is used to configure aws in terminal for terraform deployments.
- **VS CODE:** vs code is used to code function and terraform scripts. Also, to deploy resources.
- **Python and terraform:** Python is used to write the lambda function, which will generate the qr code. Terraform is used to deploy resources in cloud without logging into aws console.
