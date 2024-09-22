# aws-polly-serverless-api
A serverless application built with AWS Lambda, API Gateway, DynamoDB, S3, and SNS that converts text to speech using Amazon Polly. Users can input text, and the app generates various audio files that can be played directly in the browser.

# Objectives
By the end of this workshop, you should be able to:

Create an Amazon DynamoDB table to store data Create an Amazon API Gateway RESTful API Create AWS Lambda functions triggered by API Gateway Connect AWS Lambda functions with Amazon Simple Notification Service (SNS) Use Amazon Polly to synthesize speech in a variety of languages and voices Duration This workshop requires approximately 90 minutes to complete.

# Workshop environment
You build a serverless application, which means that you do not need to work with servers — no provisioning, no patching, no scaling. The AWS Cloud automatically takes care of this, allowing you to focus on your application.

The application provides two methods – one for sending information about a new post, which should be converted into an MP3 file, and one for retrieving information about the post (including a link to the MP3 file stored in an Amazon S3 bucket). Both methods are exposed as RESTful web services through Amazon API Gateway.
