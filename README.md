# Operation of a mini-Internet
Building and operating a fully-functional mini-Internet including dealing with intra-domain routing, inter-domain routing and policy routing by using Docker containers\  
Used **Open vSwitch for configuring the L2 switches** and the **FRRouting software routing suite for configuring the L3 routers**\
**Performed in teams of 3 people, each one of which operated one fully-functional Autonomous System (AS)**\

## Project Description
In this project, we were tasked to **build and operate our very own mini-Internet**
together with more than 100 of our fellow classmates. Our main goal? **Enabling
end-to-end connectivity across around 70 Autonomous Systems (ASes) composed
of hundreds of network devices.** In doing so, we experimented with the most
common switching and routing technologies used in the Internet today. **We had to face the same challenges actual network operators experience every day.**
To reach Internet-wide connectivity, we first needed to enable internal
connectivity, within our own AS, before interconnecting our AS with
other ASes, managed by other groups of students. To establish connectivity
within our AS, we configured **IPv4 and IPv6 addresses and used Open
Shortest Path First (OSPF).** To establish connectivity across different
ASes, we used the only inter-domain routing protocol available today: the
**Border Gateway Protocol (BGP).** At the end of the project, end-hosts were
able to communicate with each other, independently of the AS they were
located in.
To implement this we used a base network topology on top of **virtual
layer-2 switches, running Open vSwitch** and
**virtual routers, running the FRRouting software routing suite.**
We configured the virtual switches and routers through a **Command Line Interface (CLI).**
This interface is virtually identical to the one used by actual network operators.
