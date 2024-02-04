
# [Everything you need to know about HTTP](https://cs.fyi/guide/http-in-depth)

* HTTP is a TCP/IP-based application layer communication protocol that standardizes how clients and servers communicate with each other.

* HTTP itself depends on TCP/IP to get requests and responses between the client and server. By default, TCP port 80 is used, but other ports can also be used. HTTPS, however, uses port 443.

* Three Way Handshake
    Three-way handshake in it’s simples form is that all the TCP connections begin with a three-way handshake in which the client and the server share a series of packets before starting to share the application data.

    SYN - Client picks up a random number, let’s say x, and sends it to the server.
    SYN ACK - Server acknowledges the request by sending an ACK packet back to the client which is made up of a random number, let’s say y picked up by server and the number x+1 where x is the number that was sent by the client
    ACK - Client increments the number y received from the server and sends an ACK packet back with the number y+1

* HTTP/1.0: one request per connection and the connection was closed as soon as the request was fulfilled which resulted in accute performance hit and latency problems

* HTTP/1.1: connections weren’t closed by default and were kept open which allowed multiple sequential requests. To close the connections, the header Connection: close had to be available on the request. Clients usually send this header in the last request to safely close the connection.

* SPDY - 2009 (Google) : The features of SPDY included, multiplexing, compression, prioritization, security; it's a layer on HTTP

* HTTP/2.0 (1.1 + SPDY) : for low latency transport of content
