# Serverless Image Resizing API with AWS Lambda

Objective:
Design a serverless Lambda function on AWS that reads an image file from an S3 bucket, creates multiple sizes of it, and saves them back to the same S3 bucket. Additionally, implement an API to trigger this function securely.

### Requirements:

1. Create a Lambda function using Node.js or Python.
2. Implement image resizing functionality to generate multiple sizes (e.g., thumbnail, medium, large) of the image.
3. Set up AWS API Gateway to create an API endpoint that triggers the Lambda function.

### Instructions:

1. **Setup AWS Resources:**

   - Create a Lambda function with appropriate IAM roles and permissions.
   - Set up AWS API Gateway to create an API endpoint.

2. **Implement Lambda Function:**

   - Write code to handle the Lambda function's logic.
   - Use the AWS SDK to interact with S3 for reading and writing image files.
   - Utilize image processing libraries like Sharp (Node.js) or PIL (Python) to resize images.

3. **Create API Endpoint:**

   - Configure AWS API Gateway to create a REST API.
   - Define a resource and method (e.g., GET) for triggering the Lambda function.
