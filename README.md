# Serverless Image Resizing API with AWS Lambda

Objective:
Design a serverless Lambda function on AWS that reads an image file from an S3 bucket, creates multiple sizes of it, and saves them back to the same S3 bucket. Additionally, implement an API to trigger this function securely.

### Requirements:

1. Create a Lambda function using Node.js or Python.
2. Implement image resizing functionality to generate multiple sizes (e.g., thumbnail, medium, large) of the image.
3. Set up AWS API Gateway to create an API endpoint that triggers the Lambda function.
4. Ensure security measures are implemented to protect the API endpoint and AWS resources.

### Instructions:

1. **Setup AWS Resources:**

   - Create an S3 bucket to store the original and resized images.
   - Create a Lambda function with appropriate IAM roles and permissions.
   - Set up AWS API Gateway to create an API endpoint.

2. **Implement Lambda Function:**

   - Write code to handle the Lambda function's logic.
   - Use the AWS SDK to interact with S3 for reading and writing image files.
   - Utilize image processing libraries like Sharp (Node.js) or PIL (Python) to resize images.

3. **Create API Endpoint:**

   - Configure AWS API Gateway to create a REST API.
   - Define a resource and method (e.g., POST) to upload image in S3 bucket.
   - Define a resource and method (e.g., GET) for triggering the Lambda function.
   - Enable CORS (Cross-Origin Resource Sharing) if necessary.

4. **Implement Security Measures:**

   - Implement authentication and authorization mechanisms for the API endpoint. Options include:
     - Using AWS IAM roles and policies to control access.
     - Implementing API keys or JWT (JSON Web Tokens) for authentication.
   - Encrypt sensitive data such as API keys or credentials using AWS KMS (Key Management Service).
   - Enable AWS CloudTrail to log API requests for auditing and monitoring.

5. **Testing:**

   - Test the API endpoint using tools like Postman or cURL.
   - Verify that the Lambda function triggers correctly and resizes images as expected.
   - Test security measures to ensure only authorized users can access the API.

6. **Documentation:**
   - Provide clear documentation on how to deploy and use the solution.
   - Include instructions for configuring security settings and accessing the API endpoint.

### Submission:

- Submit the codebase for the Lambda function and API configuration.
- Provide the GitHub repository URL as a PRIVATE Git repository (also provide access) to roshan@gitforcetalent.com and cc prithvi@gitforcetalent.com, arun@gitforcetalent.com, pankaj@gitforcetalent.com
- Include documentation detailing the deployment process and security measures implemented.
- Provide any additional notes or considerations regarding the implementation.

### AWS Submission TODO's:

1. **Hosting the Code on AWS**: You need to deploy your code to your AWS account.

2. **Provide AWS Credentials for Evaluation (Optional)**: If you're comfortable sharing your AWS credentials, you can provide them on above mentioned emails. These credentials would allow them to access your AWS resources for evaluation purposes.

3. **API Endpoint/URL Structure**: If you prefer not to share your AWS credentials, you can instead provide an API endpoint or URL structure that we can use to check different sized images of the converted image.

Note: Ensure adherence to best practices for serverless architecture, security, and AWS services usage throughout the assignment.
