1. The program sends 5 messages in total. From the main function in the code, it calls the publish_event function five times, sending five different names.
2. It means both the Publisher and the Subscriber are connecting to the same address. For communication to work, the program sending the mail and the program receiving the mail must use the same address so they can find each other.
---
![Running RabbitMQ](images/rabbitmq1.0.png)
![Subscriber Console](images/subscriberconsole1.0.png)
![Publisher Console](images/publisherconsole1.0.png)