# AWS: Events

- Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server
    - All of them use WRRC

- List the AWS Database offerings and talk about the pros and cons of each
    - Choose from 15+ purpose-built database engines including relational, key-value, document, in-memory, graph, time series, wide column, and ledger databases.
    - relational databases that are 3-5X faster than popular alternatives, or non-relational databases that give you microsecond to sub-millisecond latency.
    - continuously monitors your clusters to keep your workloads running with self-healing storage and automated scaling, so that you can focus on application development.
    -  built for business-critical, enterprise workloads, offering high availability, reliability, and security.
    - all of these features are great for larger scale models, but can rack up a bill if not used carefully, and can be inefficient for small scale applications

- What’s the difference between a FIFO and a standard queue?
    - Standard queues will deliver a message only once, a FIFO Queue will deliver once, but remain available after delivery.

- How can the server be assured a message was properly received?
    - send back a received code

## Document the following Vocabulary Terms

- Serverless API: Serverless is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers. A serverless application runs in stateless compute containers that are event-triggered, ephemeral, and fully managed by the cloud provider.
- Triggers: The method of embedding information in the document that tells the javascript where to attach its event handlers
- Dynamo vs Mongo: MongoDB is platform-agnostic and configured with the database to run virtually anywhere from a local machine, container, or on-premise deployment to any cloud provider. It requires users to manage all the infrastructure and configurations. MongoDB is a schema-free database. While DynamoDB is limited to AWS and can only configure and use DynamoDB through AWS. It's a fully managed database. DynamoDB is a schema-less database but with no ability to enforce schemas.
- Dynamoose vs Mongoose: The ORM that refers to the specific database type its connected to.

- Which 3 things had you heard about previously and now have better clarity on?
    - Dynamo, AWS, FIFO Queue
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - Dynamo, AWS, FIFO Queue
- What are you most excited about trying to implement or see how it works?
    - Dynamo
