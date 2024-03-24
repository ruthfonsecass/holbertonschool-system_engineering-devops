# 1 - What is a server
A server is a computer or system that provides resources, data, services, or programs to other computers, known as clients, over a network. In essence, servers serve information to computers that request it. 

# 2 - What is the role of the domain name
A domain name serves as the readable address for websites on the internet, making it easier for users to find and access web pages. Instead of memorizing complex IP addresses, a domain name allows users to enter a simple, memorable name into their browser. 

# 3 - What type of DNS record www is in www.foobar.com
The "www" in "www.foobar.com" typically corresponds to a DNS record of type "A" or "AAAA". An "A" record maps a domain name to an IPv4 address, while an "AAAA" record maps a domain name to an IPv6 address. In many cases, "www" is used as a subdomain to specify the address of the web server within the "foobar.com" domain. 

# 4 - What is the role of the web server 
The web server's role is to store, process, and deliver web pages to users. It responds to requests from browsers, serving content over the internet, which can include HTML files, images, and scripts. For dynamic content, it can execute server-side scripts before sending the generated page to the user's browser.

# 5 - What is the role of the application server
An application server's role is to provide an environment where applications can run, regardless of what the end user is doing. It handles the business logic of an application, processes requests from the web server, interacts with databases or other services, and returns the processed data back to the web server. 

# 6 - What is the role of the database
The database's role is to store, retrieve, and manage data efficiently. It serves as the central repository for applications, holding everything from user information to transaction records, and enables quick data queries and updates. This allows applications to provide dynamic, personalized content to users based on stored data.

# 7 - What is the server using to communicate with the computer of the user requesting the website
The server communicates with the user's computer requesting the website primarily through the Hypertext Transfer Protocol (HTTP) or its secure version, Hypertext Transfer Protocol Secure (HTTPS). 

# 8 - what the issues are with this infrastructure
## Single Point of Failure (SPOF):
With only one server handling web, application, and database roles, any hardware or software failure affects the entire system.
## Scalability Issues with Increased Traffic: 
single server has limited resources (CPU, memory, bandwidth). As traffic to the website grows, this setup cannot accommodate the increased load without degrading performance or becoming completely overwhelmed.
## Downtime During Maintenance: 
Since there's only one server, deploying new code or performing updates that require a restart of the web server leads to downtime. 