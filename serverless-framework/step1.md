After the background about Serverless the first step is now to install the Serverless Framework.
In order to be able to install Serverless Framework we will first make sure that 
Node.js and NPM is configured in the environment.

`node --version`{{execute}}

`npm --version`{{execute}}

Now to install the Serverless Framework, execute the command in the work environment.

`npm install serverless -g`{{execute}}

This will install the serverless framework as an NPM module globally.

Now, let's check if Serverless was installed correctly.

`npm list -g | grep serverless`{{execute}}

Let's check the version of Serverless that was installed.

`serverless --version`{{execute}}

We can see that we have it installed and are good to go.

Now, that we have the Serverless Framework installed, we can go ahead and install AWS CLI and configure our AWS Credentials.
