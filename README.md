# Interview-Experience
# 1- What are java 8 features explain optional, lambda, stream?
 Ans-

# 2- How optional is beneficial?
 Ans-

# 3- How lambda function works?
 Ans-

# 4- What is stream api?
 Ans-

# 5- Write expression to get employee name through stream api?
 Ans-

# 6- How do handle exceptions?
 Ans-
 
# 7- Builtin functional interfaces?
Ans-

# 8- Write lambda expression to filter the objects?
Ans-

# 9- Write lambda expression for map intermediate method use.
Ans - 

# 10 -Predicates
Ans-

# 11- What is parallel Stream, where to use it, write lambda expressions for it.
Ans-

# 12- How stream actually works?
Ans-

# 13 - Stream’s common method and some common stream problems?
Ans-

# 14 - Builder, Singleton, proxy, adapter design pattern
Ans-


# Miseleneous-

List of questions asked in the interview with the correct answer.

##Java
Singleton pattern, how to make it. (wanted to know the constructor way with synchronized).
Difference between volatile and synchronization.

##Spring
how to configure or make changes in data source (in terms of programmatically)
data sources worked on other than mysql
What is Hibernate
What is AOP.
AWS SDK configuration in spring boot
Main use for why I configured SDK. (S3). Follow up: have you configured S3 or just used it.
How to make any header change or request change in spring boot (Spring Filters)
how to register filters
Zuul, how it works (have written in my CV)

##Maven:
Lifecycle
maven profiles
exclude classes in library

##Testing
Junit, how testing is done
Mockito, how to mock services, and how to mock if no bean is there of that class
What is TDD and BDD

##Other
Past project, what were you responsible for etc.
Any experience with Azure SDK
Any experience with Kubernetes.
Any experience with logging tools. (worked with ELK stack, so told a bit about that, AWS CloudWatch would also be a good answer)

##Java
java 8 features: optional, lambda, stream
how optional is beneficial
how lambda function works
stream api
write expression to get employee name through stream api
exception handling
##Spring
what makes java app a spring boot app.
spring boot common modules
how to connect aws sdk to spring boot
spring security, how it works
how to make controller
difference between @Controller and @RestController
how to integrate jpa
how to use JPA
most common annotations used in spring boot
redis - how it works with spring boot

##Cloud
name few AWS cloud technologies
CloudFront, how it works
S3 bucket policies

##Others
work history
what is conditional debugging
what is step over and step into
how to do remote debugging.
national ID card to show them.


##java
Main features of java 8 and where you have used
What is lambda expression
Builtin functional interfaces
Write lambda expression to filter the objects
Write lambda expression for map intermediate method use.
Predicates
What is parallel Stream, where to use it, write lambda expressions for it.

##Spring
What is the difference between Spring MVC and Spring boot
Name common modules in Spring boot
How we create spring project
How do you write REST API
How to configure JPA in spring boot
Explain how to create a repository and run jpa queries on entities.
Difference btw PUT and PATCH
What is CORS
Authorization and Authentication
Exception handling in spring boot
Spring Boot annotations
Others
How to debug and evaluate expression
Any previous project architecture
Work history, type of project I did.
How you deploy the application


##Java
Main feature of Java 8
What is lambda expression
Builtin functional interfaces
Design Patterns
Builder, Singleton, proxy, adapter design pattern
A simple java based program to write. 
What is Stream
How stream actually works
Stream’s common method and some common stream problems
	
##Spring
What is the difference between Spring and Spring boot
Name common modules in Spring boot
How we create spring project
@Profile @SpringBootApplicaiton Annotation
Dependency injection with same type of bean
Different scopes of projects. 
Interceptors and request filter in Spring
Authorization in Spring. 
Spring Security. 
What is Aspect

	
##Others
Builder, Singleton, proxy, adapter design pattern
Eclipse Vs IntelliJ
Name some challenging project
Maven profile
How to debug and evaluate expression
How to debug on an application running remotely
Work history, type of project I did.



##Devops Terraform
Environment setup
Modules
Explain a list variable (containing subnets) and a resource using count to create ec2 instances using an AMI, instance type and subnet from the list (displayed on screen share).
Explain a resource using for key word with a toset(list) (displayed on screen share)
What is the toset() function used for?
Explain a policy being defined using a Heredoc string, what does the policy do? (displayed on screen share)
Explain an assume role policy (displayed on screen share)

##AWS
What are the resources used to control access?
How can we control access between two EC2 instances?
Two EC2 instances are in the same subnet, how can we control access?
How can we control access to EC2 as a web server with traffic coming from the internet, how can we control access?
NACL vs Security groups
How can we protect a public facing infrastructure from DoS or DDoS attack?
How can two EC2 instances in two separate private subnets in two separate VPC connect to each other?
What is TLS with typical use cases?
How are certificates verified by the client?
##TODO
Terraform - [Mar 3rd, 2023]
Dynamic
Linting / formatting 
Pre-commit checks (Github)
Python - programming tasks - [Mar 7, 2023]
AWS - [Mar 9, 2023]
Security services
DR / HA


##General
Brief description of current project, have you used modules, did you set-up the environment?
Differentiate python list and set, which will have better performance?

