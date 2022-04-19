In this step we will create a user in our AWS account and configure AWS credentails for Serverless Framework.

In order to create a user other then root user ( not good idea to use root user ) we will use [AWS-Identity-And-Access-Management](https://aws.amazon.com/iam/) which in short handles the permissions and users in AWS. To create a new user, login to your [AWS-Management-Console](https://aws.amazon.com/console/) and click on 
[IAM](https://aws.amazon.com/iam/). After IAM is opened click on users in the left menu and add a new user and go through the following series of steps. 

- Add a user name.
- For access type mark both programmatic and console access.
- For password its upto you, going with auto generated or a custom password.
- For policies you can add custom policies also but for the sake of this tutorial we will give the user AdministratorAccess which is not recommended in a production environment. 
- After this click next and create the new user.

When the user is created, we will be presented with Access key ID and Secret Access key which will be needed to configure the AWS CLI, so save these keys in a safe manner.

Now that the user is created, the last part is to configure the AWS CLI that we installed in the last step.

Execute the following command in the terminal,

`aws configure`{{execute}}

After executing this we will be asked to enter some info. Enter the following info

- AWS Access key from the user we created
- AWS Secret key from the user we created
- For Default region enter 'eu-west-1' (without the quotes)
- For Default output format write 'yaml' (without the quotes)

And that is it, we have successfully configured AWS CLI with our AWS User. Now the fun part begins where we creete our first serverless application.

