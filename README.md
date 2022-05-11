# Microsoft Exchange Server

This Dynatrace extensions allows you to monitor your Microsoft Exchange Server.
It enables full observability for your mail and calendar server. It is highly flexible, and can be easily configured to meet specific requirements.

**This is intended for users, who:**
- Want to monitor Microsoft Exchange Servers
- Improve Exchange Server performance and health
- Detect potential security breaches

**This enables you to:**
- Enable alerting based on detected anomalies
- Track events reported by MS Exchange server
- Alert on anomalies leading to performance issues

**Supported Distributions**
- Microsoft Exchange Server 2013 and 2016+  
(currently only on-premises deployments are supported.)

**Collected metrics:**

Messages:
- Messages sent
- Messages sent/s
- Bytes sent
- Bytes sent/s
- Messages received
- Messages received/s
- Bytes received
- Bytes received/s
- Rejected messages

Queue messages:
- Active mailbox delivery queue
- Active non SMTP delivery queue
- External active remote delivery queue
- All external remote delivery queues
- Internal active remote delivery queue
- All internal remote delivery queues
- Poison queue
- Mailbox retry delivery queues
- Non SMTP retry delivery queues
- Submission queue
- Expired messages in submission queue
- Deffered messages in submission queue
- Completed items
- Completed items/s
- Queued items
- Queued items/s
- Expired queued items
- Completed messages
- Completed messages/s
- Delayed messages
- Delayed messages/s
- Queued messages
- Queued messages total
- Number of queued messages per second
- Submitted messages
- Submitted messages/s
