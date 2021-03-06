# Amazon EC2

### AMIs
Preconfigured templates for your instances, known as Amazon Machine Images (AMIs), that package the bits you need for your server (including the operating system and additional software)

### Amazon EBS
Persistent storage volumes for your data using Amazon Elastic Block Store (Amazon EBS), known as Amazon EBS volumes

### Elastic IP addresses
Static IPv4 addresses for dynamic cloud computing, known as Elastic IP addresses

### VPCs
Virtual networks you can create that are logically isolated from the rest of the AWS Cloud, and that you can optionally connect to your own network, known as virtual private clouds (VPCs)

### Pricing for Amazon EC2

#### On-Demand Instances
Pay for the instances that you use by the second, with no long-term commitments or upfront payments.

#### Savings Plans
You can reduce your Amazon EC2 costs by making a commitment to a consistent amount of usage, in USD per hour, for a term of 1 or 3 years.

#### Reserved Instances
You can reduce your Amazon EC2 costs by making a commitment to a specific instance configuration, including instance type and Region, for a term of 1 or 3 years.

#### Spot Instances
Request unused EC2 instances, which can reduce your Amazon EC2 costs significantly.

### Amazon Machine Images (AMI)
An Amazon Machine Image (AMI) provides the information required to launch an instance. You must specify an AMI when you launch an instance. 

All AMIs are categorized as either backed by Amazon EBS or backed by instance store.

### Amazon Accelerated computing
Accelerated computing instances use hardware accelerators, or co-processors, to perform some functions, such as floating point number calculations, graphics processing, or data pattern matching, more efficiently than is possible in software running on CPUs.

### AWS Compute Optimizer
AWS Compute Optimizer provides Amazon EC2 instance recommendations to help you improve performance, save money, or both. You can use these recommendations to decide whether to move to a new instance type.

### Amazon Elastic Inference
Amazon Elastic Inference (EI) is a resource you can attach to your Amazon EC2 CPU instances to accelerate your deep learning (DL) inference workload
Amazon EI distributes model operations defined by TensorFlow, Apache MXNet, and the Open Neural Network Exchange (ONNX)


### EC2 Fleet
An EC2 Fleet contains the configuration information to launch a fleet???or group???of instances. In a single API call, a fleet can launch multiple instance types across multiple Availability Zones

### Spot instances [Reduce cost]
Amazon EC2 Spot Instances let you take advantage of unused EC2 capacity in the AWS cloud. Spot Instances are available at up to a 90% discount compared to On-Demand prices. You can use Spot Instances for various stateless, fault-tolerant, or flexible applications such as big data, containerized workloads, CI/CD, web servers, high-performance computing (HPC), and test & development workloads. Because Spot Instances are tightly integrated with AWS services such as Auto Scaling, EMR, ECS, CloudFormation, Data Pipeline and AWS Batch, you can choose how to launch and maintain your applications running on Spot Instances.
reliability is not guaranteed, and the cloud provider can interrupt these instances at short notice to reclaim capacity.
Amazon gives you 2 minutes, Azure and Google only 30 seconds.

### Automated monitoring tools
#### System status checks 
#### Instance status checks
#### Amazon CloudWatch alarms 
#### Amazon EventBridge
automate your AWS services and respond automatically to system events. 
#### Amazon CloudWatch Logs
#### CloudWatch agent 
collect logs and system-level metrics from both hosts and guests on your EC2 instances and on-premises servers.

### Placement groups
#### Cluster 
#### Spread
#### Partition 

###  instance store
An instance store provides temporary block-level storage for your instance. This storage is located on disks that are physically attached to the host computer. Instance store is ideal for temporary storage of information that changes frequently, such as buffers, caches, scratch data, and other temporary content, or for data that is replicated across a fleet of instances, such as a load-balanced pool of web servers.

### Amazon EFS
Amazon Elastic File System (Amazon EFS) provides a simple, serverless, set-and-forget, elastic file system that lets you share file data without provisioning or managing storage. 
