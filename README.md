<h1>Build a Serverless Web Application in AWS</h1>
<h2>Overview</h2>
"In this tutorial, you will create a simple serverless web application that enables users to request unicorn rides from the 'Wild Rydes' fleet. The application will present users with an HTML-based user interface for indicating the location where they would like to be picked up and will interact with a RESTful web service on the backend to submit the request and dispatch a nearby unicorn. The application will also provide facilities for users to register with the service and log in before requesting rides."
<h2>Application Architecture</h2>
"The application architecture uses <b>AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console</b>. Amplify Console provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a persistence layer where data can be stored by the API's Lambda function."

https://i.imgur.com/gsXtY61.png
