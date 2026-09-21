# Introduction to Ip
* Encapsulation of data is very important
* Allows for more efficient data transfer
* Diagram of each payload (Client to server)
  * Ethernet header -- Ethernet payload -- Ethernet trailer
  * Ethernet header -- IP -- IP payload -- Ethernet trailer
  * Ethernet header -- IP -- TCP -- TCP payload -- Ethernet trailer
  * Ethernet header -- IP -- TCP -- HTTP data -- Ethernet trailer
  * Either TCP or UDP data
    * TCP and UDP are layer 4 (session)
    * Multiplexing
    * Allows for many applications at the same time
   
## TCP
* Connection-oriented
  * Formal connection
* Reliable delivery
  * Recovery from errors
  * Manage errors/out of order messages
* Flow control

## UDP
* Connectionless
  * No formal connection
* Unreliable delivery
  * No error recovery
  * No reordering of data
  * No way to tell that data has been delivered
* No flow control

## How to transport data
* IP is given a delivery IP address
* TCP and UDP ports determine where the data actually goes within a network
  * Port # such as 80, 443, 22 or such
 
## IPv4 sockets
* Server IP address, protocol, server application port number
* Client IP address, protocol, client port number
* Non-ephemeral ports -- permanent port numbers
  * Ports 0-1023
  * Usually on a server or service
* Ephemeral ports -- Temporary port numbers
  * Ports 1024-65535
* Any device can use any port number, no actual limits
* TCP and UDP are separate, 2 applications can use the same port # as long as the protocols are different
