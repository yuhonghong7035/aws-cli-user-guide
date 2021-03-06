# AWS Command Line Interface User Guide

-----
*****Copyright &copy; 2018 Amazon Web Services, Inc. and/or its affiliates. All rights reserved.*****

-----
Amazon's trademarks and trade dress may not be used in 
     connection with any product or service that is not Amazon's, 
     in any manner that is likely to cause confusion among customers, 
     or in any manner that disparages or discredits Amazon. All other 
     trademarks not owned by Amazon are the property of their respective
     owners, who may or may not be affiliated with, connected to, or 
     sponsored by Amazon.

-----
## Contents
+ [What Is the AWS Command Line Interface?](cli-chap-welcome.md)
+ [Installing the AWS Command Line Interface](cli-chap-install.md)
   + [Install the AWS Command Line Interface on Linux](install-linux.md)
      + [Installing Python on Linux](install-linux-python.md)
      + [Installing the AWS Command Line Interface on Amazon Linux](install-linux-al2017.md)
   + [Install the AWS Command Line Interface on Microsoft Windows](install-windows.md)
   + [Install the AWS Command Line Interface on macOS](install-macos.md)
   + [Install the AWS Command Line Interface in a Virtual Environment](install-virtualenv.md)
   + [Install the AWS CLI Using the Bundled Installer (Linux, macOS, or Unix)](install-bundle.md)
+ [Configuring the AWS CLI](cli-chap-configure.md)
   + [Configuration and Credential Files](cli-configure-files.md)
   + [Named Profiles](cli-configure-profiles.md)
   + [Environment Variables](cli-configure-envvars.md)
   + [Command Line Options](cli-configure-options.md)
   + [Instance Metadata](cli-configure-metadata.md)
   + [Using an HTTP Proxy](cli-configure-proxy.md)
   + [Assuming an IAM Role](cli-configure-role.md)
   + [Command Completion](cli-configure-completion.md)
+ [Tutorial: Using the AWS Command Line Interface to Deploy an Amazon EC2 Development Environment](cli-chap-tutorial.md)
+ [Using the AWS Command Line Interface](cli-chap-using.md)
   + [Getting Help with the AWS Command Line Interface](cli-usage-help.md)
   + [Command Structure in the AWS Command Line Interface](cli-usage-commandstructure.md)
   + [Specifying Parameter Values for the AWS Command Line Interface](cli-usage-parameters.md)
   + [Generate CLI Skeleton and CLI Input JSON Parameters](cli-usage-skeleton.md)
   + [Controlling Command Output from the AWS Command Line Interface](cli-usage-output.md)
   + [Using Shorthand Syntax with the AWS Command Line Interface](cli-usage-shorthand.md)
   + [Using the AWS Command Line Interface's Pagination Options](cli-usage-pagination.md)
+ [Working with Amazon Web Services](chap-working-with-services.md)
   + [Using Amazon DynamoDB with the AWS Command Line Interface](cli-dynamodb.md)
   + [Using Amazon EC2 through the AWS Command Line Interface](cli-using-ec2.md)
      + [Using Key Pairs](cli-ec2-keypairs.md)
      + [Using Security Groups](cli-ec2-sg.md)
      + [Using Amazon EC2 Instances](cli-ec2-launch.md)
   + [Using Amazon S3 Glacier with the AWS Command Line Interface](cli-using-glacier.md)
   + [AWS Identity and Access Management from the AWS Command Line Interface](cli-iam.md)
      + [Create New IAM Users and Groups](cli-iam-new-user-group.md)
      + [Set an IAM Policy for an IAM User](cli-iam-policy.md)
      + [Set an Initial Password for an IAM User](cli-iam-set-pw.md)
      + [Create Security Credentials for an IAM User](cli-iam-create-creds.md)
   + [Using Amazon S3 with the AWS Command Line Interface](cli-s3.md)
      + [Using High-Level s3 Commands with the AWS Command Line Interface](using-s3-commands.md)
      + [Using API-Level (s3api) Commands with the AWS Command Line Interface](using-s3api-commands.md)
   + [Using the AWS Command Line Interface with Amazon SNS](cli-sqs-queue-sns-topic.md)
   + [Using Amazon Simple Workflow Service with the AWS Command Line Interface](cli-using-swf.md)
      + [List of Amazon SWF Commands by Category](swf-commands-by-category.md)
      + [Working with Amazon SWF Domains Using the AWS Command Line Interface](cli-using-swf-domains.md)
+ [Troubleshooting AWS CLI Errors](troubleshooting.md)