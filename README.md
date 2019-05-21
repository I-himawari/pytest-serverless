# pytest-serverless
Mock local resources for serverless framework.

## What problem it tries to solve?
When building your project with [serverless](https://serverless.com/) most likely you will create
[resources](https://serverless.com/framework/docs/providers/aws/guide/resources/) like dynamodb tables, sqs queues, sns topics.

During writing tests you will have to mock those in [moto](https://github.com/spulec/moto). 

This pytest plugin tries to automate this process by reading `serverless.yml` file and create
mocks of resources for you.

## Supported resources
### AWS::DynamoDB::Table

## Issues?
Plugin is in early stage of development, so you might find some bugs or missing functionality.

If possible create pull request that fixes particular problem.
