# Chapter 0
I'm planning on creating a personal blog, and have decided to use that as my first serverless project.I have no idea yet what frameworks or collection of services I'll end up using.

I'm also dreading the problem of how to sort out urls, head elements and search bots.

My first approach is going to be something like React or Angular hosted in S3 over CloudFront. The data will come from python Lambda functions pulling from DynamoD through API Gateway.

Being new to many of these services, I'm leaning heavily on some online courses from A Cloud Guru and Udemy:

### AWS Lambda
Lambda is AWS's FAAS (Function as a service). They can be triggered by all sorts of events - like uploading to an s3 bucket or, in my case, in response to an HTTP request through API Gateway (another AWS service).

I'm going through A Cloud Guru's "AWS Lambda" course and have a separate repo for it https://github.com/smrkem/acloudguru-awslambda.
