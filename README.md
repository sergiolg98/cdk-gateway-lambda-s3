# CDK Project: AWS Gateway, Lambda and S3

This is a simple CDK project to build a Cloud infrastructure to retrieve data using AWS Gateway, Lambda and S3.

## Considerations

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `npx cdk deploy`  deploy this stack to your default AWS account/region
* `npx cdk diff`    compare deployed stack with current state
* `npx cdk synth`   emits the synthesized CloudFormation template

## Cloud Architeture

The project will create a simple architecture in which a JSON file will be stored in an S3 Bucket and it will be retrieved by a lambda function invoked by AWS API Gateway.

![Simple Cloud Architecture](https://i.ibb.co/C8dL1xF/AWS-Diagrams-1.png)

