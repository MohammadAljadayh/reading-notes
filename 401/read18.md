# AWS: S3 and Lambda

## Review, Research, and Discussion

### Describe “The Cloud”

Cloud computing is the on-demand availability of computer system resources, especially data storage and computing power, without direct active management by the user. Large clouds often have functions distributed over multiple locations, each location being a data cente

### What is a container (as it relates to computers and servers)?

Containerization is a system of intermodal freight transport using intermodal containers. The containers have standardized dimensions.

### What is auto-scaling?

Autoscaling, also spelled auto scaling or auto-scaling, and sometimes also called automatic scaling, is a method used in cloud computing that dynamically adjusts the amount of computational resources in a server farm - typically measured by the number of active servers - automatically based on the load on the farmg)

###  What is bandwidth?**

In computing, bandwidth is the maximum rate of data transfer across a given path. 

### How do cloud providers compute service costs?**

When setting price, cloud providers determine the expense to maintaining the network. They start by calculating costs for network hardware, network infrastructure maintenance, and labor. These expenses are added together and then divided by the number of rack units a business will need for its IaaS cloud

### Term Definition

`A server instance ` 
is a collection of SQL Server databases which are run by a solitary SQL Server service or instance. The details of each server instance can be viewed on the service console which can be web-based or command-line based


`Containers`   A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. 


`Cloud Services`   
 Cloud services are infrastructure, platforms, or software that are hosted by third-party providers and made available to users through the internet. ... Users can access cloud services with nothing more than a computer, operating system, and internet connectivity or virtual private network (VPN)

`Cloud Architecture`  
   refers to the various components in terms of databases, software capabilities, applications, etc. engineered to leverage the power of cloud resources to solve business problems. Cloud architecture defines the components as well as the relationships between them. 

`AWS`   
  Amazon Web Services (AWS) is a subsidiary of Amazon providing on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis ]


`EC2/Beanstalk vs Heroku`   
 Price ways, Beanstalk is better for large scale ongoing projects, and Heroku is better for small projects


# Preview
> Which 3 things had you heard about previously and now have better clarity on?
- bandwidth
- the cloud
- ACL 
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
- Aws
- Autoscaling
- OSI Model 
> What are you most excited about trying to implement or see how it works?
-  AWS 

---------------------------------------------------------------------
### Amazon S3
Object storage built to retrieve any amount of data from anywhere

- How it works
Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance. Customers of all sizes and industries can store and protect any amount of data for virtually any use case, such as data lakes, cloud-native applications, and mobile apps. With cost-effective storage classes and easy-to-use management features, you can optimize costs, organize data, and configure fine-tuned access controls to meet specific business, organizational, and compliance requirements.

![](https://d1.awsstatic.com/s3-pdp-redesign/product-page-diagram_Amazon-S3_HIW.cf4c2bd7aa02f1fe77be8aa120393993e08ac86d.png)


### AWS Lambda : 
 is a serverless computing service provided by Amazon Web Services (AWS). Users of AWS Lambda create functions, self-contained applications written in one of the supported languages and runtimes, and upload them to AWS Lambda, which executes those functions in an efficient and flexible manner.

 ### How does AWS Lambda work?
Each Lambda function runs in its own container. When a function is created, Lambda packages it into a new container and then executes that container on a multi-tenant cluster of machines managed by AWS. Before the functions start running, each function’s container is allocated its necessary RAM and CPU capacity. Once the functions finish running, the RAM allocated at the beginning is multiplied by the amount of time the function spent running. The customers then get charged based on the allocated memory and the amount of run time the function took to complete.  

![](https://d1.awsstatic.com/product-marketing/Lambda/Diagrams/product-page-diagram_Lambda-RealTimeFileProcessing.a59577de4b6471674a540b878b0b684e0249a18c.png)

-Use Amazon Simple Storage Service (Amazon S3) to trigger AWS Lambda data processing in real time after an upload, or connect to an existing Amazon EFS file system to enable massively parallel shared access for large-scale file processing.  


### Content Delivery Network (CDN) : 
A Content Delivery Network (CDN) is a geographically distributed group of servers that work together to provide fast delivery of Internet content. A CDN allows for the fast transfer of data needed for loading Internet content including HTML pages, javascript files, stylesheets, images, and videos

![](https://cyberhoot.com/wp-content/uploads/2020/03/What-is-Content-Delivery-Network-1024x647.jpg)