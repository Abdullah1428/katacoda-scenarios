Now the final step is to deploy this application and see it in action.

To deploy the application, we will use serverless framework command and as we already have configured
AWS CLI with our AWS User, we will not be needing to do the step of configuring serverless framework with AWS credentials.

To deploy the application execute the following command,

`sls deploy -v`{{execute}}

In the above command "-v" stands for verbose which will give us some nice detailed information about this deployment as this is deployed by the [AWS CloudFormation](https://aws.amazon.com/cloudformation/)

After a successfull deployment we can see some information about our service at the end. We also get an endpoint for the serivce which is an url that can be run in a browser and we get the response back from the hanlder.