## What is cloud?why it is used

The term "cloud" in technology typically refers to cloud computing, which involves the delivery of computing services—such as **servers, storage, databases,** **networking, software, analytics,** and more—over the internet (the "cloud") instead of relying on on-premises hardware and infrastructure.

**Cloud computing is used for several reasons:**

* **Scalability and Flexibility** 
* **Cost Efficiency** 
* **Accessibility and Remote Work** 
* **Reliability and Redundancy** 
* **Innovation and Agility** 


## What is Database?What are the different Types of DataBase?

A database is a structured collection of data that is organized and stored electronically in a computer system. It is designed to efficiently manage, store, retrieve, and manipulate data according to specific requirements and applications.

**Types of Database** 

**1)Relational DataBase**

**2)NoSql DataBase**

**3)Graph DataBase**

**4)Columnar DataBase**

**5)In-memory DataBase**

**6)Document Stores**

## Basics of SQL

SQL stands for Structured Query Language.It's a domain-specific language used in programming and designed for managing and querying data held in relational database management systems (RDBMS).

**Types of SQL Commands:**

* **Data Query Language (DQL)**: Used to retrieve data from the database. Example: 
**SELECT**

* **Data Manipulation Language (DML**): Used to manipulate data within the database. Example: **INSERT, UPDATE, DELETE** 

* **Data Definition Language (DDL)**: Used to define the database structure. Example: **CREATE TABLE, ALTER TABLE, DROP TABLE** 

* **Data Control Language (DCL)**: Used to control access to data within the database. Example: **GRANT, REVOKE** 

**Components of SQL:**

**Queries:** Used to retrieve specific data from the database.

**Clauses:** Such as **WHERE, ORDER BY, GROUP BY, HAVING,** etc., help filter, sort, and group data.
**Functions:** Provide built-in operations for manipulating data **(e.g., SUM, COUNT, AVG, MAX, MIN).**

**Constraints:** Rules applied to columns to enforce data integrity **(e.g., PRIMARY KEY, FOREIGN KEY, NOT NULL, UNIQUE).**

**Joins:** Used to combine data from multiple tables based on related columns.


## * HTTP Methods 

**HTTP (Hypertext Transfer Protocol)** defines several methods or verbs that specify the action to be performed on a resource identified by a URL. These methods provide different functionalities and capabilities for interacting with web servers and resources. Some of the commonly used HTTP methods include:


**GET:** The GET method is used to retrieve data from a specified resource.

**POST:** The POST method is used to submit data to a specified resource to be processed.

**PUT:** The PUT method is used to update or replace an existing resource on the server with the data provided in the request.

**DELETE:** The DELETE method is used to request the removal of a specified resource from the server.

**PATCH:** The PATCH method is used to apply partial modifications to a resource.

**HEAD:** The HEAD method is similar to GET but requests only the headers of the response, without the actual body content.

**OPTIONS:** The OPTIONS method is used to request information about the communication options available for a resource or server.

**TRACE:** The TRACE method is used to echo the received request back to the client. 

## * HTTP Headers 

HTTP headers are components of HTTP requests and responses that carry additional information about the messages being sent between a client (such as a web browser) and a server. These headers provide important metadata or instructions, influencing the way the message is processed, handled, or interpreted.

HTTP headers are divided into two main categories: 
* Request headers and 

* Response headers. 

**Request Headers:**

**Accept:** Indicates the media types that the client can process or is willing to receive in the response.

**User-Agent:** Identifies the software or application making the request, such as the browser or client type.

**Authorization:** Contains credentials for accessing protected resources (for example, in Basic or Bearer authentication).

**Cookie:** Sends stored cookies back to the server, allowing for stateful sessions.

**Host:** Specifies the domain name of the server being accessed by the client.

**Response Headers:**

**Content-Type:** Specifies the media type or format of the content in the response 

**Content-Length:** Indicates the size of the content in the response body in bytes.

**Cache-Control:** Instructs how caching should be handled by clients and proxies.

**Server:** Identifies the software and version running on the server.

**Set-Cookie:** Sets a cookie on the client-side for maintaining session state or other data.


## * HTTP Status code 

HTTP status codes are three-digit numeric codes returned by a server in response to a client's request made over the Hypertext Transfer Protocol (HTTP). These status codes provide information about the status of the request, indicating whether the request was successful, encountered an error, needs redirection, or requires further action by the client.

HTTP status codes are divided into five categories, each represented by a numeric range:

* **1xx - Informational:** These status codes indicate that the server has received the request and is continuing the process. 

**For example:**
100 - Continue
101 - Switching Protocols

* **2xx - Success:** These status codes indicate that the client's request was successfully received, understood, and processed by the server. 

**For example:**
200 - OK (Successful request)
201 - Created (Resource created successfully)
204 - No Content (The server successfully processed the request, but no content is returned)

* **3xx - Redirection:** These status codes indicate that further action is needed by the client to complete the request. 

**## For example:**
301 - Moved Permanently (Resource has been moved permanently to a new location)
302 - Found (Resource temporarily moved to a different URL)
304 - Not Modified (Client can use cached data, as the resource has not been modified)

* **4xx - Client Errors:** These status codes indicate that there was an error on the client's side of the request. It could be due to incorrect syntax, authorization issues, or unavailable resources. 

**For example:**
400 - Bad Request (The server cannot process the request due to a client error)
401 - Unauthorized (Authentication is required, and credentials are missing or invalid)
404 - Not Found (The requested resource could not be found on the server)

* **5xx - Server Errors:** These status codes indicate that there was an error on the server side in processing the request. 

**For example:**
500 - Internal Server Error (Generic server error; something went wrong on the server)
503 - Service Unavailable (The server is currently unable to handle the request due to temporary overload or maintenance)