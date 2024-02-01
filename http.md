What is the difference between HTTP1.1 and HTTP2?

Introduction

The Hypertext Transfer Protocol, or HTTP,is a protocol which is used to request a data from client computer to a remote web server through the internet. the response to the request also happens under the Hypertext Transfer Protocol.


    -> requesting for data.

        client computer(Browser) --------- through the internet --------> remote web server
   
    -> responsing for the asked Request.
      
        client computer(Browser) <--------- through the internet -------- remote web server


HTTP is also known as HTTPS, where 'S' stands for secured which means that the requested data/response data is safe and secured.


--> the difference between HTTP1.1 and HTTP2

HTTP1.1 was first published in the early 1997. It was published only few months after the HTTP1.0. whereas the HTTP2 was officially standardized in May 2015.
HTTP2 came in when the HTTP1.1 was facing difficulties to handle the complex web pages and some of them were even applications in their own right. More visual media was displayed and the volume and size of scripts adding interactivity also increased. Much more data was transmitted over significantly more HTTP requests and this created more complexity and overhead for HTTP1.1 connections.Therefore HTTP2 was made to handle all these advanced difficulties like multiplexing,binary protocol leading to faster and more efficient web communication compared to HTTP1.1.

1) Header Size:

=> HTTP1.1: Headers are sent with each request and response, contributing to increased overhead.
=> HTTP2 Header size is reduced due to header compression, resulting in lower overhead.

2) Connection reuse:

=> HTTP1.1: Multiple connections are required to fetch resources in parallel, leading to additional latency.
=> HTTP2: A single connection can be reused for multiple requests, reducing latency.

3) Prioritization:

=> HTTP1.1: Requests are processed in the order they are received.
=> HTTP2: It allows for stream prioritization, enabling more important resources to be loaded first.

4) Binary Protocol:

=> HTTP1.1: It uses a text-based protocol, which is human-readable but can be less efficient in terms of parsing and transmission.
=> HTTP2: It is a binary protocol, making it more compact and efficient for both parsing and transmission.
 
5) Header Compression:

=> HTTP1.1: Headers are not compressed, and redundant information is often resent with each request and response.
=> HTTP2: It uses header compression, which reduces overhead by compressing repeated header fields.

In summary,HTTP2 aims to improve performance by introducing features like multiplexing, header compression, and server push, leading to faster and more efficient web communication compared to HTTP1.1.

