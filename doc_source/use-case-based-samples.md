--------

 The procedures in this guide support the new console design\. If you choose to use the older version of the console, you will find many of the concepts and basic procedures in this guide still apply\. To access help in the new console, choose the information icon\.

--------

# AWS CodeBuild Use Case\-Based Samples<a name="use-case-based-samples"></a>

You can use these use case\-based samples to experiment with AWS CodeBuild:


****  

| Name | Description | 
| --- | --- | 
| [Amazon ECR Sample](sample-ecr.md) | Uses a Docker image in an Amazon ECR repository to use Apache Maven to produce a single JAR file\. | 
| [Docker Sample](sample-docker.md) | Uses a build image provided by AWS CodeBuild with Docker support to produce a Docker image with Apache Maven\. Pushes the Docker image to a repository in Amazon ECR\. You can also adapt this sample to push the Docker image to Docker Hub\. | 
| [Amazon EFS Sample](sample-efs.md) | Shows how to configure a buildspec file so that an AWS CodeBuild project mounts and builds on an Amazon EFS file system\. | 
| [GitHub Enterprise Sample](sample-github-enterprise.md) | Uses AWS CodeBuild with GitHub Enterprise as the source repository, with certificates installed and webhooks enabled, to rebuild the source code every time a code change is pushed to the repository\. | 
| [GitHub Pull Request Sample](sample-github-pull-request.md) | Uses AWS CodeBuild with GitHub as the source repository and webhooks enabled, to rebuild the source code every time a code change is pushed to the repository\. | 
| [Bitbucket Pull Request Sample](sample-bitbucket-pull-request.md) | Uses AWS CodeBuild with Bitbucket as the source repository and webhooks enabled, to rebuild the source code every time a code change is pushed to the repository\. | 
| [Use AWS Config with AWS CodeBuild Sample](how-to-integrate-config.md) | Shows how to set up AWS Config\. Lists which AWS CodeBuild resources are tracked and describes how to look up AWS CodeBuild projects in AWS Config\. | 
| [ Host Build Output in an Amazon S3 Bucket ](sample-disable-artifact-encryption.md) | Shows how to create a static website in an Amazon S3 bucket using unencrypted build artifacts\. | 
| [ Multiple Input Sources and Output Artifacts Sample ](sample-multi-in-out.md) |  Shows how to use multiple input sources and multiple output artifacts in a build project\.  | 
| [ AWS CodePipeline Integration with AWS CodeBuild and Multiple Input Sources and Output Artifacts Sample ](sample-pipeline-multi-input-output.md) |  Shows how to use AWS CodePipeline to create a build with multiple input sources and multiple output artifacts\.  | 
| [Build Badges Sample](sample-build-badges.md) | Shows how to set up AWS CodeBuild with build badges\. | 
| [Using Semantic Versioning to Name Build Artifacts Sample](sample-buildspec-artifact-naming.md) | Shows how to use semantic versioning to create an artifact name at build time\. | 
| [Build Notifications Sample](sample-build-notifications.md) | Uses Apache Maven to produce a single JAR file\. Sends a build notification to subscribers of an Amazon SNS topic\. | 
| [Docker in Custom Image Sample](sample-docker-custom-image.md) | Uses a custom Docker image to produce a Docker image\. | 
| [AWS CodeDeploy Sample](sample-codedeploy.md) | Uses Apache Maven to produce a single JAR file\. Uses AWS CodeDeploy to deploy the JAR file to an Amazon Linux instance\. You can also use AWS CodePipeline to build and deploy the sample\. | 
| [AWS Lambda Sample](sample-lambda.md) | Uses AWS CodeBuild, Lambda, AWS CloudFormation, and AWS CodePipeline to build and deploy a serverless application that follows the AWS Serverless Application Model \(AWS SAM\) standard\. | 
| [Elastic Beanstalk Sample](sample-elastic-beanstalk.md) | Uses Apache Maven to produce a single WAR file\. Uses Elastic Beanstalk to deploy the WAR file to an Elastic Beanstalk instance\. | 