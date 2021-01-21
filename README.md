# An Implementation of Membership Protocol based on GOSSIP.

### What is the project?
The project is about implementing a Gossip Protocol.

The main functionalities of the project :
**1.Introduction :** Each new peer contacts a well-known peer (the introducer) to join the group.
**2.Membership :** A membership protocol satisfies completeness all the time (for joins and failures), and accuracy when there are no message delays or losses (high accuracy when there are losses or delays).


### The protocol satisfies:

Completeness : Every none faulty process detects every node join, failure and leave.
Accuracy of failure detection : When there are no message losses and message delays are small, all failures are detected. When there are message losses, completeness is satisfied and accuracy is high. 
