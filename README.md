# Chapter 1 — Introduction to web designing 

> **Web Designing and Publishing | NIELIT O Level (IT)**


This chapter introduces the basic concepts required to understand how the Web works. Before learning HTML, CSS and JavaScript, it is important to understand the Internet, WWW, websites, webpages, browsers, servers, URLs and the client-server model.

---

# 📚 Table of Contents

## Chapter 1 — Introduction to Web Designing

### In this chapter, we will learn:
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

## Chapter 2 — Editors

### In this chapter, we will learn:
1. [What is an Editor?](#1-what-is-an-editor)
2. [Types of Editors](#2-types-of-editors)
3. [Text Editor](#3-text-editor)
4. [Code Editor](#4-code-editor)
5. [Syntax Highlighting](#5-syntax-highlighting)
6. [Auto-Completion](#6-auto-completion)
7. [Multiple Tabs](#7-multiple-tabs)
8. [Text Editor vs Code Editor](#8-text-editor-vs-code-editor)
9. [Notepad++](#3-notepad)
10. [Sublime Text](#4-sublime-text)

---
## Chapter 3 — Introduction to HTML

### In this chapter, we will learn:
1. [What is HTML?](#-introduction-to-html)
2. [History of HTML](#-history-of-html--short-notes)
3. [HTML5 Introduction](#-html5-introduction-and-basic-structure-of-html)
4. [Basic Structure of HTML](#3-html5-basic-structure)
5. [Explanation of Basic Tags](#4-explanation-of-basic-tags)
6. [Creating and Running an HTML File Using Notepad++](#-creating-and-running-an-html-file-using-notepad)
7. [HTML Tags and Their Types](#-html-tags-and-their-types)
8. [Paired Tags](#1-paired-tags)
9. [Empty Tags (Void Tags)](#2-empty-tags-void-tags)
10. [Container Tags](#types-of-html-tags)

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
## 11. Types of Website

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





## 10. Working of Website

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

## 13. Frontend and Backend

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

## 14. What is Scripting?

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
## 15. Responsive Design

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

//Editors
# Chapter 2: Editors

## 1. What is an Editor?

An **editor** is a software application used to create, write, edit and save text or code.

We can think of an editor as a **digital notebook** for writing.

### Simple Example

Just as we use a notebook to:

- Write notes
- Correct mistakes
- Add new text
- Save our work

we use an editor to:

- Write text
- Edit text
- Write computer code
- Save files

### Examples

- Notepad
- Notepad++
- Sublime Text
- Visual Studio Code

---

## 2. Types of Editors

Editors can mainly be divided into:

```
                Editors
                   ↓
        ┌──────────┴──────────┐
        ↓                     ↓
   Text Editors           Code Editors
```

> **Note:** In practice, the terms can overlap. Many modern code editors also work as advanced text editors.

---

## 3. Text Editor

A **text editor** is a program used to create, write, edit and save text files.

It is mainly used for simple text work.

### Example

**Notepad** is a simple text editor.

We can use it to write:

```
My Name is Rahul.
I am learning Web Designing.
```

We can save the file as:

```
notes.txt
```

### Features of a Text Editor

- Simple to use
- Write and edit text
- Open files
- Save files
- Find text
- Replace text

### Example

```
Notepad
   ↓
Write Text
   ↓
Edit Text
   ↓
Save File
```

---

## 4. Code Editor

A **code editor** is an editor specially designed for writing and editing computer programs or source code.

It provides extra features that make coding easier.

### Examples

- Notepad++
- Sublime Text
- Visual Studio Code

### Features of Code Editors

- Syntax Highlighting
- Auto-completion
- Multiple Tabs
- Find and Replace
- Code Formatting
- Support for different programming languages

---

## 5. Syntax Highlighting

**Syntax highlighting** displays different parts of code in different colors/styles so that code is easier to read.

### Example:

```
<h1>Hello World</h1>
<p>Welcome</p>
```

The editor highlights tags, attributes and other parts differently.

### Simple Meaning

> Syntax highlighting makes code easier to read and understand.

---

## 6. Auto-Completion

**Auto-completion** helps us while writing code by suggesting possible words, tags, functions or properties.

For example, while writing:

```
<ht
```

the editor may suggest:

```
<html>
```

### Simple Meaning

> Auto-completion helps us write code faster.

---

## 7. Multiple Tabs

Code editors allow us to open several files at the same time.

For example:

```
index.html | style.css | script.js
```

We can easily switch between these files.

---

# 3. Notepad++

## What is Notepad++?

**Notepad++** is a free and lightweight editor used to write and edit text and computer code.

It is very useful for learning **HTML, CSS, JavaScript** and other programming languages.

---

## Basic Features

- Easy to use
- Fast and lightweight
- Syntax highlighting
- Multiple files can be opened in tabs
- Supports many programming languages
- Find and Replace option

---

## Basic Menus of Notepad++

The main menu of Notepad++ contains options such as:

```
File | Edit | Search | View | Encoding | Language | Settings | Tools | Macro | Run | Plugins | Window | ?
```

---

### 1. File

Used to work with files.

**Important options:**

- **New** → Create a new file
- **Open** → Open an existing file
- **Save** → Save the current file
- **Save As** → Save with a new name/location
- **Close** → Close the file

---

### 2. Edit

Used to edit the text or code.

**Important options:**

- **Undo** → Remove the last change
- **Redo** → Bring back the undone change
- **Cut** → Remove selected text
- **Copy** → Copy selected text
- **Paste** → Insert copied text
- **Select All** → Select all text

---

### 3. Search

Used to find or change text.

**Important options:**

- **Find** → Search for text
- **Replace** → Replace one text with another
- **Find Next** → Find the next occurrence

---

### 4. View

Used to change how the editor looks.

For example:

- Show/Hide panels
- Zoom in/out
- Show tabs
- Change display options

---

### 5. Language

Used to select the programming language for syntax highlighting.

For example:

- HTML
- CSS
- JavaScript
- PHP
- Python

---

### 6. Settings

Used to change editor settings and preferences.

---

### 7. Plugins

Used to add extra features to Notepad++.

---

## ⭐ Remember

> **Notepad++ = Write + Edit + Save Code**

---

# 4. Sublime Text

## What is Sublime Text?

**Sublime Text** is a fast and lightweight code editor used to write and edit computer code.

It supports many programming languages and provides useful features for programmers.

---

## Basic Features

- Fast and lightweight
- Simple interface
- Syntax highlighting
- Multiple tabs
- Multiple selection
- Powerful search
- Supports many programming languages

---

## Basic Menus of Sublime Text

The main menu contains:

```
File | Edit | Selection | Find | View | Goto | Tools | Project | Preferences | Help
```

---

### 1. File

Used to work with files.

**Important options:**

- **New File** → Create a new file
- **Open File** → Open an existing file
- **Save** → Save the file
- **Save As** → Save with another name/location
- **Close File** → Close the file

---

### 2. Edit

Used to edit code or text.

**Important options:**

- Undo
- Redo
- Cut
- Copy
- Paste
- Select All

---

### 3. Selection

Used to select text or multiple parts of code.

---

### 4. Find

Used to search and replace text.

**Important options:**

- **Find** → Search text
- **Find Next** → Find next occurrence
- **Replace** → Replace text

---

### 5. View

Used to control how the editor looks.

For example:

- Zoom
- Side Bar
- Layout
- Word Wrap

---

### 6. Goto

Used to quickly move to a particular:

- Line
- File
- Symbol

---

### 7. Tools

Provides tools and options useful for working with code.

---

### 8. Project

Used to manage files and folders as a project.

---

### 9. Preferences

Used to change Sublime Text settings and appearance.

---

### 10. Help

Used to get help and information about Sublime Text.





# 🌐 Introduction to HTML

## 1. What is HTML?

**HTML** stands for **HyperText Markup Language**.

 HTML is the **standard markup language** used to create the **structure** of a webpage.

  Markup means using special tags or symbols to format and structure text.

HTML tells the browser:

> What content should be present on the webpage?

For example:

- Heading
- Paragraph
- Image
- Link
- Button
- Table
- Form

### Simple Definition

> **HTML gives structure to a webpage.**

---

## 🚗 Real-Life Example: A Car

We can understand **HTML, CSS and JavaScript** using a car.

A car has:

- **Structure / Body**
- **Design / Appearance**
- **Controls / Actions**

A webpage also has these three parts.
```
Car                         Website

Structure                   HTML
Design                      CSS
Actions / Controls          JavaScript
```

# 📚 History of HTML — 

HTML was invented by Tim Berners-Lee in 1991 while working at CERN.

He is also known as the inventor of the World Wide Web (WWW)..

---

## 🕐 Timeline
```
| Year     | HTML Version | Main Point                                  |
| -------- | ------------ | ------------------------------------------- |
| **1989** | Beginning    | Tim Berners-Lee proposed the World Wide Web |
| **1991** | HTML 1.0     | Basic HTML and simple webpages              |
| **1995** | HTML 2.0     | More HTML features                          |
| **1997** | HTML 3.2     | Tables and Forms                            |
| **1999** | HTML 4.01    | Better structure, styles and scripting      |
| **2014** | HTML5        | Audio, Video, Canvas, modern web features   |
| **2017** | HTML 5.2     | Further improvements                        |

```

# 🌐 HTML5 Introduction and Basic Structure of HTML

## 1. What is HTML5?

**HTML5** is a modern version of HTML (HyperText Markup Language) used to create and structure webpages.

HTML5 helps us create webpages with:

- Text
- Images
- Links
- Forms
- Audio
- Video
- Graphics
- Other interactive content

### Simple Definition

> **HTML5 is used to create and structure modern webpages.**

---

## 2. Why HTML5?

HTML5 provides many useful features for modern websites.

### Main Features

- 🎵 Supports Audio
- 🎥 Supports Video
- 🖼️ Supports Graphics using Canvas
- 📝 Provides better Forms
- 📱 Works well with different devices
- 🧩 Provides Semantic Tags such as `<header>`, `<nav>`, `<section>`, `<article>`, and `<footer>`



---

## 3. HTML5 Basic Structure

Every HTML5 webpage follows a basic structure.

```html
<!DOCTYPE html>

<html>

<head>
    <title>My First Web Page</title>
</head>

<body>

    <h1>Welcome to HTML5</h1>
    <p>This is my first webpage.</p>

</body>

</html>
```

---

## 4. Explanation of Basic Tags

### `<!DOCTYPE html>`

It tells the browser that the document is an **HTML5 document**.

```html
<!DOCTYPE html>
```

**Remember:**

> DOCTYPE → Tells the browser which HTML standard is being used.

---

### `<html>`

It is the **main/root element** of the HTML document.

```html
<html>
    ...
</html>
```

All other HTML elements are normally placed inside `<html>`.

**Remember:**

> `<html>` → Contains the complete HTML document.

---

### `<head>`

The `<head>` contains **meta information about the webpage**.

```html
<head>
    <title>My Website</title>
</head>
```

It can contain:

- `<title>`
- Metadata
- Links to CSS
- Other page information

> The content of `<head>` is generally **not displayed** as the main page content.

---

### `<title>`

The `<title>` specifies the **title of the webpage**.

```html
<title>My First Web Page</title>
```

It normally appears in the **browser tab**.

```
Browser Tab
┌──────────────────────────┐
│ My First Web Page        │
└──────────────────────────┘
```

---

### `<body>`

The `<body>` contains the **visible content** of the webpage.

```html
<body>

    <h1>Welcome</h1>
    <p>Hello Students!</p>

</body>
```

It can contain:

- Headings
- Paragraphs
- Images
- Links
- Tables
- Forms
- Videos
- Buttons

**Remember:**

> `<body>` → What the user sees on the webpage.



# 📝 Creating and Running an HTML File Using Notepad++

## Step 1: Open Notepad++

1. Click **Start Menu**.
2. Search for **Notepad++**.
3. Open **Notepad++**.

---

## Step 2: Create a New File

Go to:

```
File → New
```

Or use the shortcut:

```
Ctrl + N
```

---

## Step 3: Write HTML Code

Type HTML code in Notepad++.

Example:

```html
<!DOCTYPE html>
<html>

<head>
    <title>My First Webpage</title>
</head>

<body>

    <h1>Hello Students!</h1>
    <p>Welcome to Web Designing.</p>

</body>

</html>
```

---

## Step 4: Save the File

Go to:

```
File → Save As
```

Choose the location where you want to save the file.

For example:

```
Desktop
```

Give the file a name with the **.html** extension:

```
myfirstpage.html
```

Then click **Save**.

### Important

The file must end with:

```
.html
```

Example:

```
myfirstpage.html
```

---

## Step 5: Run the HTML File

1. Go to the folder where you saved the file.
2. Find:

```
myfirstpage.html
```

3. Then **double-click** the file.

---

## Step 6: View the Output

The HTML file will open in your **default web browser**.

You will see:

```
Hello Students!

Welcome to Web Designing.
```


# 🏷️ HTML Tags 

## What is an HTML Tag?

An **HTML tag** is a special keyword written inside **angle brackets** `< >`.

Tags are used to tell the browser **how to display or organize content**.

### Example:

```html
<h1>Welcome</h1>
```

Here:

```
<h1>       → Opening Tag
Welcome    → Content
</h1>      → Closing Tag
```

---

## Types of HTML Tags

There are mainly **3 types**:

```
HTML Tags
   │
   ├── 1. Paired Tags
   ├── 2. Empty Tags
   └── 3. Container Tags
```

---

## 1. Paired Tags

**Paired tags** have two tags:

- **Opening tag**
- **Closing tag**

They contain **content** between them.

### Example

```html
<h1>Welcome</h1>
```

```
<h1>       → Opening
Welcome    → Content
</h1>      → Closing
```

### More Examples

```html
<p>This is a paragraph.</p>

<b>Bold Text</b>

<i>Italic Text</i>
```

### Remember

> **Paired Tag = Opening Tag + Content + Closing Tag**

---

## 2. Empty Tags (Void Tags)

**Empty tags** do **not** have a closing tag.

They are used to **insert or add** something to the webpage.

### Examples

```html
<br>
<hr>
<img>
<input>
<meta>
<link>
```