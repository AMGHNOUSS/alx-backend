# 0x03. Queuing System in JS
Project done during **Full Stack Software Engineering studies** at **ALX School**. It aims to learn about :
- How to run a Redis server on your machine
- How to run simple operations with the Redis client
- How to use a Redis client with Node JS for basic operations
- How to store hash values in Redis
- How to deal with async operations with Redis
- How to use Kue as a queue system
- How to build a basic Express app interacting with a Redis server
- How to the build a basic Express app interacting with a Redis server and queue

## Technologies
* Scripts written in Bash 5.1.16
* Tested on Ubuntu 20.04 LTS
* Node v18.19.1

## Files

| Filename | Description |
| -------- | ----------- |
| `README.md, dump.rdb` | 0. Install a redis instance |
| `0-redis_client.js` | 1. Node Redis Client |
| `1-redis_op.js` | 2. Node Redis client and basic operations |
| `2-redis_op_async.js` | 3. Node Redis client and async operations |
| `4-redis_advanced_op.js` | 4. Node Redis client and advanced operations |
| `5-subscriber.js, 5-publisher.js` | 5. Node Redis client publisher and subscriber |
| `6-job_creator.js` | 6. Create the Job creator |
| `6-job_processor.js` | 7. Create the Job processor |
| `7-job_creator.js` | 8. Track progress and errors with Kue: Create the Job creator |
| `7-job_processor.js` | 9. Track progress and errors with Kue: Create the Job processor |
| `8-job.js` | 10. Writing the job creation function |
| `8-job.test.js` | 11. Writing the test for job creation |
| `9-stock.js` |  12. In stock? |
| `100-seat.js` |  13. Can I have a seat?  |
