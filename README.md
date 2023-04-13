<h1>Build a Serverless Web Application in AWS</h1>
<h2>Overview</h2>
"In this tutorial, you will create a simple serverless web application that enables users to request unicorn rides from the 'Wild Rydes' fleet. The application will present users with an HTML-based user interface for indicating the location where they would like to be picked up and will interact with a RESTful web service on the backend to submit the request and dispatch a nearby unicorn. The application will also provide facilities for users to register with the service and log in before requesting rides."
<h2>Application Architecture</h2>
"The application architecture uses <b>AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console</b>. Amplify Console provides continuous deployment and hosting of the static web resources including <b>HTML, CSS, JavaScript</b>, and image files which are loaded in the user's browser. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a persistence layer where data can be stored by the API's Lambda function."
<br>
<br>
<p align="center">
<img src="https://i.imgur.com/EvhjBJV.png" height="85%" width="85%" alt="Reference Architecture"/>
</p>
<br>
<br>
"This tutorial is divided into five modules. Each module describes a scenario of what we're going to build and step-by-step directions to help you implement the architecture and verify your work. 
<br>
<br>
<br>
<b>Host a Static Website (15 minutes):</b> Configure AWS Amplify to host the static resources for your web application with continuous deployment built in<br><br>
<b>Manage Users (30 minutes):</b> Create an Amazon Cognito user pool to manage your users' accounts<br><br>
<b>Build a Serverless Backend (30 minutes):</b> Build a backend process for handling requests for your web application<br><br>
<b>Deploy a RESTful API (15 minutes):</b> Use Amazon API Gateway to expose the Lambda function you built in the previous module as a RESTful API<br><br>
<b>Terminate Resources (10 minutes):</b> Terminate all the resources you created throughout this tutorial"<br>
<br>
<h2>Resources Used</h2>
- [Build a Serverless Web Application](https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/)
