# DiijkestraAlgo
Implimentation of Diijekstra Algo

Problem Statement
In this problem, you will create a static routing algorithm (using Dijkstra’s algorithm). You will be given the computer network as a header file (see below). You will have to create a routing table for this network and then wait for user input. The user can now input a source (A) and destination (B) IP address (see below for input format). You will now output the IP address of all machines through which a packet originating from A will traverse before it reaches B.

Header file explanation
The objective of header file is to give the input network. We assume that all subnets have subnet mask of 24 bits. Therefore assume that all IP addresses which have the
same 24 bits in the prefix form a subnet (see Figure below).
1. The string IPaddress gives the list of IP addresses in the network. It also includes the interface IP address of the routers.
2. The string Routers identify the routers using the interface IP addresses
3. The string InterfaceDistance gives the distance (or cost) of sending a packet from the one router interface to another (or vice versa).

Input and Output
Give source and destination IP: 67.100.3.8, 60.80.33.10
The packet from 67.100.3.8 to 60.80.33.10 goes via the following router interfaces: x.y.z.t, ….
Give source and destination IP.
