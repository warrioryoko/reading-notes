Oh joy. We're apparently going to learn ALL ABOUT REDIS, a IN-MEMORY Key-Value store, cache, message broker and queue system. This is NOT a database, because it is IN MEMORY.

This is desirable to performing mutations on data, and having access to data structures rather than have to rely on Classes that store data in SQL, which has limited capabilities, and data bottlenecks.

Queues - places elements in a sequence. First In, First Out. Works like a restaurant line.

Task Queues - you might have an operation you don't want to execute immediately.

FIFO - Add (shift) items to the start of an array, remove (pop) items from the end of an array.

You CAN prioritize some operations higher than others.

Bull is a node library that gives you a queue system based on REDIS.