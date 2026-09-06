# Chapter 1 — Introduction to web designing 

> **Web Designing and Publishing | NIELIT O Level (IT)**


This chapter introduces the basic concepts required to understand how the Web works. Before learning HTML, CSS and JavaScript, it is important to understand the Internet, WWW, websites, webpages, browsers, servers, URLs and the client-server model.

---

## 📚 Chapter Overview

# In this chapter, we will learn:
1. [Internet](#1-internet)
2. [History of Internet](#2-history-of-internet)
3. [World Wide Web (WWW)](#3-world-wide-web-www)
4. [Web Browser](#4-web-browser)
5. [Client-Server Architecture](#5-Client-Server Architecture)
6. [HTTP and HTTPS](#6-http-and-https)
7. [Webpage](#7-webpage)
8. [URL](#8-url)
9. [Website](#9-website)
10. [Working of a Website](#10-working-of-a-website)
11. [Types of Websites](#11-types-of-websites)
12. [Search Engine](#12-search-engine)
13. [Front End and Back End](#13-front-end-and-back-end)
14. [Scripting Language](#14-scripting-language)
15. [Responsive Web Design](#15-responsive-web-design)

---

## 1.  What is the Internet?

## English

The **Internet** is a globally connected network system that uses the **TCP/IP model** to transmit data through different communication media such as wired and wireless networks.
Hinglish

## HEnglish
Internet ek global network hai jo duniya bhar ke computers aur devices ko connect karta hai.

In simple words:

> **The Internet is a network of networks.**

It connects millions of computers, smartphones, servers and other devices around the world.

The Internet connects different types of networks, including:

- Private networks
- Public networks
- Business networks
- Academic networks
- Government networks

### Simple Example

When you send a WhatsApp message from your mobile phone to a friend:

```text
Your Mobile
     ↓
   Internet
     ↓
Friend's Mobile
```
## 2. History of Internet

The Internet did not develop in a single day. It evolved gradually through research, experiments, and technological developments over several decades.

### 1. Origin of ARPA

The Advanced Research Project Agency (ARPA) was established under the U.S. Department of Defense (DoD).

The initial objective was to connect computers so that researchers could share resources.

### 2. ARPANET Proposed — 1967

In 1967, ARPA presented the idea of ARPANET, a small network of computers.

The basic idea was that each host computer would be connected to a specialized computer called an:

IMP — Interface Message Processor

The IMP was used to help create the network connection between computers.

### 3. First ARPANET Connection — 1969

By 1969, ARPANET connected four nodes through IMPs:

University of California, Los Angeles (UCLA)
University of California, Santa Barbara (UCSB)
Stanford Research Institute (SRI)
University of Utah

A team of engineers at UCLA successfully sent the first computer message to another team at Stanford.

The First Message

The intended message was:

LOGIN

However, the system crashed after the first two letters:

LO

So, “LO” became the first successful message sent over ARPANET.

### 4. Development of TCP/IP — 1970s

During the 1970s, scientists Robert Kahn and Vinton Cerf developed TCP/IP.

TCP/IP provided a communication model and established standards for transmitting data between multiple networks.

TCP/IP
TCP → Transmission Control Protocol
IP  → Internet Protocol

TCP/IP later became fundamental to Internet communication.

#### 5. ARPANET Adopted TCP/IP — 1983

On January 1, 1983, ARPANET adopted TCP/IP.

After this, researchers increasingly connected networks together, gradually forming what became the modern Internet.

This is one of the most important milestones in Internet history.

### 6. World Wide Web — 1989

In 1989, Tim Berners-Lee proposed the idea of the World Wide Web (WWW).

The Web provided a way to access information through interconnected documents, websites and hyperlinks.

### 7. WWW Became Available — 1990

In 1990, the World Wide Web became available and helped make the Internet more popular among the general public.

The course material also notes that the commercial Web started in 1990.

Internet History — Quick Timeline
```
1967
│
├── ARPA proposed ARPANET
│
1969
│
├── ARPANET connected four nodes
├── First successful message: "LO"
│
1970s
│
├── Robert Kahn & Vinton Cerf developed TCP/IP
│
1983
│
├── ARPANET adopted TCP/IP
│
1989
│
├── Tim Berners-Lee proposed WWW
│
1990
│
└── WWW became available and popularized the Internet
```
### Key Takeaways
ARPA wanted to connect computers for resource sharing.
1967 → ARPANET idea was presented.
1969 → Four ARPANET nodes were connected.
1970s → TCP/IP was developed.
1983 → ARPANET adopted TCP/IP.
1989 → WWW was proposed by Tim Berners-Lee.
1990 → WWW became available and helped popularize the Internet.


## 3. World Wide Web (WWW)

The World Wide Web (WWW), commonly referred to as the Web, is one of the services provided through the Internet.

The idea of the WWW was proposed by Tim Berners-Lee in 1989, and the commercial Web started in 1990.

### What is WWW?

The World Wide Web (WWW) is a system used for accessing information and data online in the form of:

Websites
Webpages
Hyperlinks
Web resources

It provides a large repository of information in which documents are distributed across different locations and related documents are linked together.

### In Simple Words

WWW is a collection of interconnected web resources that users can access through a web browser over the Internet.

### Internet vs WWW

Internet and WWW are related, but they are not the same thing.

| Internet                                      | World Wide Web                               |
| --------------------------------------------- | -------------------------------------------- |
| Global network infrastructure                 | A service that operates over the Internet    |
| Connects networks and devices                 | Provides access to web information           |
| Uses networking technologies such as TCP/IP   | Uses websites, webpages and hyperlinks       |
| Provides the underlying communication network | Provides web-based information and resources |

## 4. Web Browser

A Web Browser is software used to access, interpret, and display webpages on the World Wide Web.

A web browser is also known as a Web Client because it sends requests to web servers and receives the requested web resources.

### Examples of Web Browsers

Some commonly used web browsers are:
```
Google Chrome
Mozilla Firefox
Microsoft Edge
Opera
Safari
Netscape Navigator
MS Internet Explorer

```

### What Does a Web Browser Do?

A web browser mainly performs the following tasks:
```
1.Accepts a website address or URL from the user.
2.Sends a request to the appropriate web server.
3.Receives the requested webpage/resources.
4.Interprets the webpage.
5.Displays the webpage on the user's screen.
```

## Real-World Scenario

Suppose you want to visit an NIELIT GKP website.

You open Google Chrome and enter:
```
https://regn.nielitvte.edu.in/
```
The browser acts as a client.

It sends a request to the web server:
```
Browser (Client)
       │
       │ Request
       ↓
   Web Server
       │
       │ Response
       ↓
Browser (Client)
```
The browser then interprets the received webpage and displays it.
 
## 5. Client-Server Architecture

Client-Server Architecture is a model in which a client requests a service or resource, and a server provides the requested service or resource.

In Web applications, the web browser acts as the client, while the web server hosts webpages and responds to requests.
```

                 REQUEST
Client ─────────────────────────→ Server
(Browser)                            Web Server
  │                                    │
  │                                    │
  │                              Processing
  │                                    │
  │                                    ↓
  ←─────────────────────────── RESPONSE
  ```

 ### Steps:-
 ```
1.User enters a website address in the browser.
2.Browser sends a request to the server.
3.Server receives and processes the request.
4.Server sends the requested webpage/resources as a response.
5.Browser interprets the response and displays the webpage.
```
### Real-World Scenario

Imagine a restaurant.

When a customer visits a restaurant:
```
Customer
   ↓
Places Order
   ↓
Restaurant Kitchen
   ↓
Prepares Food
   ↓
Food Delivered
   ↓
Customer
```
```
Customer = Client
Kitchen = Server
Order = Request
Food = Response
```
The same concept can be used to understand the Web:
```
Browser / Client
       ↓
    Request
       ↓
   Web Server
       ↓
   Processing
       ↓
    Response
       ↓
Browser / Client
```
### HTTP

- HTTP = Hyper Text Transfer Protocol

- HTTP is a protocol that defines the rules for communication between a Web Client and a Web Server.
- It work on PORT number 80.

- It is used to transfer different types of information over the World Wide Web, such as:
```
Text
Graphics
Images
Sound
Video
Multimedia
```
### Basic HTTP Communication
```
User
  ↓
Browser (Client)
  ↓
HTTP Request
  ↓
Web Server
  ↓
HTTP Response
  ↓
Browser
  ↓
Webpage
```
### HTTPS

- HTTPS = Hyper Text Transfer Protocol Secure

- HTTPS is an extension of HTTP that is used for secure communication between a web client and web server.
- It work on PORT number 443.

- It establishes an encrypted link between the client and server.

- HTTPS uses security technologies such as:
```
TLS — Transport Layer Security
SSL — Secure Socket Layer
```
