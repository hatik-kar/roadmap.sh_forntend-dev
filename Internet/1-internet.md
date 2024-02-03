
# [Internet](https://cs.fyi/guide/how-does-internet-work#introduction-to-the-internet)

## Intro to internet

* A network is a group of computers or other devices which are connected to eachother.
* The internet is a network of networks.

## Workings

* Connecting devices and computer systems together using a set of standardized protocols (info exchange, security)

* In core it's a global network of interconnected routers,  which helps directing traffic between different devices and systems. data is broken up into small packets [device(packet) -> router(examines) -> router -> destination].

* Internet Protocol (IP) and the Transmission Control Protocol (TCP). IP is responsible for routing packets to their correct destination, while TCP ensures that packets are transmitted reliably and in the correct order.

* Domain Name System (DNS), the Hypertext Transfer Protocol (HTTP), and the Secure Sockets Layer/Transport Layer Security (SSL/TLS) protocol.

## Basic Concepts and Terminology

* Packet: A small unit of data that is transmitted over the internet.
* Router: A device that directs packets of data between different networks.
* IP Address: A unique identifier assigned to each device on a network, used to route data to the correct destination.
* Domain Name: A human-readable name that is used to identify a website, such as google.com.
* DNS: The Domain Name System is responsible for translating domain names into IP addresses.
* HTTP: The Hypertext Transfer Protocol is used to transfer data between a client (such as a web browser) and a server (such as a website).
* HTTPS: An encrypted version of HTTP that is used to provide secure communication between a client and server.
* SSL/TLS: The Secure Sockets Layer and Transport Layer Security protocols are used to provide secure communication over the internet.

## The Role of Protocols in Internet

A protocol is a set of rules and standards that define how information is exchanged between devices and systems. Like, IP, TCP, UDP, DNS etc..

* **IP** (Internet Protocol) is responsible for routing packets of data to their correct destination, while **TCP** (Transmission Control Protocol) and **UDP** (User Datagram Protocol) ensure that packets are transmitted reliably and efficiently. **DNS** (Domain Name System) is used to translate domain names into IP addresses, and **HTTP** (Hypertext Transfer Protocol) is used to transfer data between clients and servers.

## Understanding IP Addresses and Domain Names

* An IP address is a unique identifier assigned to each device on a network. It’s used to route data to the correct destination. IP addresses are typically represented as a series of four numbers separated by periods, such as “192.168.1.1”.

* Domain names, are human-readable names used to identify websites and other internet resources. They’re typically composed of two or more parts, separated by periods. For example, “google.com” is a domain name. Domain names are translated into IP addresses using the Domain Name System (DNS).
[Browser -> Enter Domain Name -> DNS Query to DNS Server -> IP return -> Computer goes there]

## Introduction to HTTP and HTTPS

* HTTP is the protocol used to transfer data between a client (such as a web browser) and a server (such as a website). When you visit a website, your web browser sends an HTTP request to the server, asking for the webpage or other resource you’ve requested. The server then sends an HTTP response back to the client, containing the requested data.

* HTTPS is a more secure version of HTTP, which encrypts the data being transmitted between the client and server using SSL/TLS (Secure Sockets Layer/Transport Layer Security) encryption. This provides an additional layer of security, helping to protect sensitive information such as login credentials, payment information, and other personal data.

## Building Applications with TCP/IP

* It provides a reliable, ordered, and error-checked delivery of data between applications running on different devices.

* When building applications with TCP/IP, there are a few key concepts to understand:

  * Ports: Ports are used to identify the application or service running on a device. Each application or service is assigned a unique port number, allowing data to be sent to the correct destination.

  * Sockets: A socket is a combination of an IP address and a port number, representing a specific endpoint for communication. Sockets are used to establish connections between devices and transfer data between applications.

  * Connections: A connection is established between two sockets when two devices want to communicate with each other. During the connection establishment process, the devices negotiate various parameters such as the maximum segment size and window size, which determine how data will be transmitted over the connection.
  
  * Data transfer: Once a connection is established, data can be transferred between the applications running on each device. Data is typically transmitted in segments, with each segment containing a sequence number and other metadata to ensure reliable delivery.

* Other protocols HTTP, FTP, SMTP.

## Securing Internet Communication with SSL/TLS

SSL/TLS is a protocol used to encrypt data being transmitted over the internet. It is commonly used to provide secure connections for applications such as web browsers, email clients, and file transfer programs.

When using SSL/TLS to secure internet communication, there are a few key concepts to understand:

* Certificates: SSL/TLS certificates are used to establish trust between the client and server. They contain information about the identity of the server and are signed by a trusted third party (a Certificate Authority) to verify their authenticity.

* Handshake: During the SSL/TLS handshake process, the client and server exchange information to negotiate the encryption algorithm and other parameters for the secure connection.

* Encryption: Once the secure connection is established, data is encrypted using the agreed-upon algorithm and can be transmitted securely between the client and server.

## The Future: Emerging Trends and Technologies

* Internet of Things (IoT): IoT refers to the network of physical devices, vehicles, home appliances, and other objects that are connected to the internet and can exchange data. As IoT continues to grow, it is expected to revolutionize industries such as healthcare, transportation, and manufacturing.

* Artificial Intelligence (AI): AI technologies such as machine learning and natural language processing are already being used to power a wide range of applications and services, from voice assistants to fraud detection. As AI continues to advance, it is expected to enable new use cases and transform industries such as healthcare, finance, and education.

* Blockchain: Blockchain is a distributed ledger technology that enables secure, decentralized transactions. It is being used to power a wide range of applications, from cryptocurrency to supply chain management.

* Edge computing: Edge computing refers to the processing and storage of data at the edge of the network, rather than in centralized data centers. It is expected to enable new use cases and applications, such as real-time analytics and low-latency applications.

## Summery

* The internet is a global network of interconnected computers that uses a standard set of communication protocols to exchange data

* The internet works by connecting devices and computer systems together using standardized protocols, such as IP and TCP

* The core of the internet is a global network of interconnected routers that direct traffic between different devices and systems.

* Basic concepts and terminology that you need to familiarize yourself with include packets, routers, IP addresses, domain names, DNS, HTTP, HTTPS, and SSL/TLS.

* Protocols play a critical role in enabling communication and data exchange over the internet, allowing devices and systems from different manufacturers and vendors to communicate seamlessly.