##Terraform
Steps to setup new terraform environment (directory structure, providers, backend)
What is a backend, what is it used for?
How to set-up a project with multiple environments? (dev, UAT, pre-prod and prod etc)
How to setup common modules for multi-environment
Explain a list variable (containing subnets) and a resource using count to create ec2 instances using an AMI, instance type and subnet from the list (displayed on screen share).
What will the output of a resource using count look like? (using [] brackets and 0 based index)
Explain a resource using for key word with a toset(list) (displayed on screen share)
What is the toset() function used for?
Explain a policy being defined using a Heredoc string, what does the policy do? (displayed on screen share)
Explain an assume role policy (displayed on screen share)
Give examples of common blocks (Ans: e.g. provider, module, data, variable, output etc)
What is a data block used for?
Is it possible to share resources between two different AWS accounts?

##AWS
What are the resources used to control access?
How can we control access between two EC2 instances?
Two EC2 instances are in the same subnet, how can we control access?
How can we control access to EC2 as a web server with traffic coming from the internet, how can we control access?
How are rules configured to control access
Do we need outbound rules for NACLs?
What port will be used to allow outbound traffic of a web server?
How do we configure access to EC2 instances running the same service? (Ans: Load Balancer)
What are the types of load balancers?
What layer does ELB work on, and how does it decide to route traffic?
What layer does ALB work on, and how does it decide to route traffic?
How can we protect a public facing infrastructure from DoS or DDoS attack?
How can we design a highly available infrastructure for EC2?
How many subnets will be required for HA EC2 infrastructure?
Is it possible to allow access to a specific S3 bucket from an instance in a private subnet? How?
How can two EC2 instances in two separate private subnets in two separate VPC connect to each other?
What are private endpoints?
Differentiate Interface and Gateway VPC Endpoints
What is TLS with typical use cases?
How are certificates verified by the client?
How to apply patches on EC2?
What other tools can be used to maintain and patch devops resources?

ALB / NLB / ACM [March 6, 2023]
End-end TLS [March 2, 2023]
CodePipeline (CICD) [March 3, 2023]

##(DevOps) Terraform
Environment setup
State file
Backend / Locking
Modules
What to do if resource already exists and you try creating it from Terraform
AWS
HA for EC2s
HA for RDS
ALB / ELB
HTTPS with ALB
End-end HTTPS from Client to ALB to EC2
Difference between Interface and Gateway VPC Endpoints
Lambda Code Deployments
Lambda Configuratios / Lambda Handler
How to apply patch on EC2
How to rollout the change in Prod
TODO
Python [ETA: 8 March]
AWS
VPC Peering & Transit Gateway [ETA: 6 March]
Service Discovery - CloudMap [ETA: 7 March]
DR [ETA: 9 March]

##(DevOps)Terraform
Environment setup
Providers
State file
Backend / Locking
Modules
What to do if resource already exists and you try creating it from Terraform

##AWS
Three-Tier architecture and end-to-end traffic flow from endpoint to service
AWS Security best practices (least privilege permissions)
HA for EC2s
HA for RDS
ALB / ELB
HTTPS with ALB
IAM Roles, Policies, Permission Boundary, Group
Difference between Interface and Gateway VPC Endpoints
Lambda Serverless Architecture
Deployment Strategy
How to apply patch on EC2
How to rollout the change in Prod
TODO
Python (8-Mar-23)
AWS (9-Mar-23)
Well Architected Review
DR
Security Standards


##(Python)
AWS + Infrastructure
How to access EC2 from a Lambda?
Explain S3 Policy?
What are other options for security then IAM?
How are SSL certificates generated?
Where is the SSL certificate being stored?
How are SSL certificates being used with NLB?
HTTPS and ALB
ALB, NLB and ELB
Jenkins + Code Pipeline
Python
Iterators vs generators
Json load vs loads
Data structure
How to implement security of a Python script
Unit Tests
Integration Tests
TODO



##(DB)
Do you know about Redis?
Azure MySQL installation?
Risk/Challenges may face in Azure Vs AWS?
Which is the preferred DB between MYSQL and MS SQL SERVER?
How to tackle Performance post migration?
What are the migration steps?
How does AWS Migration using AWS SCT and DMS work?
Comparative difference betweenHomogeneous and Heterogeneous Migration implementation?
How will users be moved to Target DB?
What kind of migration have you performed Bulk Loading vs CDC?
Any tools used in Migration?
Have you performed On-Prem to Cloud Migration?
Have you performed MYSQL replication?
Will you perform SCT before migration?
What are the key parameters/ components in  DMS?
TODO
Azure to AWS MYSQL DB Migration			ETA: 06-Mar-2023
Redis 							ETA: 06-Mar-2023
AWS DB - Aurora					ETA: 07-09-Mar-2023
Cross region/account replication		
Aurora Security standards
Comparison with RDS
Pricing



##AWS
End-End TLS (ACM, {letsencrypt}) [March 6th 2023]
VPC Peering & Transit Gateway [March 7th 2023]
Comparison between these.
Cross Account/Region Deployments (CodePipeline) [March 8th 2023]
Service Discovery - CloudMap [March 9th 2023]
