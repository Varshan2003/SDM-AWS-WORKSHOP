# SDM-AWS-WORKSHOP

## Agenda

- Introduction to cloud computing and AWS
	- Cloud computing concepts
	- AWS Regions and Availability Zones
	- Shared responsibility model
	- AWS pricing and cost awareness

- AWS account and security basics
	- IAM users, roles, and permissions
	- Least-privilege access
	- Multi-factor authentication
	- Billing alerts and resource cleanup

- Understanding the Student Notes application
	- Application architecture
	- Frontend, backend, and database responsibilities
	- Request flow between AWS services

- Hosting the frontend with Amazon S3
	- Create an S3 bucket
	- Upload the application files
	- Configure static website hosting
	- Access the hosted webpage

- Creating the backend with AWS Lambda
	- Create a Lambda function
	- Write and test a function
	- Return student notes as JSON
	- Understand event and response objects

- Exposing the backend with API Gateway
	- Create an HTTP API
	- Connect API Gateway to Lambda
	- Configure routes for creating and viewing notes
	- Test API requests

- Storing notes with Amazon DynamoDB
	- Create a DynamoDB table
	- Understand tables, items, and attributes
	- Save notes from Lambda
	- Retrieve notes from DynamoDB

- Connecting the frontend and backend
	- Send requests from the webpage to the API
	- Submit a new note
	- Display saved notes
	- Handle basic errors

- Monitoring and troubleshooting with CloudWatch
	- View Lambda logs
	- Identify failed requests
	- Diagnose common configuration errors
	- Retest the application after fixing an issue

- Review and cleanup
	- Review the complete AWS architecture
	- Identify next steps for learning AWS