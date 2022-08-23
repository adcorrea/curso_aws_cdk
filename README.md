# Welcome to your CDK Java project!

This is a blank project for CDK development with Java.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

It is a [Maven](https://maven.apache.org/) based project, so you can open this project with any Maven compatible Java IDE to build and run tests.

## Useful commands

 * `mvn package`     compile and run tests
 * `cdk ls`          list all stacks in the app
 * `cdk synth`       emits the synthesized CloudFormation template
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk docs`        open CDK documentation

Enjoy!


--lista stacks
Cdk list

-- configura conta aws
Cdk configure


-- implanta as stacks
Cdk deploy stack1 stack2 

-- destroy as stacks
Cdk destroy stack1 stack2

-- deploy Rds
cdk deploy --all --parameters Rds:databasePassword=matilde123456

-- cria docker que emula serviços AWS
docker run --rm -p 4566:4566 -p 4571:4571 localstack/localstack -e "SERVICES=sns,sqs,dynamodb,s3"


-- Emula serviços AWS
https://github.com/localstack/localstack


-- Rodar local
-- Em enviroment variables
spring.profiles.active=local

