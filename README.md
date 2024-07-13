<div align=center>
  <h1>Networking Course</h1>
</div>

- This networking course belongs to [Kunal Kushwaha](https://github.com/kunal-kushwaha). This repo has all the notes that his course provided in markdown format.
- This repo is my version of all the notes taken by his video course.


## Index

- [Introduction](./Introduction.md)
- [Structure Of Network](./Structure-Of-Network.md)
- [TCP(Transmission Control Protocol)](./TCP.md)
- [UDP(User Datagram Protocol)](./UDP.md)
- [Client-Server Architecture](./Client-Server-Architecture.md)
- [Protocols](./Protocols.md)
- [Submarine Cable Map](./Submarine-Cables-Map.md)
- [Transport Layer Important Stuff](./Transport-Layer.md)
- [Data Link Layer Important Stuff](./Data-Link-Layer.md)
- [How Email Works](./How-Email-Works.md)
- [Internet Protocol](./Internet-Protocol.md)
- [Packets](./Packets.md)
- [DNS](./DNS.md)
- [Middle Boxes](./Middle-Boxes.md)
- [NAT](./NAT.md)

## overview
![image](https://github.com/user-attachments/assets/9679e4bc-c638-4ca2-89e3-c85b7f6027d7)
your computer can act as a client or a server (local host)

![image](https://github.com/user-attachments/assets/d97fa085-5457-435f-9908-06aad30a1cb9)
Everything in computer is 0's and 1's and there all data is not send at one. they are send in packets which we can see in above image. same packets is used when we recieve information. 

### IP address
the phone no (IP address) is connected to a name (Youtube)
IP address - XXXX.XXXX.XXXX.XXXX (0-255 each)
![](https://media.geeksforgeeks.org/wp-content/uploads/Packet_flow_9-1.jpg)
ip address and port no (which application uses called for the domain)


> $ curl if congig.me -s //to check ip address of your computer.

Internet -> ISP (internet service provider) -> modem -> router -> switch -> pc
1 kbps = 1000 bits/second.

![image](https://github.com/user-attachments/assets/367ebb60-8506-461c-adbb-3691b788a7a9)
Physically - Optical fibre cables, coaxial cables.
Wireless - Bluetooth, etc

## How things are connected acc to area/ scope
### LAN connecting within a organization
![Untitled](https://github.com/user-attachments/assets/739cc956-ebce-4d4b-8e6b-7bdcb9575e61)

### MAN ( between cities and organization) collection of LAN
![55554](https://github.com/user-attachments/assets/53cbc6b3-8f56-4194-9abb-f241af6bb720)

### WAN ( using optical fiber cable) collection of MAN
![Untitled](https://github.com/user-attachments/assets/4c19e14a-84a8-4d06-8246-fdae2151122d)

### SONET (Synchronous Optical Network)
### Frame relay ( local area network connected to wider)

## Basic Protcols 
- TCP data will reach the user and doesnt get corrupt
               - UDP some data is lost but we are okay with it
               - HTTP - used by web browser, it defines fomat for web cients and web servers. 

## Topologies 
![topology](https://github.com/user-attachments/assets/c24f170d-228b-48db-a123-1563647fb94a)

1. Bus Topology:

    Description: All devices share a single communication line or cable.
    Advantages: Easy to install, requires less cable than other topologies.
    Disadvantages: Limited cable length and number of stations, difficult to troubleshoot, a break in the main cable stops all transmission.

2. Ring Topology:

    Description: Devices are connected in a circular fashion where each device has exactly two neighbors.
    Advantages: Data packets travel in one direction, reducing the chance of packet collisions.
    Disadvantages: A break in the ring can disable the entire network, and it can be difficult to troubleshoot.

3. Star Topology:

    Description: All devices are connected to a central hub or switch.
    Advantages: Easy to install and manage, failure of one node does not affect the rest of the network, easy to troubleshoot.
    Disadvantages: If the central hub fails, the whole network goes down, requires more cable than bus topology.

4. Mesh Topology:

    Description: Every device is connected to every other device in the network.
    Advantages: High redundancy and reliability, failure of one device does not affect the network.
    Disadvantages: Expensive and complex to install, requires a lot of cables and network interfaces.

5. Tree Topology:

    Description: A hybrid topology that combines characteristics of star and bus topologies, with groups of star-configured networks connected to a linear bus backbone.
    Advantages: Scalable, easy to manage and troubleshoot, supports future expandability.
    Disadvantages: A break in the backbone cable can isolate entire segments, requires more cable than bus or star topologies.

7. Hybrid Topology:

    Description: Combines two or more different topologies to form a resultant topology that exploits the advantages of each constituent topology.
    Advantages: Flexible, scalable, and reliable, combines the strengths of the different topologies used.
    Disadvantages: Complex to design and implement, can be expensive due to the use of multiple topologies.


## Strucuture of network

   ![image](https://github.com/user-attachments/assets/3223a8e2-9c5c-4e07-bbd5-6dfdd34a42e3)

