# Why Add Each Element:

## Firewalls: 
Added for enhanced security, controlling access to the network and protecting against unauthorized access and threats.
## SSL Certificate: 
Ensures encrypted communication over HTTPS, safeguarding data in transit between the user and the server.
## Monitoring Clients: 
Provide real-time insights into system performance, helping detect and troubleshoot issues quickly.

# Purpose of Firewalls:
Firewalls act as a barrier between your internal network and incoming traffic from external sources. They are crucial for preventing unauthorized access and can filter traffic based on predetermined security rules.

# HTTPS Traffic:
Serving traffic over HTTPS encrypts the data exchanged, protecting sensitive information from interception or tampering by attackers. It's essential for user trust and privacy, and often required for compliance with security standards.

# Use of Monitoring:
Monitoring tools are used to track the performance and health of the infrastructure. They can alert administrators to potential issues before they impact users, ensuring the system runs smoothly and efficiently.

# Data Collection by Monitoring Tools:
Monitoring tools collect data through agents installed on servers or network devices. These agents gather metrics and logs, sending them back to the monitoring service for analysis and alerting.

# Monitoring Web Server QPS:
To monitor your web server's Queries Per Second (QPS), you would configure your monitoring tool to track the number of requests that the web server processes each second. This can involve setting up custom metrics or using existing ones, depending on the tool.

# Issues with Infrastructure:

## SSL Termination at Load Balancer: 
Terminating SSL at the load balancer can expose unencrypted traffic within the internal network, potentially creating a security vulnerability if the internal network is compromised.
## Single MySQL Server for Writes: 
Having only one MySQL server that can accept writes creates a single point of failure. If it goes down, the entire application's ability to update or insert new data is compromised.
## Same Components on All Servers: 
Having servers with identical setups (database, web server, and application server) can lead to inefficiencies and potential resource contention. It also means that a single security vulnerability could compromise every aspect of the application, from the presentation layer down to the data layer.