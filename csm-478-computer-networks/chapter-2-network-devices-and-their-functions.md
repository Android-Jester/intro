# Chapter 2: Network Devices and their Functions

## Network Devices&#x20;

### Network Interface Card (NIC)

* The NIC is a board that is installed in the computer or network device.&#x20;
* It is usually built into the main board. One end of the NIC is accessible on the outside of the workstation via a connector for attachment to the communications media.&#x20;
  * The NIC may also be a separate card that is inserted into an expansion slot on the computer.&#x20;
* Imprinted on a NIC is a Hardware address known as Media Access Control (MAC) address. MAC addresses (aka Physical Addresses) is unique for every host device.

### Hub/Switch

* Electronic device (with a number of ports) used in a LAN to link groups of computers
* Its major function is to replicate data it receives from one device attached to it to all other devices.

#### Communication using a hub

* The two hosts (Bob and Sally) communicate using their hardware or MAC addresses
* Bob will begin what is known as Hostname to IP address resolution since he knows only Sally’s name
* **Scenario 1**
  * If the two hosts are on different Networks, then this will Require a Domain Name Service (DNS)&#x20;
*   **Scenario 2**

    * If the two hosts are on the same LAN, then Bob can just send a BROADCAST massage to all hosts on the network to request for the required info
    * Before the name (Sally) is resolved, the first thing Bob has to do is to BROADCAST on the LAN to get sally’s MAC address so he can communicate to her PC and resolve her name to an IP address

    #### Causes of LAN Traffic Congestion

    * Too many hosts in a single broadcast domain&#x20;
    * Broadcast storm&#x20;
    * Multicasting&#x20;
    * Low Bandwidth&#x20;
    * Adding hubs for connectivity to the network&#x20;
    * A bunch of ARP or IPX traffic

    ### Network Segmentation

    * The network terminology for breaking up a big network into a number of smaller ones
    * **Network Segmentation with a Switch**
      * The Switch replaces the Hub, and break up the collision domains.
      * Each network segment connected to the switch is now a separate collision domain.&#x20;
      * There is however still one (1) broadcast domain.
      * A switch does not break up Broadcast Domain. Using a switch is an inexpensive way to connect a couple of PCs together for home or small office network

### Routers&#x20;

* Electronic devices used to ensure messages are sent to their intended destinations
* Routers are used to connect separate networks together and route packets of data between them.&#x20;
* Routers, by default, break up a Broadcast Domain (Thus: the set of all devices on a network segment that hear all the broadcasts on that segment).&#x20;
* Routers in addition to breaking up broadcast domains, also break up collision domains Routers create an internetwork and provide connections to WAN services
* The ROUTER in above network has created two(2) broadcast domains and also provides connections to WAN services through its serial interface.
* Routers by default do not forward broadcasts.&#x20;
* Routers can filter a network based on Network Layer information

#### Functions of a Router&#x20;

* Packet Switching&#x20;
* Packet filtering&#x20;
* Internetwork communication&#x20;
* Path selection

### Differences between Routers and Switches

* Routers are actually known and called Layer 3 switches, they operate at layer 3 of the OSI model, & TCP/IP model Switches (a.k.a. Layer 2 Switches) operate at layer 2 of the OSI model, and TCP/IP model&#x20;
* Switches do not create internetworks
* Switches do not break up broadcast domains by default but break up collision domains by default
* Switches main purpose is to make a LAN work better by providing more bandwidth to LAN users&#x20;
* Switches do not forward packets as do Routers.&#x20;
  * They instead, switch frames from one port to another within a switched network&#x20;
  * Switches creates separate collision domains but a single broadcast domain.&#x20;
    * Routers on the other hand provide a separate broadcast domain for each of its interface

### Bridge

consists of hardware and/or software that allows communication between two similar networks

### Gateway&#x20;

consists of hardware and/or software that allows communications between dissimilar networks

### Repeaters

* Repeaters are devices that amplifies and re-transmits data from a sender at a distance away
  * This is due to weakening of electrical signals over distance especially through wires
* A repeater is connected between two cable segments. &#x20;
* Any electrical signal reaching the repeater from one segment, will be amplified and re-transmitted to the other segment.
*

    <figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

###

## Switching and Switching Tables

### Collision Domain(s)

### Broadcast Domain(s)
