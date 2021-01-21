# An Implementation of Membership Protocol based on GOSSIP.

Building a distributed Fault-Tolerant Key-Value Store on nodes running membership protocol.

The project was forked from University of Illinois at Urbana-Champaign' [Cloud Computing Specialization](https://www.coursera.org/specializations/cloud-computing) programming assignment. 

### What is the project?
The project is about implementing a Gossip Protocol.

The main functionalities of the project :

**1.Introduction :** Each new peer contacts a well-known peer (the introducer) to join the group.

**2.Membership :** A membership protocol satisfies completeness all the time (for joins and failures), and accuracy when there are no message delays or losses (high accuracy when there are losses or delays).


### The protocol satisfies:

Completeness : Every none faulty process detects every node join, failure and leave.

Accuracy of failure detection : When there are no message losses and message delays are small, all failures are detected. When there are message losses, completeness is satisfied and accuracy is high. 

### Test

There is a grader script GraderNew.sh. It tests your implementation of membership protocol in 3 scenarios.

Single node failure

Multiple node failure

Single node failure under a lossy network.

	$ chmod +x GraderNew.sh
	$ ./GraderNew.sh
