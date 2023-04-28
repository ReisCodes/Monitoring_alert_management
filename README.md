# Monitoring & Aleret management

### Why do we need to Monitor?

Cloud monitoring is the practice of measuring, evaluating, monitoring, and managing workloads inside cloud tenancies against specific metrics and thresholds. It can use either manual or automated tools to verify the cloud is fully available and operating properly.

Cloud monitoring allows you to find out if your cloud-hosted applications are performing within their Service-Level Agreement (SLA), discover any potential security risks, identify any capacity issues, and analyze costs.

### 4 Golden "Signals" of Monitoring

- Latency: The time it takes to service a request.
<br>

- Traffic: A measure of how much demand is being placed on your system, measured in a high-level system-specific metric. For a web service, this measurement is usually HTTP requests per second.
<br>

- Errors: The rate of requests that fail, either explicitly (e.g., HTTP 500s), implicitly (for example, an HTTP 200 success response, but coupled with the wrong content), or by policy (for example, "If you committed to one-second response times, any request over one second is an error"). 
<br>

- Saturation: How "full" your service is. A measure of your system fraction, emphasizing the resources that are most constrained (e.g., in a memory-constrained system, show memory; in an I/O-constrained system, show I/O).

### What is Alert Management?

The alert management process consists of monitoring systems, defining what’s normal, and notifying the right people when something abnormal occurs so that the right teams can be made aware of the issue and resolve it.

##### Simple notification service (SNS)

Simple Notification Service (SNS) is a cloud service for coordinating the delivery of push messages from software applications to subscribing endpoints and clients.

##### Simple Queue Service (SQS)

Amazon Simple Queue Service (SQS) is a managed message queuing service technical professionals and developers use to send, store and retrieve multiple messages of various sizes asynchronously.

#### Cloud watch to monitor AWS service/s

Amazon CloudWatch is an AWS monitoring and management service which is designed for the purpose of maintaining the services and resources which are used. Particularly, this is designed for developers, site reliability engineers, IT managers, and system operators to make their life easier.