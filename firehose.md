#### Kinesis Firehose:

* We have Data Producers like EC2.

#### Sending the data to Firehose:
* No need to worry about Streams, Shards, Manually adding shards based on the data etc.. It is completely automated.
* No need to worry about Data Consumers who is going to analyse the data.
* You can analyse data using lambda in real time. Once the data is analyzed you can send the data to directly to S3.
* Now the Actual analytics of the data is completely optional.

#### Data Retention
* In Firehose there is no automatic data retention window, in kinesis we have 24 hrs window and can be extended upto 7 days.
* As soon as the data comes either its already analyzed using Lambda or directly sent to S3 or other locations like 
RedShift.

* First data must be copied to S3 and then the data copied from S3 to RedShift.
