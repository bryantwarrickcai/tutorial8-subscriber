## Module 9
### Question 7
a.  
AMQP (Advanced Message Queuing Protocol) is an open-standard messaging protocol that enabled applications and systems to communicate via a message broker. It is designed to be a reliable, asynchronous, and secure method of exchanging messages between systems. This protocol also ensures that messages are delivered even in the case of network or system failures.

b.  
The first `guest` is the username used to authenticate with the AMQP broker. The second `guest` is the password for authentication. However, these are both default credentials, and should not be used in actual production.

The `localhost` is the host address where the AMQP broker is running. `localhost` refers to the local machine and translates to `127.0.0.1`. `5672` is the default port number used for unencrypted AMQP connections. For encrypted connections with SSL/TLS, the port is `5671` instead.
