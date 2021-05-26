## Event Driven Architecture

 (EDA) is a software architecture paradigm promoting the production, detection, consumption of, and reaction to events. ... A car dealer's system architecture may treat this state change as an event whose occurrence can be made known to other applications within the architecture


-  What’s the difference between a FIFO and a standard queue?
FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers


- How can the server be assured a message was properly received?
we can use the socket.io’s acknowledgements.

- What classic design pattern is best represented by event driven programming?
Observer pattern
### How do you test an event driven system?
- Ensure supporting topics exist
- Start the application under test (“application” here could mean Kafka Streams, Kafka connectors, Samza, etc.)
- Send some input events
- Wait until the application has finished processing the test input
- Assert that it looks right


## FIFO Queue
 (First-In-First-Out) queues are designed to enhance messaging between applications when the order of operations and events is critical
## Pub/Sub
is an asynchronous messaging service that decouples services that produce events from services