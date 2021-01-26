## AWS CodePipeline build status integration with third party GIT repository

Please see the AWS DevOps Blog (https://aws.amazon.com/blogs/devops/) article AWS CodePipeline build status integration with third party GIT repository for instructions and more context.

AWS CodePipeline allows using third-party git repository as a source for a pipeline and keeping track on results of pipeline execution triggered by a particular commit can be challenging. Setting up this solution assumes some knowledge of CloudFormation, Python3 and the boto3 AWS SDK.

You will need to have or configure an existing AWS CodePipeline pipeline setup with source provider Bitbucket or GitHub and jave access to GitHub or Bitbucket account to generate API credentials.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

