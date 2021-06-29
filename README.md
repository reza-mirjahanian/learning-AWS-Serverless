# practice1

### Fan-out pattern

Fan-out is a type of messaging pattern that’s familiar to many users of AWS. Generally,
the fan-out pattern is used to push a message out to all listening/subscribed clients of
a particular queue or a message pipeline. In AWS, this pattern is usually implemented
using SNS topics 


### Some Patterns for serverless
 Command pattern

 Messaging pattern

 Priority queue pattern

 Fan-out pattern

 Pipes and filters pattern

### Federation

Federation is another concept that’s discussed often in the context of roles. Federation 
is the process of creating a trust relationship between an external identity provider  such  as  Facebook,  Google,  or  an  enterprise  identity  system  that  supports
Security Assertion Markup Language (SAML) 2.0, and AWS.

### Permissions in AWS

Permissions in AWS are either identity-based or resource-based. Identity-based permissions specify what an IAM user ,or a role may do. Resource-based permissions specify
what an AWS resource, such as an S3 bucket or an SNS topic, is allowed to do or who
can have access to it
There are two types of policies: managed and inline. Managed policies apply to
users, groups, and roles but not to resources.

Inline policies are created and attached directly to a specific user, group, or role.
When an entity is deleted, the inline policies embedded within it are deleted also.
Resource-based policies are always inline

### Logging and alerting

CloudWatch is an AWS component for monitoring resources and services running on
AWS, setting alarms based on a wide range of metrics, and viewing statistics on the performance of your resources. 

### CloudTrail
CloudTrail is an AWS service that records API calls. It records information such as
the identity of the API caller, the source IP address, and the event. This data is saved in
a log file in an S3 bucket.  CloudTrail supports a number of
AWS services including CloudSearch, DynamoDB, Kinesis, API Gateway, and Lambda

### AWS CodePipeline
AWS CodePipeline automatically builds, tests and launches an application each time the code is changed; a developer uses a graphic user interface to model workflow configurations for the release process within the pipeline. A development team can specify and run actions or a group of actions, which is called a stage. For example, a developer would specify which tests CodePipeline will run and to which pre-production environments it should deploy. The service can then run these actions through the parallel execution process, in which multiple processors handle computing tasks simultaneously to accelerate workflows.

### AWS CodeCommit
(Bitbucket!),AWS CodeCommit is a secure, highly scalable, managed source control service that hosts private Git repositories. 

### AWS CodeDeploy
AWS CodeDeploy is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises serve
An application specification file (AppSpec file), which is unique to CodeDeploy, is a YAML-formatted or JSON-formatted file. The AppSpec file is used to manage each deployment as a series of lifecycle event hooks, which are defined in the file.

### Blue/Green Strategy
The blue/green deployment strategy creates two independent infrastructure environments. The blue environment contains the previous code or configuration, while the green environment contains the newest code or configurations. Traffic is then shifted to the newest environment (green) and diverted away from the previous environment (blue) by redirecting the DNS record to green's load balancer using Route 53.

### Amazon ECR
Amazon Elastic Container Registry (ECR) is a fully managed container registry that makes it easy to store, manage, share, and deploy your container images and artifacts anywhere. Amazon ECR eliminates the need to operate your own container repositories or worry about scaling the underlying infrastructure. Amazon ECR hosts your images in a highly available and high-performance architecture, allowing you to reliably deploy images for your container applications.

### AWS CloudFormation 
AWS CloudFormation gives you an easy way to model a collection of related AWS and third-party resources, provision them quickly and consistently, and manage them throughout their lifecycles, by treating infrastructure as code. A CloudFormation template describes your desired resources and their dependencies 



