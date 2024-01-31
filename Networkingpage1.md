## OSI Model and TCP/IP Network models 


The **OSI (Open Systems Interconnection) model** is a conceptual framework used to understand how different networking protocols and technologies interact within a network. It consists of seven distinct layers, each responsible for specific functions in the process of transmitting data from one point to another.

**Here's an overview of each layer in the OSI model:**

![OSI Model](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F8c53f73a-c6ec-45cc-afb5-4018ac97a488_1600x1085.png)

1) **Application Layer (Layer 7):**

* This is the topmost layer that interacts directly with the end-user applications and provides network services to user applications. 
* It includes protocols that users interact with directly, such as HTTP, SMTP, FTP, DNS, etc. 
* Responsible for tasks like data encryption, authentication, and formatting. 

2) **Presentation Layer (Layer 6):**

* Focuses on data representation, encryption, and translation. 
* Converts data into a format that the Application Layer can understand, ensuring that data from the Application Layer of one system can be read by the Application Layer of another system. 

3) **Session Layer (Layer 5):**

* Manages and establishes connections (sessions) between applications on different devices. 
* Responsible for controlling dialogues between devices, managing sessions, and ensuring data synchronization. 

4) **Transport Layer (Layer 4):**

* Provides end-to-end communication and ensures that data is delivered error-free and in the correct sequence. 
* Includes protocols like TCP (Transmission Control Protocol) and UDP (User Datagram Protocol). 
* Handles flow control, error correction, and data segmentation. 

5) **Network Layer (Layer 3):**

* Handles logical addressing and routing of data packets between different networks. 
* Key protocols in this layer include IP (Internet Protocol). 
* Determines the best path for data transmission based on network conditions and addresses. 

6) **Data Link Layer (Layer 2):**

* Responsible for node-to-node communication and provides reliable transit of data across the physical link. 
* Divided into two sublayers: LLC (Logical Link Control) and MAC (Media Access Control). 
* Performs tasks like framing, error detection, and flow control. 

7) **Physical Layer (Layer 1):**

* Deals with the physical transmission of data over the network medium. 
* Specifies hardware characteristics such as cables, connectors, voltages, and signaling methods. 
* Transmits raw bits over a physical medium. 


## **TCP/IP Network Model**

**TCP (Transmission Control Protocol)**
TCP is is designed to send packets across the internet and ensure the successful delivery of data and messages over networks. Many application-layer protocols build on top of TCP.

**UDP (User Datagram Protocol)**
UDP sends packets directly to a target computer, without establishing a connection first. UDP is commonly used in time-sensitive communications where occasionally dropping packets is better than waiting. Voice and video traffic are often sent using this protocol.


The TCP/IP model is a more practical and widely used networking model. It originated from the development of the Internet and consists of four interconnected layers:

**1) Application Layer:** Corresponds roughly to the top three layers of the OSI model (Application, Presentation, and Session). It includes protocols for various applications like HTTP (web browsing), SMTP (email), FTP (file transfer), etc.

**2) **Transport Layer**:** Equivalent to the OSI Transport Layer, responsible for end-to-end communication, ensuring data integrity, and managing the reliability of the connection. It mainly uses TCP and UDP.

**3) Internet Layer**: Similar to the OSI Network Layer, handles addressing, routing, and packet forwarding across networks. It uses IP (Internet Protocol) to accomplish these tasks.

**4) Link Layer:** Comparable to the OSI Data Link and Physical Layers. It deals with data transfer between devices on the same network and includes protocols for the physical transmission of data.


