For this tutorial we have successfully deployed and invoked our Serverless application and that was our main
goal from this session.

In this last step, we will just see the output from our CloudFormation service on AWS to see what happens when we run the `sls deploy` command.

Login to your AWS management console and search for CloudFormation and open it. In CloudFormation click on stacks.

Here is a screenshot from the CloudFormation and it should look similar for you.
![cloudformation](https://github.com/Abdullah1428/katacoda-scenarios/blob/main/assets/cloud-formation.png?raw=true)

From the image we can see that a bunch of resources and events were created for our stack during the deployment. Imagine if one is doing this when creating a simple application, this will definitely take a lot of time and will not be an easy task to do. Serverless takes responsibility for this and deploys our application very easily for us.

At the end if you want to remove your stack from AWS (meaning destroy your application) so that you don't have to pay for it anymore, just execute the command

`sls remove`{{execute}}

And this is it for our tutorial. Nice Job making it through all the way!.