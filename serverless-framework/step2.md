In this section we will install AWS CLI and after that we will configure
AWS credentails for Serverless Framework.

To install AWS CLI we will use command from the [AWS-Documentation](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html) for Linux x86 (64 bit)

Execute the following commands in the work environment.

`curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"`{{execute}} 

`unzip awscliv2.zip`{{execute}} 

`sudo ./aws/install`{{execute}}

Let's check the version of AWS CLI that was installed.

`aws --version`{{execute}}

We can see that we have it installed correctly.

Now, we have Serverless Framework installed, AWS CLI installed, next step is to create AWS user credentials and configure the AWS CLI.