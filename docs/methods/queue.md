## Queue

### /v1/queue
`POST`
| Cookie | Value |
| ------ | ----- |
| bhvrSession | session |

> Queues you for the game  
> Can be called multiple times to update queue position  
> Requires passing the EAC challenge check

### /v1/queue/cancel
`POST`
| Cookie | Value |
| ------ | ----- |
| bhvrSession | session |

> Cancels queue

### /v1/queue/token/issue
`POST`
| Cookie | Value |
| ------ | ----- |
| bhvrSession | session |

> Generates token for a match  
> Executed when [/v1/queue](./queue.md#v1queue) returns "MATCHED" status