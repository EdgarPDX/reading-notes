Read
Redis
    -is a fast, open-source, in-memory key-value data store for use as a database, cache, message broker, and queue
Queue
    -is another common data structure that places elements in a sequence, similar to a stack
    Enqueue() — Inserts an element to the end of the queue

    Dequeue() — Removes an element from the start of the queue

    isEmpty() — Returns true if queue is empty

    Top() — Returns the first element of the queue
Task Queue Overview
    -This method of deferring work to some task processor is called a task queue
Task Queue - FIFO
    first in first out
Bull Quick 
    -Bull is a Node library that implements a fast and robust queue system based on redis.
    -this library provides an API that takes care of all the low-level details and enriches Redis basic functionality so that more complex use-cases can be handled easily.
    -In order to work with Bull, you also need to have a Redis server running. For local development you can easily install it using docker.
    -Bull will by default try to connect to a Redis server running on localhost:6379