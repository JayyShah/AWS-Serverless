- This repository aims to cover the following topics that gives you a high level idea on Amazon EMR:
    1. EMR Serverless
    2. Deployment Options
    3. What Problem does it solves
    4. Benifits and use Cases
    5. Implementation

# Introduction:
    - EMR refers to Elastic Map Reduce <A bit more>
    - It is Used to process large/Vast amount of data efficiently using hadoop and services offered by AWS.
    - It is used to Run large scale distributed data processing job, interactive queries and ML applications using analytics framework like spark, Hive and Presto.
    - It aims to automate time consuming tasks like setup, tuning and capacity Planning.

# Deployment Options

1. EMR Serverless 
    - It helps data analyst and data engineers run open source big data analytics framework without configuring managing and scaling cluster/Servers.
    - It is suitable for customers who want to avoid managing and operating clusters and prefer to run applications using open source frameworks.

2. EMR on EC2
    - Closest deployment to a YARN based hadoop platform supporting various open source frameworks.
    - It is suitable for those who need maximum control and flexibility over running applications.
    - With EMR on EC2, customers can shut instance type to meet application specific performance needs and customize Linux AMI and Instance.
    - They can also customize and extend open source and install additional software on cluster instances.

3. EMR on EKS
    - Runs application on EKS (Elastic Kubernetes Services) cluster that offers the benifits of both EMR and Kubernetes.
    - Suitable for customers who want to standardize on EKS to manage Clustes across apllication or use different versions of Open source Frameworks on the same cluster.

4. EMR on AWS Outposts
    - It is a fully managed service that offers the same AWS Infrastructure and Services, API's and tools to virtually any data center, co-location space or on-premises facility for a consistent hybrid experience.
    - For customers who want to run EMR closer to their data within an Outpost

