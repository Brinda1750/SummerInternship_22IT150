# SummerInternship_22IT150# 🌟 AWS Summer Internship 2024 - Project Showcase 🌟

Welcome to my GitHub repository for the AWS Summer Internship 2024! This project showcases the work done during the internship, including practical insights and hands-on experience with Amazon Web Services (AWS).

## 🚀 Introduction

### *25th May 2024*
- **AWS Bootcamp Live Session**: Basics of Amazon Web Services
  - On 25th May, Amit Arora (Security Architect at AWS) conducted a live bootcamp for an AWS Club where entry-level engineers participated to build their AWS skills from the ground up. This session provided a foundational understanding of AWS and its various functionalities for developers. 
  - The internship spans 4 weeks, focusing on labs and practical insights to familiarize us with AWS.

## Start of Internship

## 1️⃣ Week 1
### *28th May 2024*
- **Orientation Meeting**: Introduction to AWS and overview of the internship tasks
  - The meeting began with a Q&A session to establish a foundational understanding of AWS. The tasks for the first week, including account creation and portfolio generation hosted on an AWS instance, were discussed.

<img src="https://media.licdn.com/dms/image/C4E22AQHZqrKVMi6FOw/feedshare-shrink_2048_1536/0/1666809813685?e=1723075200&v=beta&t=p5q0SSwNpNf4moUF9QJ1M4GloydKL8bm-zCtff0Mxo4" alt="AWS Bootcamp" width="350"/>


### Week 1 Outline:

1. Create an AWS Free Tier account
2. Log on to the AWS Console
3. AWS Billing and Cost Management
4. Set up a zero-dollar limit budget
5. Launch an EC2 Instance
6. Connect to the EC2 Instance
7. Install Apache Web Server on the Linux Instance
8. Deploy a personal `page.html` on Apache
9. Open Security Group for Apache to accept connections on port 80
10. Access the `page.html` using the public IP address of the EC2 instance

## 📝 Day-by-Day Progress

### Day 1: Creating AWS Free Tier Account
- Created an AWS Free Tier account.
- Logged on to the AWS Console.
- Explored AWS Billing and Cost Management.
- Set up a zero-dollar limit budget.
- Launched an EC2 instance from the free tier options.

### Day 2: Creating Instance with Apache Server to Deploy Web Page
- **Connected to the EC2 Instance**:
  - Connected to the instance using SSH, establishing a secure connection with the provided key pair.

- **Commands**:
  - `shell`: to write commands
  - `pwd`: current web directory
  - `whoami`: current logged-in user

- **Installed Apache Web Server on the Linux Instance**:
  - Installed Apache to serve web pages.

- **Commands**:
  - `sudo su`: elevate credentials to root
  - `yum install -y httpd`: install Apache web server (Linux server)
  - `cd /var/www/html`: navigate to the HTML directory

- **Deployed a Personal `page.html` on Apache**:
  - Deployed a simple HTML page in Apache’s root directory, making it accessible via the instance's public IP address.(http://3.26.149.37/personalpage.html)

### Day 3: Building the Portfolio
- **Setting Up the Project Structure**:
  - Created a project directory with folders for HTML, CSS, JavaScript, and assets.
  - Initialized the project with a basic `index.html` file.

- **Creating the HTML Structure**:
  - Developed the portfolio structure using HTML5, including sections for the header, about me, projects, and contact information.

- **Integrating Bootstrap**:
  - Used Bootstrap for a responsive and modern design. Utilized components like navigation bars, cards, and buttons.

### Day 4: Enhancing with JavaScript, SASS, and CSS
- **Adding Interactivity with JavaScript**:
  - Implemented interactive features like form validation and dynamic content loading.

- **Styling with SASS and CSS**:
  - Used SASS for more maintainable and modular CSS. Compiled SASS files into CSS and applied custom styles.

- **Finalizing the Deployment**:
  - Ensured all files were correctly linked and the website was functioning. Tested on different browsers and devices.

### Day 5: Configuration and Final Touch-Up
- Configured the Security Group for the Apache server to accept connections on port 80.
- Verified the configuration by accessing the personal webpage via the EC2 instance's public IP address.

