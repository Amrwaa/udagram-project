# AWS
![alt text](https://github.com/Amrwaa/udagram-project/blob/main/documents/aws.png?raw=true)


## RDS Postgres
The application server uses AWS RDS Postgres as database for storing and retrieving information.

RDS Database : database-1.cdgdt3bwnkhi.us-east-1.rds.amazonaws.com


## Elastic Beanstalk
The application server is deployed on AWS Elastic Beanstalk service node platform. The application is build, archived and uploaded to and S3 bucket from where Elastic Beanstalk do all the hard work for setting up the environment and runs the application on an endpoint.

ElastibBeans api: http://Udapp-env.eba-ifeuz3hf.us-east-1.elasticbeanstalk.com

## S3 Bucket
The frontend application is deployed using AWS S3 Bucket. The application build are uploaded to an S3 bucket and that bucket is made publicly readable.

Bucket URL: http://udagrambucket.s3-website-us-east-1.amazonaws.com

