#### SQS

* SQS is a distributed message queueing system.
* SQS allows you to decouple the components of an application so that they are independent.
* Pull-based not push-based.

#### Types of Queues:
* Standard Queues (default)
* FIFO Queues

#### Standard Queues(default):
* best effor ordering, message delivered at least once.

#### FIFO Queues(First In First Out):
* ordering strictly preserved, message delivered once, no duplicates ( e.g. good for banking transactions
which need to happen in strict order).

#### Visibility Timeout  
* Default 30 seconds - increase if your task takes more than 30 seconds to complete.
* Maximum 12 hours

#### Short Polling :
*  returned immediately even if no messages are in the queue.

#### Long Polling
* polls the queue periodically and only returns a response when a message is in the queue or the timeout is reached.
