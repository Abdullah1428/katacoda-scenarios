## Serverless Framework: Do more with less, Serverless

Welcome to this tutorial on *Serverless Framework*! which is all-in-one development & monitoring of auto-scaling apps on AWS Lambda.

## What will we learn

- A little background on Serverless Computing/Architecture and Serverless Framework
- Install the Serverless Framework
- Install AWS CLI and configure the AWS credentials
- Build our first NodeJS Serverless application using templates from Serverless Framework
- Deploy and Run our application on AWS Lambda

## What is Serverless Computing/Architecture?
Serverless computing is a cloud computing execution model in which the cloud provider allocates machine resources on demand, taking care of the servers on behalf of their customers. "Serverless" is a misnomer in the sense that servers are still used by cloud service providers to execute code for developers.

Serverless architecture is an approach to software design that allows developers to build and run services without having to manage the underlying infrastructure. Developers can write and deploy code, while a cloud provider provisions servers to run their applications, databases, and storage systems at any scale.

One of the most popular serverless architectures is Function as a Service (FaaS), where developers write their application code as a set of discrete functions. Each function will perform a specific task when triggered by an event, such as an incoming email or an HTTP request. After the customary stages of testing, developers then deploy their functions, along with their triggers, to a cloud provider account. When a function is invoked, the cloud provider either executes the function on a running server, or, if there is no server currently running, it spins up a new server to execute the function. This execution process is abstracted away from the view of developers, who focus on writing and deploying the application code.

Example use case for Serverless Architecture
![serverless](https://github.com/Abdullah1428/katacoda-scenarios/blob/main/assets/serverless.png?raw=true)