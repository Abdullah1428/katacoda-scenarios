## Serverless Framework: Do more with less, Serverless

Welcome to this tutorial on *Serverless Framework*! which is all-in-one development & monitoring of auto-scaling apps on AWS Lambda.

## What will we learn

- A little background on Serverless Computing/Architecture and Serverless Framework.
- Install the Serverless Framework.
- Install AWS CLI and configure the AWS credentials.
- Build our first NodeJS Serverless application using templates from Serverless Framework.
- Deploy and Run our application on AWS Lambda.

## What is Serverless Computing/Architecture?
Serverless computing is a cloud computing execution model in which the cloud provider allocates machine resources on demand, taking care of the servers on behalf of their customers. "Serverless" is a misnomer in the sense that servers are still used by cloud service providers to execute code for developers.

Serverless architecture is an approach to software design that allows developers to build and run services without having to manage the underlying infrastructure. Developers can write and deploy code, while a cloud provider provisions servers to run their applications, databases, and storage systems at any scale.

One of the most popular serverless architectures is Function as a Service (FaaS), where developers write their application code as a set of discrete functions. Each function will perform a specific task when triggered by an event, such as an incoming email or an HTTP request. After the customary stages of testing, developers then deploy their functions, along with their triggers, to a cloud provider account. When a function is invoked, the cloud provider either executes the function on a running server, or, if there is no server currently running, it spins up a new server to execute the function. This execution process is abstracted away from the view of developers, who focus on writing and deploying the application code.

Example use case for Serverless Architecture
![serverless](https://github.com/Abdullah1428/katacoda-scenarios/blob/main/assets/serverless.png?raw=true)

## Some Benefits and Challenges of Serverless Architecture

### Benefits
- Cost Effective as Cloud providers charge you on per invocation basis.
- Scalability as Function instances are automatically created or removed in response to traffic variations.
- Productivity as Engineers who use serverless can simply deploy their code without having to manage any servers, which helps accelerate delivery cycles and rapidly scale company operations.

### Challenges
- Loss of Control as In serverless environments, you lack control over the software stack that your code runs on.
- Security (always a concern)
- Performance Impact as cold starts are common in serverless environments, adding several seconds of latency to code execution when functions are invoked after a period of inactivity.
- Testing as developers can run unit tests on function code, but integration tests, which evaluate how frontend and backend components interact, are difficult to perform in a serverless environment.

## Now What is Serverless Framework?
The Serverless Framework says on their website "Develop, deploy, troubleshoot and secure your serverless applications with radically less overhead and cost by using the Serverless Framework. The Serverless Framework consists of an open source CLI and a hosted dashboard. Together, they provide you with full serverless application lifecycle management".

With Serverless Framework one can easily
- Easily define applications as functions and events.
- Deploy infrastructure and code with a single command.
- Extend your use-cases and workflow with Plugins.
- Troubleshooting with Top-tier debugging tools, built right in.
- Query and inspect every request.
- Collaborate, share and contribute across your entire team.
- Manage everything in one place.

Go Serverless. Deploy the use-cases you love, on auto-scaling infra.
You can deploy many familiar use-cases instantly with the Serverless Framework. From REST APIs on Node.js, Python, Go, Java, to GraphQL APIs, scheduled tasks, Express.js applications, and front-end applications.

## What prior experience & tools are required?
This tutorial is intended for beginners new to serverless computing. We will install the tools step by step but
you will need to signup for AWS account in order to complete this tutorial. AWS provides one year of free trial
so no real money will be charged during this tutorial [AWS-Account](https://portal.aws.amazon.com/billing/signup#/start/email). 

To give yourself an edge, one can read more about serverless framework [here](https://www.serverless.com/). 

By [Abdullah](https://github.com/Abdullah1428) & [Aksel Uhr](https://github.com/Akseluhr)