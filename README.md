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
5. [Client-Server Architecture](#5-client-server-architecture)
6. [HTTP and HTTPS](#6-http-and-https)
7. [URL](#7-url)
8. [Webpage](#8-webpage)
9. [Website](#9-website)
10. [Working of a Website](#10-working-of-a-website)
11. [Types of Websites](#11-types-of-websites)
12. [Search Engine](#12-search-engine)
13. [Front End and Back End](#13-front-end-and-back-end)
14. [Scripting Language](#14-scripting-language)
15. [Responsive Web Design](#15-responsive-web-design)

---

## 1. Internet

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
## 6. HTTP and HTTPS

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
## 7. URL 

- It stans for (Uniform Resource Locator).
- A URL (Uniform Resource Locator) is the unique address of a web page on the internet. It tells the browser where to find the resource such as a web page, image, file, etc.

In simple words:

- A URL tells the browser where a resource is located and how it should be accessed.

Example
```
https://www.regn.nielitvte.edu.in/courses
```
### 1. Structure of a URL

A URL can contain the following main parts:
```
https://www.nielit.gov.in:443/courses
│       │              │   │
│       │              │   └── Path
│       │              └────── Port
│       └───────────────────── Host
└───────────────────────────── Protocol
```
Main Components
```
| Component    | Description                                                   | Example           |
| ------------ | ------------------------------------------------------------- | ----------------- |
| **Protocol** | Defines how the resource should be accessed                   | `https`           |
| **Host**     | Identifies the server/domain hosting the resource             | `www.nielit.gov.in` |
| **Port**     | Identifies the communication port used by the service         | `443`             |
| **Path**     | Specifies the location of a particular resource on the server | `/courses`        |
```

Note: The port number is often not written in a URL because the browser uses the default port for the selected protocol.

### 2. Protocol

- The protocol specifies the rules used for communication between the client and the server.

Common web protocols include:
```
http://
https://
```

### 3. Host

- The host identifies the server or domain where the requested resource is located.

Example:
```
https://www.regn.nielitvte.edu.in/courses
        └──────────────┘
              Host
```
Here:
```
www.regn.nielitvte.edu.in
```
is the host.

The host commonly contains a domain name and may include a subdomain.

### 4. Port

A port identifies a communication endpoint on a server.

Example:
```
https://www.nielit.gov.in:443/courses
                     └───┘
                     Port
```

Common default web ports:
```
| Protocol | Default Port |
| -------- | -----------: |
| HTTP     |       80 |
| HTTPS    |      443|
```

For example:
```
http://regn.nielitvte.edu.in
```
is normally equivalent to:
```
http://regn.nielitvte.edu.in:80
```
Similarly:
```
https://regn.nielitvte.edu.in
```
normally uses:
```
https://regn.nielitvte.edu.in:443
```
### 5. Path

The path specifies the location of a particular resource on the server.

Example:
```
https://www.nielit.gov.in/courses/web-design
                         └────────────────┘
                                Path
```

Here:

/courses/web-design

is the path.

## 8. Webpage
- A webpage is a single page on the Internet.
- It is displayed using a web browser.
- A webpage is mainly created using HTML.
- A webpage can contain:
```
Text
Images
Videos
Links
Buttons
Forms
```
Every webpage can have a URL (web address).
### Example

Suppose we have a website:
```
https://regn.nielitvte.edu.in/
```
It may have:
```
Home → One webpage
About → One webpage
Courses → One webpage
Contact → One webpage
```
## 9. Website
 - A website is a collection of related webpages.
 - All webpages are connected to each other using links (hyperlinks).
 - A website has a Home Page, which is usually the first page we see.
 - A website is accessed using a domain name or URL.
 - A website can contain:
```
Text
Images
Videos
Links
Forms
Buttons
```
Example:
```
www.nielit.gov.in
```
 - It may contain different webpages such as:
```
Home
About Us
Courses
Notices
Contact Us
```
### Types of Website

 - There are mainly two types of websites:

### 1. Static Website
 - Content is fixed or predefined.
 - Content usually remains the same for users.
 - There is generally little or no user interaction.
 - Usually does not require a database.
 - Commonly created using HTML, CSS and JavaScript.
 - Changes are usually made manually.

### Examples
```
College information website
Company profile website
Personal portfolio website
```
##### Static website = "Website with mostly fixed content."
### 2. Dynamic Website
 - Content can change according to the user or request.
 - Provides more user interaction.
 - Usually uses a database.
 - Uses both front-end and back-end technologies.
 - Content can be generated in real time.

### Examples
```
Facebook
Online shopping websites
Online banking websites
Email websites
```
#####  Dynamic website = "Website where content can change according to users or data"

Real world  Example

Think of a book:
```
📖 Website → Complete book
📄 Webpage → One page of the book
🌐 URL → Address of that page
```





# 10. Working of Website

## 🌐 Introduction

- When we type a website address (URL) in a browser and press Enter, several steps happen behind the scenes before the website appears on our screen.

- **Basic Flow**

```
User
  ↓
Browser (Enter URL)
  ↓
DNS Lookup
  ↓
Connect to Server
  ↓
Send Request
  ↓
Server Processes the Request
  ↓
Response
  ↓
Browser Displays the Website
```

---

## 1. Enter URL

- First, the user enters a website address in the browser.

Example:

```
https://www.nielit.gov.in
```

- The URL tells the browser which website the user wants to open.

---

## 2. DNS Lookup

- The browser asks the DNS (Domain Name System) to find the IP address of the website.

- **Domain Name → IP Address**

For example:

```
www.nielit.gov.in → IP Address
```

### Simple Example

- DNS works like a phone directory.

- We remember a person's name, but the phone directory helps us find their phone number.

### Similarly:

```
Website Name → DNS → IP Address
```

---

## 3. Connect to Server

- After getting the IP address, the browser connects to the web server using the Internet.

- The server is the computer/system where the website and its resources are hosted.

---

## 4. Send Request

- The browser sends an HTTP/HTTPS request to the server.

For example:

```
/index.html
```

It means:

- "Please send me the webpage."

The request may ask for:

```
HTML
CSS
JavaScript
Images
Other website resources
```

---

## 5. Server Processes the Request

- The server receives the request and processes it.

- For a simple website, the server may directly provide the required files.

- For a dynamic website, the request may go to the backend application.

- The backend may also communicate with a database to get required information.

---

## 6. Server Sends Response

- After processing the request, the server sends a response back to the browser.

The response can contain:

```
HTML
CSS
JavaScript
Images
Data
```

---

## 7. Browser Displays the Website

- The browser receives the files and processes them.

```
HTML → Structure
CSS → Design
JavaScript → Interactivity
```

The browser combines these resources and renders the webpage on the screen.

```
HTML + CSS + JavaScript
          ↓
     Browser Rendering
          ↓
     Webpage Displayed
```

---

## 🍔 Real-Life Example: Ordering Food

- Website working can be compared with ordering food in a restaurant.

```
| Website           | Restaurant                 |
| ----------------- | -------------------------- |
| Enter URL         | Place an order             |
| DNS Lookup        | Waiter checks your order   |
| Connect to Server | Waiter goes to kitchen     |
| Send Request      | Waiter gives order to chef |
| Server Processes  | Chef prepares food         |
| Server Response   | Waiter brings food         |
| Browser Displays  | You receive and enjoy food |
```

### Easy to Remember

```
Order → Process → Prepare → Deliver → Receive
```

Similarly:

```
Request → Process → Generate → Response → Display
```

# 🖥️ Frontend and Backend

## Introduction

A website mainly has two parts:

```
Frontend + Backend
```

---

## 1. Frontend — What You See

- Frontend is the part of a website that we can see and use.
- It runs in the web browser.

### Frontend includes:

```
Buttons
Menus
Images
Text
Forms
Colors
Website layout
```

### Technologies:

```
HTML + CSS + JavaScript
```

### Example:

In a food-ordering website, we can see:

```
🍔 Burger
₹150

[ Order Now ]
```

- The menu, burger image, price and Order Now button are **frontend**.

---

## 2. Backend — What Happens Behind the Scene

- Backend is the part of the website that the user normally cannot see.
- It works on the server.

### Backend:

```
Receives the user's request
Processes the request
Checks information
Works with the database
Sends the result back to the frontend
```

### Backend Technologies

Examples:

```
PHP
Python
Node.js
Java
```

---

## 🔄 How Frontend and Backend Work Together

Suppose you click:

```
[ Order Now ]
```

### The process is:

```
FRONTEND
   ↓
User clicks "Order Now"
   ↓
Request
   ↓
BACKEND
   ↓
Processes the order
   ↓
DATABASE
   ↓
Saves order
   ↓
BACKEND
   ↓
Response
   ↓
FRONTEND
   ↓
"Order Confirmed!"
```

---

## 🍔 Simple Real-Life Example

- Think about a restaurant.

### Frontend = Dining Area + Menu

- The customer sees:

```
Menu
Food
Price
Order Button
```

### Backend = Kitchen + Staff

Behind the scene:

```
Receive Order
      ↓
Check Food
      ↓
Prepare Order
      ↓
Process Payment
      ↓
Confirm Order
```

---

## 🧠 Remember

> 🖥️ **Frontend = What You See**

> ⚙️ **Backend = What Happens Behind the Scene**

---

## 📊 Frontend vs Backend (Quick Comparison)
```

| Frontend               | Backend                       |
| ---------------------- | ----------------------------- |
| What you see           | What happens behind the scene |
| Runs in browser        | Runs on server                |
| HTML, CSS, JavaScript  | PHP, Python, Node.js etc.     |
| Buttons, menus, images | Processing, database, login   |
| User interacts with it | User normally doesn't see it  |
```




//Client, Server and Scripting Languages


# 🌐 Client, Server and Scripting Languages

## 1. What is a Client?

A **client** is a device or software that sends a request to a server.

In web development, the **web browser** acts as a client.

### Examples of Clients
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Mobile Browser
- Laptop/Desktop browser

### Simple Example
When you open an online shopping website on your laptop:

> **Laptop + Browser = Client**

The client asks the server for information.

---

## 2. What is a Server?

A **server** is a computer that provides information or services to the client.

A web server can:
- Store website files
- Receive requests
- Process requests
- Send responses to the client
- Work with databases

### Simple Example
When you open a website:

```
Client                    Server
Browser  ─── Request ───> Server
Browser  <── Response ─── Server
```

### 🍽️ Real-Life Example
Think about a restaurant:

```
Customer → places order → Kitchen
Customer ← receives food ← Kitchen
```

Similarly:

```
Client → sends request → Server
Client ← receives response ← Server
```

---

## 3. What is Scripting?

**Scripting** means writing instructions in a programming/scripting language to make a webpage or application perform a task.

For example:
- Check a form
- Show a message
- Validate an email
- Login a user
- Save information
- Fetch information from a database

---

## 4. Types of Scripting

In web development, scripting is mainly divided into two types:

```
             Scripting
                │
        ┌───────┴────────┐
        ↓                ↓
 Client-Side         Server-Side
 Scripting           Scripting
        ↓                ↓
    Browser            Server
```

---

## 5. Client-Side Scripting

### Meaning
**Client-side scripting** is scripting that runs in the user's browser.

The most common client-side scripting language is:
- **JavaScript**

### Simple Flow
```
User
 ↓
Browser
 ↓
JavaScript
 ↓
Result
```

### Example
Suppose a user enters an incorrect email:

```
Email: abc
```

JavaScript can immediately show:

> Please enter a valid email address.

The page does not necessarily need to contact the server just to perform this basic validation.

### Uses of Client-Side Scripting
JavaScript can be used for:
- Form validation
- Button actions
- Animations
- Changing webpage content
- Showing/hiding elements
- Creating interactive webpages

### Remember
> **Client-side scripting runs in the browser.**

---

## 6. Server-Side Scripting

### Meaning
**Server-side scripting** is scripting that runs on the server.

Examples:
- PHP
- Python
- Node.js

### Simple Flow
```
User
 ↓
Browser
 ↓
Request
 ↓
Server
 ↓
Server-Side Script
 ↓
Database
 ↓
Response
 ↓
Browser
```

### Example: Login
Suppose a user enters:

```
Username: student
Password: 12345
```

When the user clicks Login:
1. Browser sends the login request.
2. Server receives the request.
3. Server-side program checks the username and password.
4. Server may check the database.
5. Server sends the result back.
6. Browser displays the result.

```
Browser
   ↓
Login Request
   ↓
Server
   ↓
PHP / Python / Node.js
   ↓
Database
   ↓
Result
   ↓
Browser
```

### Uses of Server-Side Scripting
It is used for:
- Login and registration
- Database operations
- User authentication
- Payment processing
- Saving data
- Fetching data
- Generating dynamic content

### Remember
> **Server-side scripting runs on the server.**

---

## 7. Client-Side vs Server-Side Scripting
```
| Client-Side Scripting              | Server-Side Scripting               |
| ---------------------------------- | ----------------------------------- |
| Runs in the browser                | Runs on the server                  |
| Mainly JavaScript                  | PHP, Python, Node.js etc.           |
| Used for webpage interaction       | Used for server processing          |
| Can validate forms                 | Can check data with database        |
| Makes pages interactive            | Handles business logic              |
| User can see the result in browser | Processing happens behind the scene |
```



//Responsive design
# 📱 Responsive Design

## What is Responsive Design?

**Responsive Design** means making a website that works properly on different screen sizes.

The website automatically changes its layout according to the device.

```
        ONE WEBSITE
             ↓
   ┌─────────┼─────────┐
   ↓         ↓         ↓
Desktop    Tablet    Mobile
   ↓         ↓         ↓
Different screen sizes
             ↓
      Website adjusts
```

---

## Simple Example

The same website may look like this:

### 💻 Laptop/Desktop

```
Home | About | Courses | Contact
--------------------------------
      Course 1 | Course 2
```

### 📱 Mobile

```
☰ Menu
--------
Course 1
--------
Course 2
```

The website is the **same**, but its **layout changes** according to the screen.

---

## Why is Responsive Design Needed?

People use websites on different devices:

- 💻 Laptop
- 🖥️ Desktop
- 📱 Mobile
- 📲 Tablet

A responsive website makes the website **easy to see and use** on all these devices.

---

## Main Features

A responsive website:

- Adjusts its layout
- Adjusts images
- Adjusts text
- Changes the menu
- Fits different screen sizes
- Provides a better user experience

---

## How is it Created?

Responsive websites are mainly created using:

```
HTML → Structure
CSS → Design & Layout
JavaScript → Interaction
```

**CSS Media Queries** are commonly used to change the design for different screen sizes.

---

## 🌍 Real-Life Example

Suppose you open an online shopping website on your **laptop**.

You see:

```
Logo | Home | Products | Cart | Profile
```

Now you open the same website on your **mobile**.

You may see:

```
☰ Logo              🛒
```

The website **automatically adjusts** itself for the smaller screen.

---

## ⭐ Remember This

> **Responsive Design = Same Website + Different Screen Sizes**

```
💻 Desktop
     ↓
📲 Tablet
     ↓
📱 Mobile
```


