Let's get to the interesting and fun part now. 
In this step We will create our first Serverless Application.

Serverless Framework provides us with a rich amount of [templates](https://www.serverless.com/framework/docs/providers/aws/cli-reference/create) for whatever needs we have. These templates helps to get you up running with a project very quickly.

For this tutoiral, we will use an open source template which uses latest version of javascript and webpack to create a Serverless Node.js Application.

We will generate the application scaffolding, which will in turn generate an AWS Lambda function in Node.js. Execute the following command.

`sls create --name demo --template-url https://github.com/Abdullah1428/serverless-base-template`{{execute}}

The next step is to install the dependencies for this template. Execute the following command which will install all the dependencies required for this template.

`cd demo`{{execute}}

`npm install`{{execute}}

Let's talk about the structure of this project

`cd demo && ls`{{execute}}

We see `serverless.yml` file. This file is the heart of our serverless application written in YAML where you define your Functions, the Events that trigger them, and the Resources your Functions use.

We see `package.json` file which contains all the dependencies for this template.

We see `src` directory which contains another directory named `hanlders` and inside that we have `hello.js` hanlder which is an application language specific file and since we are creating a Node.js application, we have a JS file with our function defined here.

Okay, so we have our boilerplate code and from this point on you can edit this code according to your application need.

In the next step, we will go through the final setup which is deploying this application to AWS and running this on AWS Lambda.
