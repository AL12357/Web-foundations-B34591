# Web Foundations Lab

## Student
Name: MAWEJJE ALESHA
Student Number: S25D14/012

## Course
CSC1202 Web & Mobile Application Development

## Project Purpose
This project demonstrates the development workflow covered during the first three lessons.
The project demonstrates:
- basic project organisation
- HTML
- terminal commands
- Git version control
- GitHub
- Internet and Web concepts
- client/server communication
- DNS and HTTP concepts

## How to Run the Project
1. Download or clone the repository.
2. Open the project folder.
3. Open index.html using a modern web browser.

## What I Have Learned
During the first three lessons, I learned how to configure my local development environment using Node.js and VS Code. I gained a practical understanding of how client-server architecture operates via DNS and HTTP/HTTPS requests. Additionally, I learned how to track project history using Git commits and publish local repositories to GitHub.

## Internet Investigation

### Question 1
What domain name did I test?
Answer: google.com

### Question 2
What IP address was returned?
Answer: 172.16.7.206

### Question 3
What does DNS do?
Answer: DNS translates human-readable domain names into machine-readable IP addresses.

### Question 4
What does ping help us test?
Answer: Ping checks network connectivity and measures latency between your computer and a remote host.

## Browser Request Trace

1. **User enters a URL:** HTTPS is the protocol and example.com is the domain.
2. **Browser acts as the client:** The browser is the client because it requests a resource from another computer.
3. **DNS lookup occurs:** DNS translates the domain name into an IP address so the correct server can be located.
4. **Browser contacts the server:** Using the resolved IP address, the browser establishes communication with the web server.
5. **HTTP/HTTPS request is sent:** A request such as GET / asks the server for a resource.
6. **Server sends a response:** The server returns an HTTP response containing HTML or other resources such as CSS, JavaScript, and images.
7. **Browser renders the page:** The browser reads the returned content and displays the page to the user.

### Request Flow Diagram
USER
| enters URL
and 
BROWSER / CLIENT
| DNS lookup
and 
DNS SERVER
| returns IP address
and
BROWSER
| HTTP/HTTPS request
and
WEB SERVER
| HTTP response
and
BROWSER
| renders HTML
and
USER SEES WEB PAGE