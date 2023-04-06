# APIs

## API stands for: Application Programming Interface

It is a set of rules that enable different applications to communicate with each other. It can be any software that performs a specific task and the interface is a point where two applications communicate.

## Why is everyone using APIs?!

APIs are extremely beneficial to the development of applications and services, as well as the integration and management of existing ones.

## Types of APIs

## Certain protocols have been developed to provide users with a set of API **specifications**, that create accepted data types, commands and syntax. The protocols facilitate standardized information exchange.
### SOAP (Simple Object Access Protocol): Built with XML, SOAP enables and the sending and receiving of data through SMTP and HTTP. SOAP APIs make it make it easier to share information between apps or software components that are running in multiple environments and different languages.

### REST(Representational State Transfer): REST is a way for two computer/programs to communicate with each other. They can receive, delete, edit or send information to the server. 
### The six guiding principles or Constraints of REST are:

* Uniform Interface
* Client-Server
* Stateless
* Cacheable
* Layered architecture
* Code on demand (optional).

### Stateless
#### Suppose we have an API where we want to log in and order some goods, the API deployed on many servers can serve many requests, even from the same account without storing the authentication details or provided token state. Every time client is making a request it will send the authentication details as well as the other required information and that request can be processed easily at the server side as it includes all the information needed to fulfill the request.

### Caching
#### Caching is the ability to store copies of frequently accessed data in several places along the request-response path.

## What is **HTTPS**?
### Hypertext Transport (or Transfer) Protocol, the data transfer protocol used on the World Wide Web. 

## 5 HTTP verbs and what they do: GET, POST, PUT, PATCH, DELETE
### The most common HTTP verbs are GET, POST, PUT, and DELETE, which are used to retrieve, create, update, and delete resources

## HTTP - Response Structure
![image](https://user-images.githubusercontent.com/129324316/230402298-b7355c25-92bf-4842-9dc8-9020123bb9cc.png)
A simple response from the server contains the following components:

* HTTP Status Code 
* Headers (Example – Content-Type: html)
* An empty line.
* A message body which is optional.
* All the lines in the server response should end with a carriage return and line feed. Similar to request, the empty line in a response also should only have     carriage return and line feed without any spaces.


## HTTP - Request Structure
![image](https://user-images.githubusercontent.com/129324316/230404248-f7c982e6-123a-4e7d-9813-b83f8641239d.png)
A simple request message from a client computer consists of the following components:

* A request line to get a required resource, for example a request GET /content/page1.html is requesting a resource called /content/page1.html from the server.
* Headers (Example – Accept-Language: EN).
* An empty line.
* A message body which is optional.
* All the lines should end with a carriage return and line feed. The empty line should only contains carriage return and line feed without any spaces.



