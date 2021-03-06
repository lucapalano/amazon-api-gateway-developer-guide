# Generate an SDK for a REST API in API Gateway<a name="how-to-generate-sdk"></a>

To call your REST API in a platform\- or language\-specific way, you must generate the platform\- or language\-specific SDK of the API\. Currently, API Gateway supports generating an SDK for an API in Java, JavaScript, Java for Android, Objective\-C or Swift for iOS, and Ruby\.

This section explains how to generate an SDK of an API Gateway API and demonstrates how to use the generated SDK in a Java app, a Java for Android app, Objective\-C and Swift for iOS apps, and a JavaScript app\. 

To facilitate the discussion, we use this API Gateway [API](simple-calc-lambda-api.md), which exposes this [Simple Calculator](simple-calc-nodejs-lambda-function.md) Lambda function\. 

Before proceeding, create or import the API and deploy it at least once in API Gateway\. For instructions, see [Deploying a REST API in Amazon API Gateway](how-to-deploy-api.md)\.

**Topics**
+ [Generate SDKs for an API Using the API Gateway Console](how-to-generate-sdk-console.md)
+ [Generate SDKs for an API Using AWS CLI Commands](how-to-generate-sdk-cli.md)
+ [Simple Calculator Lambda Function](simple-calc-nodejs-lambda-function.md)
+ [Simple Calculator API in API Gateway](simple-calc-lambda-api.md)
+ [Simple Calculator API OpenAPI Definition](simple-calc-lambda-api-swagger-definition.md)