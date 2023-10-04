
✅ Project Title: Deploy a 3 Tier Architecture On AWS - End to End Project

✅ Project Overview: In this architecture, a public-facing Application Load Balancer forwards client traffic to our web tier EC2 instances. The web tier is running Nginx webservers that are configured to serve a React.js website and redirects our API calls to the application tier’s internal facing load balancer. The internal facing load balancer then forwards that traffic to the application tier, which is written in Node.js. The application tier manipulates data in an Aurora MySQL multi-AZ database and returns it to our web tier. Load balancing, health checks and autoscaling groups are created at each layer to maintain the availability of this architecture.



☑ Tier 1: Presentation Layer
☑ Create a web application using a framework like React, Angular, or Vue.js.
☑ Host the frontend on Amazon S3 or use AWS Amplify for a serverless frontend deployment.

✅ Tier 2: Application Layer
☑ Develop a server-side application using a technology like Node.js, Python, or Java.
☑ Deploy the application on AWS Elastic Beanstalk or AWS Lambda for serverless applications.
☑ Use Amazon API Gateway for creating RESTful APIs or AWS App Runner for containerized applications.

✅ Tier 3: Data Layer
☑ Choose a database solution like Amazon RDS (Relational Database Service), Amazon DynamoDB (NoSQL), or Amazon Aurora (MySQL/PostgreSQL).
☑ Configure database security groups and access controls.
☑ Ensure data backup and redundancy as per your application's needs.

![image](https://github.com/Shreyashbhise/-Deploy-a-3-Tier-Architecture-On-AWS---End-to-End-Project-/assets/108046802/5e7069ed-2627-4c09-9553-0a966b9a49f5)
![image](https://github.com/Shreyashbhise/-Deploy-a-3-Tier-Architecture-On-AWS---End-to-End-Project-/assets/108046802/675d72fc-1148-4a29-89fc-53ca8a57fcc0)





