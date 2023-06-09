# Class 19 Reading: AWS - Events

## Resources

- [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)
- [AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)
- [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

## AWS SQS vs SNS

1. What is the difference betweeen SQS and SNS?
    - SQS is a distributed message queueing system. It allows you to send messages between applications. SNS is a distributed publish/subscribe system. It allows you to send messages to subscribers to a topic.

2. What are some use cases for both SNS and SQS?
    - SQS is used for decoupling applications. It allows you to send messages between applications without having to worry about the applications being available at the same time. SNS is used for fanout messaging and event notifications. It allows you to send messages to multiple subscribers to a topic.

## AWS SNS and SQS

1. Describe how to use SQS and SNS in a “fanout” pattern.
    - You can use SNS to send messages to SQS queues. This allows you to send messages to multiple SQS queues at once.

2. Explain how “push notifications” work, using SNS.
    - You can use SNS to send messages to mobile devices. This allows you to send messages to multiple mobile devices at once.

## SQS and SNS Basics

1. How might a large scale, distributed application make use of a Queue system like SQS?
    - A large scale, distributed application might use SQS to send messages between applications. This allows the applications to be decoupled and not have to worry about being available at the same time.

### Bookmark and Review

- [SNS JavaScript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)
- [SQS JavaScript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)

### Reflection

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-19/)

1. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: I just want to build a mobile app that can send push notifications. I think that'd be pretty sick.

#### Things I Want to Know More About

1. AWS in general is a giant beast that I don't know much about. I'd like to learn more about it because I'd really like to try out this SNS and SQS stuff.

![GIF](https://media.giphy.com/media/1vZcbntQ1jVcSA78gw/giphy-downsized-large.gif)
