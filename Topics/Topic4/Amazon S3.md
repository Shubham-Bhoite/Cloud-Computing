# Amazon S3 

-   Amazon S3 (Simple Storage Service) is a highly scalable and durable object storage service provided by Amazon Web Services (AWS). 

-   It is designed to store and retrieve large amounts of data, such as files, images, videos, and backups, over the internet. 

-   S3 offers a simple and cost-effective solution for businesses and developers to store, manage, and retrieve data from anywhere at any time.

## Features :
1. Unlimited storage
2. Highly scalable : In terms of storage, request rate and concurrent users.
3. Reliable : Store redundant data in multiple facilities and on multiple devices.
4. Secure : Flexibility to control who / how / when / where to access the data.
5. Performance : Choose region to optimize for latency / minimize costs.
- Example : Online photo processing service.

## Procedure :
-  Web server receive request.
-  Put request message in the queue.
-  Pictures stored in 53.
-  Multiple EC2 instances run photo prcxessing.
-  Put back in the queue.
-  Return