# aws-cicd-pipeline

This repo contains a CloudFormation template for a CI/CD pipeline.

## Deploying

Deploy the pipeline using the following command

`npm run:deploy`

After running this command the following resources will be created:

- A CodePipeline pipeline
- A CodeCommit repository
- An S3 bucket

Once you push code to the repository the pipeline will be triggered.
