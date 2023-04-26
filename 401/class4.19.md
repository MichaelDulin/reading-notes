# Class 4.19 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 19**
- [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)
- [AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)
- [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)
- [SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)
- [SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)

**AWS SQS vs SNS**
1. What is the difference betweeen SQS and SNS?
  - SQS: Simple Queue Service
    - Can log messages and can hold for up to 14 days
  - SNS: Simple Notification System
    - Used for applications which need realtime notifications 
2. What are some use cases for both SNS and SQS?
  - These two services can be used together, however, the real difference comes from real-time application while the other technically does not run concurrently.

  
**AWS SNS and SQS**
1. Describe how to use SQS and SNS in a “fanout” pattern.
  - When an SNS topic is replicated and pushed to multiple endpoints such as SQS, HTTP endpoints and Lambda functions. These allow us to 'link' multiple functions / code together to execute.
2. Explain how “push notifications” work, using SNS.
  - Using predefined threshholds, we can use SNS to send emails or text messages to specific users given specific parameters.


**SQS and SNS Basics**
1. How might a large scale, distributed application make use of a Queue system like SQS?
  - By pushing fanout patterned objects, we can enqueue entire objects full of functions and links to other AWS services.



## Things I want to know more about
