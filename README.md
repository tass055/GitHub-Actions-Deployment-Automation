The workflowshave been manifested for any node.js application, they are designed to work with 3 environments, QA, Stage, prod. 
This is designed to deploy to aws environment consisting of an S3 bucket, a cloudfront and their keys, i.e the architecture for a microfrontend
Since S3 is used here we would to have it with versioning enabled so that it can be used a version control medium for our deployment additionally a secodn approac has also been implemented for the same whic involves a branch creation whenever a Pr is opened to master. This branch can later be used to revert to previous code version as well 
Prod deploy strategy is release of a publish
QA is managed with develop branch and staging is managed with stage branch
