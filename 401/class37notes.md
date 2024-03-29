# [Class 37 Reading Notes](https://github.com/snur206/reading-notes/blob/main/401/class37notes.md)

This topic matters because it is an intro to S3.

## Introduction to Amazon S3

What is Amazon S3?

It is an object an object storage service that offers industry-leading scalability, data availability, security, and performance. It is used for storing and retrieving data at any time, from anywhere.

List at least 3 features that it offers to its users.

- Storage classes: You can store data with changing or unknown access patterns in S3 Intelligent-Tiering, which optimizes storage costs by automatically moving your data between four access tiers when your access patterns change.

- Storage management: Used to manage costs, meet regulatory requirements, reduce latency, and save multiple distinct copies of your data for compliance requirements.

- Data processing: To transform data and trigger workflows to automate a variety of other processing activities at scale, you can use the following features.

What is an object key?

A unique identifier for an object w/in a bucket.

What is Amazon S3? - amazon simple storage service (no date). Available at: https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html (Accessed: February 28, 2023). 

## S3 with Amplify

Which dependencies are needed to install Amplify AWS S3 to your ndroid application?

`implementation 'com.amplifyframework:aws-storage-s3:2.2.2'`

`implementation 'com.amplifyframework:aws-auth-cognito:2.2.2'`

What is needed in order to upload data to your bucket?

You specify the key and the data object.

what method(s) initialize(s) the Amplify Auth and Storage categories?

Call `Amplify.addPlugin()` for each category, then `Amplify.configure()` to complete the initialization call.

## Things I want to know more about

More on S3.
