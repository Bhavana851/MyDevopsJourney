## Monolith System

A monolithic system refers to a software application or architecture that is built as a single, indivisible unit where all components of the application are interconnected and interdependent. In this type of system, the entire application is designed, developed, deployed, and maintained as a single cohesive unit.

Key characteristics of a monolithic system include:

* Unified deployment 

* Tightly coupled components 

* Single codebase 

## Microservices system

* The microservice architectural style is an approach to developing a single application as a suite of small services, each running in its own process and communicating with lightweight mechanisms, often an HTTP resource API. 
* These services are built around business capabilities and independently deployable by fully automated deployment machinery. There is a bare minimum of centralized management of these services, which may be written in different programming languages and use different data storage technologies. 



## * API Gateway 

In a microservices architecture, an API gateway acts as a single entry point for client requests. The API gateway is responsible for request routing, composition, and protocol translation. It also provides additional features like authentication, authorization, caching, and rate limiting.

![A P I](API.png)


## * Proxy 

A proxy server acts as an intermediary between a client (such as a user's computer or device) and another server (typically the internet or a specific server) to facilitate various types of requests, connections, or services. It sits between the client and the destination server, forwarding requests from the client to the server and returning responses from the server to the client.

## * Forward Proxy
A forward proxy is a server that sits between user devices and the internet.

A forward proxy is commonly used for: 

* Protect clients 

* Avoid browsing restrictions 

* Block access to certain content 

## * Reverse Proxy

A reverse proxy is a server that accepts a request from the client, forwards the request to web servers, and returns the results to the client as if the proxy server had processed the request.

A reverse proxy is good for:

* Protect servers 

* Load balancing 

* Cache static contents 

* Encrypt and decrypt SSL communications 

## * session

a "session" refers to a period of interaction or communication between a user (or a client) and a system (such as a website or an application) within a specific timeframe. Sessions play a crucial role in maintaining state and managing interactions between users and servers.

## * Token 

"token" refers to a small, self-contained piece of data that represents certain information or privileges. Tokens are widely used in various contexts and serve multiple purposes, including authentication, authorization, and data exchange.

## * Cookie

A cookie, in the context of computing and web technology, is a small piece of data that a website sends to a user's web browser while the user is browsing that website. Cookies are stored in the user's browser and are used to remember information about the user or their browsing activity on the site. They serve various purposes, including maintaining user sessions, personalizing user experiences, and tracking user behavior.

## * Password

A password is a secret string of characters used to authenticate or confirm the identity of a user attempting to access a system, device, application, or specific content. It serves as a means of access control by allowing authorized users to gain entry while preventing unauthorized access.

## * What is Auth and expore on Outh 

**"Auth"** is a widely used abbreviation for "authentication," which refers to the process of confirming or validating the identity of an individual, system, or entity attempting to access a particular resource, system, or data.

**OAuth (Open Authorization)** is an open standard protocol used for secure, delegated access to user data on the internet. It allows applications to access resources on behalf of users without requiring them to share their credentials (like usernames and passwords) directly with the application.

## * what is Authentication 

Authentication is the process of confirming or verifying the identity of an individual, entity, system, or user attempting to access a particular system, service, data, or resource. It is a fundamental aspect of security that ensures only authorized and legitimate users or entities gain access while preventing unauthorized access or potential security breaches.

*** What is Authorization**

Authorization is the process of granting or denying access to specific resources, functionalities, or actions within a system, application, or service based on the authenticated identity and permissions of an individual or entity. While authentication confirms the identity of a user, authorization determines what actions or resources an authenticated user or entity is allowed to access.

## * HTTP Protocol 

**Hypertext Transfer Protocol Secure (HTTPS)** is an extension of the Hypertext Transfer Protocol (HTTP.) HTTPS transmits encrypted data using Transport Layer Security (TLS.) If the data is hijacked online, all the hijacker gets is binary code.

![8c53f73a c6ec 45cc afb5 4018ac97a488_1600x1085](8c53f73a-c6ec-45cc-afb5-4018ac97a488_1600x1085.png)

How is the data encrypted and decrypted?

**Step 1 -** The client (browser) and the server establish a TCP connection.

**Step 2 -** The client sends a “client hello” to the server. The message contains a set of necessary encryption algorithms (cipher suites) and the latest TLS version it can support. The server responds with a “server hello” so the browser knows whether it can support the algorithms and TLS version.

The server then sends the SSL certificate to the client. The certificate contains the public key, hostname, expiry dates, etc. The client validates the certificate. 

**Step 3 -** After validating the SSL certificate, the client generates a session key and encrypts it using the public key. The server receives the encrypted session key and decrypts it with the private key. 

**Step 4 -** Now that both the client and the server hold the same session key (symmetric encryption), the encrypted data is transmitted in a secure bi-directional channel.
