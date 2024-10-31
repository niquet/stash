# Computer Networks

- Broad overview of computer networking and the internet
- Structure
  - Basic terminology and concepts
  - Basic hardware and software components that make up a network
  - Network edge, end systems and network applications running in the network
  - Network core, links and switches that transport the data, access networks and physical media that connect end systems to the network core
  - Internet = network of networks, and how they connect with each other
  - Delay, loss, throughput of data in computer networks (transmission, propagation, queueing delays)
  - Key architectural principles in computer networking (protocol layering and service models)
  - Vulnerabilities and history of computer networks

## The internet

- Public internet as specific computer network
- Largest engineered system ever created
- Hundreds of millions of connected computers, communication links, and switches
- Billions of users and an array of internet-connected things

### A nuts-and-bolts description

- Basic hardware and software components that make up the internet
- Internet is a computer network that interconnects billions of computing devices globally
- These devices are called _hosts_ or _end systems_
- End systems are connected together by a network of _communication links_ and _packet switches_
- There are many types of communication links which are made up of different types of physical media (e.g. coaxiaal cable, copper wire, optical fiber, radio spectrum)
- Different links can transmit data at different rates
- The _transmission rate_ of a link is measured in bits/second
- The sending end system segments the data and adds header bytes to each segment
- The resulting paackages of information (packets) are then sent through the network to the destination end system
- The destination end system reassembles the packets into the original data
- A _packet switch_ takes a packet arriving on one of ist incoming communication links and forwards it to one of its outgoing communication links
- The two main types of packet switches are _routers_ and _link-layer switches_
- Both forward packets toward their ultimate destination
- Link-layer switches are typically used in access networks
- Routers are typically used in the network core
- The sequence of communication links and packet switches traversed by a packet from the sending end system to the receiving end system is known as a _route_ or _path_ through the network
- Packet-switched networks transport packets
- End systems access the internet through Internet Service Providers (ISPs)
- Residential ISPs, e.g., local cable/telephone companies, corporate ISPs, university ISPs, ISPs that provide WiFi access in airports, hotels, coffee shops, etc., cellulat IRPs that provide access to smartphones and other devices
- Each ISP is in itself a network of packet switches and communication links and communication links
- 

### A services description

- Networking infrastructure that provides services to distributed applications
- 

### What is a protocol?

## The network edge
### Access networks
### Physical media

## The network core
### Packet switching
### Circuit switching
### Network of networks

## Delay, loss, and throughput in packed-switched networks
### Overview of delay in packed-switched networks
### Queueing delay and packet loss
### End-to-end delay
### Throughput in computer networks

## Protocol layers and their service models
### Layered architecture
### Encapsulation

## Networks under attack
## History of computer networking and the internet

## Credits

- J. F. Kurose and K. W. Ross, "Computer Networks and the Internet," in Computer Networking: A Top-Down Approach, 7th ed., New York: Pearson, 2017, ch. 1.
