## Kinesis

#### What is streaming data ?
* Streaming Data is data that is generated continuously by thousands of data sources, which typically
send in the data records simultaneously, and in small sizes ( order of Kilobytes).

#### What is Kinesis ?

* Amazon Kinesis is a platform on AWS to send your streaming data.
* Kinesis makes it easy to load and analyze streaming data, and also providing the ability for you to build your own custom applications for your business needs.

#### What are the core Kinesis Services ?
* Three Services:
 * Kinesis Streams
 * Kinesis Firehose
 * Kinesis Analytics

Note: 
* In the exam, you will be given different scenario questions and you have to identify which service you should use in order to best fit the scenarios.
* You need to have a key understanding of the different aspects of the services.

#### What is Kinesis Stream ?

* Producers - EC2, Mobile Phones, Computer, IoT
* Data sent to Kinesis are stored in SHARDS for 24 hrs to 7 days Retention.

* Data Consumers: Fleet of EC2 instances
* They take the data from the shards and turn them into something useful.
 * Data Aggregation
 * Sentimental Analysis on Social Media Platform
 * etc..