- **Finalized Link**: [Personal Page](http://3.26.149.37/personalpage.html)

## Notes:
- **Helpful Repo**: [AWS Services Documentation](https://github.com/hamidgholami/accp-cheatsheet)


## 2️⃣ Week 2
### *4th June 2024*
- **Online Session**: Learning about storage and S3 with its related services, transitioning from EC2 to S3
  - The session began with rapid questions regarding Week 1 tasks.

![AWS Cloudfront](https://d2908q01vomqb2.cloudfront.net/da4b9237bacccdf19c0760cab7aec4a8359010b0/2023/02/22/AWS-Pi-Day-2023-Video-small-2.gif)

### Week 2 Outline:

1. Create a Bucket
2. Make it private
3. Upload files
4. Encrypt the files
5. Create a Distribution
6. Integrate it with S3
7. Create a new KMS Key
8. Change the Default Key for your bucket to this new key
9. Find out these events and logs for them in CloudTrail
10. Shutdown the EC2 instance created in Week 1

## 📝 Day-by-Day Progress

### Day 1: Creating and Configuring an S3 Bucket
➠ Created a new S3 bucket:
- I started by creating a new Amazon S3 bucket. Amazon S3 is a scalable object storage service that allows for the storage and retrieval of any amount of data at any time.
 
➠ Set the bucket's permissions to private:
- Ensured the bucket's security by setting its permissions to private, making sure that only authorized users have access to the stored data.
  
➠ Uploaded files to the bucket:
- Uploaded various files to the S3 bucket to test storage and retrieval capabilities. This provided hands-on experience with S3's upload functionalities and permissions settings.

### Day 2: Securing and Distributing Content
➠ *Enabled encryption for the uploaded files*:
  - To enhance data security, I enabled server-side encryption for the files uploaded to the S3 bucket. This ensures that data is encrypted at rest, protecting it from unauthorized access.
    
➠ *Created a CloudFront distribution and integrated it with the S3 bucket*:
  - Created an Amazon CloudFront distribution to deliver content stored in the S3 bucket with low latency and high transfer speeds. This involved setting up the distribution and linking it to the S3 bucket, demonstrating how CloudFront can improve content delivery performance.

- CDN(Content Delivery Network) --

<img src="https://delante.co/wp-content/uploads/2019/11/cdn-definicja-2.png" width="400" height="200"/>

### Day 3: Advanced Security and Monitoring
- **Created a new KMS key**:
  - Managed encryption keys using AWS KMS.

- **Changed the default encryption key for the S3 bucket to the new KMS key**:
  - Ensured future objects are encrypted with the KMS key.

- **Used CloudTrail to track events and logs**:
  - Monitored and logged activities for compliance and security analysis.

- **Shut down the EC2 instance created in Week 1**:
  - Optimized resource usage and avoided unnecessary charges.

### Day 4-5: Exploring New AWS Services
- Explored AWS Athena's Capabilities**:
  - Investigated SQL queries, data partitioning, and AWS Glue Data Catalog integration.

- **Explored Data Integration and Orchestration**:
  - Researched AWS Glue's ETL features and AWS Step Functions' orchestration capabilities.

### Day 4: Unveiling AWS Athena's Capabilities
- **Explored the flexibility of SQL queries in AWS Athena**:
   - Delved into the diverse SQL queries that can be executed in AWS Athena, understanding its interaction with data stored in S3 and the various types of 
      analyses that can be conducted.
     
- **Analyzed data partitioning techniques**:
  - Investigated different data partitioning techniques and their impact on query efficiency in Athena, gaining insights into how partitioning can lead to cost 
    savings.
    
- **Studied AWS Glue Data Catalog integration**:
  - Examined how AWS Glue Data Catalog acts as a centralized metadata repository and its integration with Athena to facilitate easy searching and querying of S3 
    data.

### Day 5: Diving into Data Integration and Orchestration
- **Explored AWS Glue's ETL capabilities**:
  - Researched AWS Glue's ETL functionalities, understanding how it automates data extraction, transformation, and loading for analytical purposes.
    
- **Learned about AWS Step Functions' orchestration**:
  - Acquired knowledge about AWS Step Functions and its ability to orchestrate multiple AWS services into serverless workflows, understanding the basics of 
    service orchestration.
- **Reviewed error handling in Step Functions workflows**:
  - Investigated best practices for implementing error handling in Step Functions workflows, appreciating the significance of resilience in service orchestration.


## 3️⃣ Week 3
### *12th June 2024*
- **Online Session**: Introduction to AWS DynamoDB, API Gateway, and Lambda Functions
  - Focused on building a serverless backend using AWS services like DynamoDB, API Gateway, and Lambda Functions. Worked on creating CRUD APIs for managing items in a DynamoDB table.

<img src="https://miro.medium.com/v2/resize:fit:828/1*azZXECXc2CKfdAvet92bLA.gif" height="400"/>

### Week 3 Outline:

1. Create a table in DynamoDB
2. Write a Lambda Function as a Backend
3. Configure API Endpoints on API Gateway
4. Get /items
5. Put /items
6. Get /items/{id}
7. Delete /items/{id}
8. Configure API Endpoints with Lambda Code
9. Test Out APIs through Curl and Browser

## 📝 Day-by-Day Progress

### Day 1: Creating a Table in DynamoDB
- **Created a table in DynamoDB**:
  - Configured the table with a primary key and necessary attributes.

### Day 2: Writing Lambda Functions
- **Wrote a Lambda Function as a Backend**:
  - Developed a Lambda function in Python to interact with DynamoDB for CRUD operations.

### Day 3: Configuring API Endpoints
- **Configured API Endpoints on API Gateway**:
  - Set up API Gateway to expose Lambda functions as RESTful API endpoints.

### Day 4: Implementing CRUD Operations
- **Building the Get All Endpoint (GET /items)**:  
  - I configured an API endpoint that retrieves all items stored in our DynamoDB table. When a user sends a GET request to this endpoint, the Lambda function 
    kicks in, fetches all the items, and returns them in the response.

- **Building the Create Item Endpoint (PUT /items)**: 
  - Next, I created an endpoint that allows users to add new items to the DynamoDB table.  This endpoint interacts with the Lambda function, which processes the 
    incoming request and inserts the new item into the table.

- **Building the Get Item Endpoint (GET /items/{id})**: 
  - I then implemented an endpoint that retrieves a specific item based on its unique ID.  The Lambda function uses the ID parameter to query DynamoDB and return 
    the requested item.

- **Building the Delete Item Endpoint (DELETE /items/{id})**: 
  - Finally, I configured an endpoint for deleting items from the DynamoDB table. The Lambda function handles the deletion process and ensures the item is removed 
    based on the provided ID.
    
- **Configure API Endpoints with Lambda Code**:
- Linked the API Gateway endpoints with the corresponding Lambda functions. This integration allows API Gateway to invoke the correct Lambda function for each API request, ensuring the backend logic is executed properly.

- **Test Out APIs through Curl and Browser**:
- Tested the configured APIs using curl commands and a web browser to ensure they work as expected. Verified that the CRUD operations (Create, Read, Update, Delete) perform correctly and that the APIs return the appropriate responses for different scenarios.


## 4️⃣ week 4

### *21st June 2024*
- **Online Session**: Introduction to AWS Bedrock, S3, and Knowledge Base Integration
  - This week focused on building a knowledge base using AWS Bedrock, creating a vector store for efficient data retrieval, and interacting with the knowledge base using an agent.

  <img src="https://community.aws/_next/image?url=https%3A%2F%2Fassets.community.aws%2Fa%2F2Z6yg51zfyrwr7WzyFJ4zNsUukb.png%3FimgSize%3D2772x1102&w=3840&q=75" width="550" height="300"/>

### *Here is the Outline of Week-4:*
1. Create a Bucket
2. Upload my Resume
3. Create Knowledge Base in BedRock
4. Link S3 Bucket Object (Resume) with this Knowledge Base
5. Create Vector Store using Embeddings and Data Source
6. Test Knowledge Base using Generate Responses
7. Test Knowledge Base without using Generate Responses
8. Create an Agent
9. Connect it with Knowledge Base
10. Interact with your Resume

## 📝 Day-by-Day Progress

### Day 1: Setting Up the S3 Bucket and Uploading Resume
- **Create a Bucket**:
  - Created a new S3 bucket for storing objects. Amazon S3 is a scalable object storage service that allows for the storage and retrieval of any amount of data at any time.

- **Upload my Resume**:
  - Uploaded my resume to the S3 bucket. This step is crucial for linking the resume to the knowledge base in Bedrock.

### Day 2: Creating and Linking Knowledge Base in Bedrock
- **Create Knowledge Base in BedRock**:
  - Created a knowledge base in AWS Bedrock. Bedrock is used for building intelligent applications with comprehensive knowledge management and natural language understanding capabilities.

- **Link S3 Bucket Object (Resume) with this Knowledge Base**:
  - Linked the uploaded resume from the S3 bucket to the knowledge base. This allows Bedrock to use the resume as a data source for generating responses.

### Day 3: Building and Testing the Vector Store
- **Create Vector Store using Embeddings and Data Source**:
  - Created a vector store using embeddings to enable efficient data retrieval. This involved transforming the resume data into vector embeddings that Bedrock can use for quick search and retrieval.

- **Test Knowledge Base using Generate Responses**:
  - Tested the knowledge base by generating responses from the linked resume data. This helped verify that the knowledge base correctly understands and retrieves information from the resume.

- **Test Knowledge Base without using Generate Responses**:
  - Conducted tests on the knowledge base without using the generate response feature to ensure it can handle direct queries and return accurate information.

### Day 4: Creating and Connecting an Agent
- **Create an Agent**:
  - Created an agent in AWS Bedrock. Agents in Bedrock are responsible for interacting with users and providing responses based on the knowledge base.

- **Connect it with Knowledge Base**:
  - Linked the created agent with the knowledge base to enable it to access and retrieve information from the resume stored in S3.

### Day 5: Interacting with the Resume
- **Interact with your Resume**:
  - Interacted with the resume through the agent. This involved querying the agent to retrieve specific information from the resume, ensuring the setup was functional and effective.

### Technologies Explored
- **S3**: For storing and managing resume data.
- **Bedrock**: For creating a knowledge base and intelligent data retrieval.
- **Embeddings**: For creating vector stores to enable efficient search and retrieval.
- **Agents**: For facilitating interaction with the knowledge base and users.







