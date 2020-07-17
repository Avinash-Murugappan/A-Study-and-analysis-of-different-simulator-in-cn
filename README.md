```
ISSN (Print): 2347- 6710
```
## International Journal of Innovative Research in Science,

## Engineering and Technology

```
(An ISO 3297: 2007 Certified Organization)
Website: http://www.ijirset.com
Vol. 6, Issue 7, July 2017
```
# A Study and Analysis of Different Simulators

# in Computer Network

#### Sudha Rani S^1 , Akshay R^2 , Avinash Arunachalam A M 3

```
Assistant Professor, Department of Computer Science, Sri Krishna College of Engineering and Technology ,
Coimbatore, Tamil Nadu, India^1
UG Student, Department of Computer Science, Sri Krishna College of Engineering and Technology ,Coimbatore,Tamil
Nadu , India^2
UG Student, Department of Computer Science, Sri Krishna College of Engineering and Technology ,Coimbatore,Tamil
Nadu , India^3
```
**ABSTRACT** : Real world applications such as aircraft design, motor drive controller design and space robot integration
simulation plays a prominent role. Simulation modelling aids to garner consensus and generate confidence for the
design which was/is tried and tested. Simulation modelling acquires information about how something will behave
without actually testing it in real life. One such type of simulation is network about how system behaves externally
without actually testing it in real life. In this paper, we have examined one such type of simulation known as network
simulation. In computer networking research, network simulation is a technique which models the behaviour of
different network entities under different conditions. Our paper provides and overall analysis on divergent species of
simulators used in networking models.

**KEYWORDS** : _Computer networks; Network simulation; Network simulator_

### I. INTRODUCTION

At present, performing data communication in a network is one of the rapidly growing technologies. Sending the
required information from one place to another place is extremely complex without networking. Can you imagine
world without google, online newspapers, blogs, forums and other web services offered by the internet using network?
Today, computer networks are the core of modern communication. Computer networking benefits the people to share
the resources during data communication. Network manages all the program, data and hardware available to everyone
in the network without any regard of physical location of users and their resources.

Computer networking is one of the very few profession in which top 25% workers make over $100,000. Computer
network is fastest occupation for the need of system administrator who can help organizations to achieve increased
firms.Networking has excellent research opportunities in the fields of military reconnaissance, Artificial Intelligence,


```
ISSN (Print): 2347- 6710
```
## International Journal of Innovative Research in Science,

## Engineering and Technology

```
(An ISO 3297: 2007 Certified Organization)
Website: http://www.ijirset.com
Vol. 6, Issue 7, July 2017
```
Remote sensing and wireless sensor networks. Computer network finds its applications in various fields such as
business, smart homes, mobile users, social networks, organization, education, telecommunication, media, industry,
science, research and development etc. Advancement of technologies has proved itself that performing data
communication is huge faster with expanded bandwidth capacity. Therefore, computer network guides people who live
or work apart.

Balancing information and communication between any two entities is one of the tedious tasks to run a successful
organization. To represent the physical view of information and communication we need computer systems. To manage
and maintain both information and communication we need networks. Computer network is the process of transmitting
or exchanging information/data between two different devices being connected. Connection can be either wired or
wireless medium. When wired communication takes place between two different devices we use cables as transmission
medium.

Advantages of networks are easy file sharing, sharing resources such as printers, Internet connections, and
centralized data communication using file server for ease of access and back-up. Disadvantages of networks are
vulnerable to hackers, if the network fails then other task becomes very difficult, easily attacked by unauthorized users.
Similarly, when computer connected to Internet can find loopholes such as revealing personal information, suspecting
websites that are malware, sometimes information in Internet is not always accurate or reliable. The use of network
with respect to organization is cost reduction because it shares the hardware and software resources, high reliability
because multiple sources of supply, greater flexibility because of possibility to connect devices from various vendors.

Data Communication is the movement of computer information from one device to another device forming a
network. Client computers connected together to create a network which is termed to be servers and clients. Client
computers or workstations are the normal computers where people sit at to get their work done. Servers are special,
powerful computers that provide “services” to the client computers in the network. Servers provides a central, common
file storage area, sharing hardware such as printers, controlling who can or can’t have access to the network and sharing
Internet connections. Servers are built to be very reliable.

```
A. Benefits of Computer Network
```
```
● File Sharing: Networking of computers helps the users to share data files such as emails, instant messaging,
video telephone, cat rooms etc.
● Hardware sharing: Users can share devices such as printers, scanners, CD-ROM, drivers, hard drives etc.
● Application sharing: Applications can be shared over the network, and this allows to implement client/server
applications.
● User communication: Networks allow users to communicate using email, newsgroups and video
conferencing etc.
● Network gaming: A lot of network games available allows multi-users to play from different locations.
II LAYERING CONCEPT OF NETWORK SIMULATION
```

```
ISSN (Print): 2347- 6710
```
## International Journal of Innovative Research in Science,

## Engineering and Technology

```
(An ISO 3297: 2007 Certified Organization)
Website: http://www.ijirset.com
Vol. 6, Issue 7, July 2017
```
```
Simulation is meant to be a network entity (node, host, packets) flow process [3]. Simulation [2] “Process of
designing a real system model and conducting experiments with this model to understand the behaviour of the system
and evaluating various procedures for the operation of the system”.Network simulation is used to validate protocol,
control experimental conditions, low cost in terms of $, time, collaboration and complexity. The main objective of
simulation is to generate statistical results that represent the behaviour of certain network entities and their operations.
Key elements used in simulation are as follows [1],
```
```
● Performance Modelling
● Failure Analysis
● Network Design
● Network resource planning
● Reusability
● Availability
● Scalability
● Graphical, debug and trace support
In a network, if real system is not available, complex, costly or dangerous (e.g. space simulations, flight simulations),
to quickly evaluate design alternatives and evaluate complex functions for which closed form formulas or numerical
techniques not available, then we tend to prefer simulations in that particular network. Network Simulation (Ns) [5]
itself is derived from REAL (Realistic and Large) which in turn is derived from NEST (Network Simulation Testbed).
TABLE I shows the difference between testbed and simulator advantages and disadvantages [21].
```
**Platform Advantages Disadvantages**
Testbed Fast , Accurate, Ground truth Expensive
Shared resource????Hard to reconfigure, Hard
to change, Hard to download

Simulator Inexpensive, Flexible, Easy to
download virtual time (faster than
reality”), performance of a real-life
system (latency time, packet loss, etc.)

```
May require app changes might not run OS
code accurately, May not be “believable”, May
be slow/non-interactive
```
```
TABLE I Difference between Testbed and Simulator
```
```
III NETWORK SIMULATORS
```

```
ISSN (Print): 2347- 6710
```
## International Journal of Innovative Research in Science,

## Engineering and Technology

```
(An ISO 3297: 2007 Certified Organization)
Website: http://www.ijirset.com
Vol. 6, Issue 7, July 2017
```
```
A. Cloonix
```
Cloonix is a network simulator which provides GUI to the user. It allows [7]KVM to create virtual machines and
consists of inbuilt file systems which can be used as virtual machines for creating other virtual machine root file
systems. It is widely used in virtualization of mobile networks [6]. It manages the virtual network topology providing
WYSIWYG. It works under Linux Network Emulator tool known as netem [6]. It performs host simulation on Linux
router encapsulating application, host and network L2 and L3 in the GUI form. Network characteristics such as delay
and loss can be configured per network link using Cloonix simulator [7]. Fig.1. shows a simple GUI of Cloonix
network simulator.

Fig.1.Cloonix Network Simulator

```
B.Cooja
```
Cooja simulator [8] allows real hardware platforms which need to be emulated and simulated. It is implemented by
Contiki a sensor network operating system. It is a flexible Java-based simulator specially designed for sensor networks
using Contiki sensor network operating system [9].It is used to handle the event or to fetch the entire Contiki system
memory for analysis. Fig.2. shows a simple GUI of Cooja network simulator.

```
Fig.2.Cooja Network Simulator
```
```
C. GNS
```

```
ISSN (Print): 2347- 6710
```
## International Journal of Innovative Research in Science,

## Engineering and Technology

```
(An ISO 3297: 2007 Certified Organization)
Website: http://www.ijirset.com
Vol. 6, Issue 7, July 2017
```
GNS3 [10] stands for “Graphical Network Simulator” an open source software which simulates complex real
networks. It is platform independent and implemented by CISCO and Juniper. A graphical network simulator which
designs network topologies like IOS routers, ATM/Frame Relay/Ethernet switches and hubs by extending network with
virtual topology. It performs emulation [13] using Cisco Internetwork Operating Systems. Graphical front end product
of GNS3 is Dynagen Which is on the top of Dynamips used to create a text based environment [11] [12].

```
Fig.3. GNS3 Network Simulator
```
```
D. GloMoSim
```
GloMoSim stands for Global Mobile Information System Simulator [14] used for both wired and wireless networking
environment especially used for ad hoc network. It is designed using parallel discrete-event called “Parsec”. It performs
communication on heterogeneous, asymmetric, multihop wireless communication [15]. It uses rich protocol stack for
the design and development of GloMoSim framework so as to achieve scalability and feasibility features. It supports
both unicast and multicast wireless protocols [15].

```
Fig.4.GloMoSim Network Simulator
```
```
E. IMUNES
```
IMUNES stands for Integrated Multiprotocol Network Emulator/Simulator which is a network emulation
framework runs on FreeBSD operating system to partition virtualbox of virtual machine into multiple lightweight
virtual machines. Lightweight virtual nodes will be interconnected via kernel level links to form complex network


```
ISSN (Print): 2347- 6710
```
## International Journal of Innovative Research in Science,

## Engineering and Technology

```
(An ISO 3297: 2007 Certified Organization)
Website: http://www.ijirset.com
Vol. 6, Issue 7, July 2017
```
topologies. It provides each virtual node to run a private copy of any unmodified user-level application such as routing
protocol daemons, traffic generators, analysers. Thus it provides high scalability, performance and fidelity [16] [17].

```
F. JavaSim
```
JavaSim or J-Sim is an object oriented simulator written in Java. It is a discrete event process based simulator
consists of classes, methods, libraries. It is an open source simulator which can be modified according to the user.
JavaSim package consists of JavaSim class which supports simulation using inbuilt classes of JavaSim class. Some of
the methods available in JavaSim class are javaSimInit(), schedule(), schedule Plus(), report(), clearStats(). It used in
commercial and academic organisations [18]. It provides,

```
● The SIMULA like simulation routines, random number generators, queueing algorithms and thread package
interfaces.
● SIMSET similar to entity and set manipulation.
● Non causal events such as interrupts classes are allowed.
● Statistical routines such as histogram and variance classes.
● Debugging classes too.
G. Marionnet
```
A virtual network which allows user to define, configure and run complex computer networks without any need for
physical setup. One non-networked Linux/GNU host machine is enough to simulate a whole Ethernet network
consisting of computers, routers, hubs, switches, cables. It integrates the virtual network with the physical host
network. It is termed as “virtual network laboratory” [19]. Marionnet[20] enables users to test computer network
cabling, network protocols, services and applications. Then application allows to easily define and configure a virtual
network complete with hubs, switches and routers. It is free software application. Network devices like hubs, switches,
routers physical behaviour in the network can be simulated.

```
H. Mininet
```
Mininet creates a realistic virtual network running on real kernel, switch and application code on the same domain
with a single command (e.g. >sudo mn) [21] [22]. Linux network namespace is used for virtualization technology to

create virtual switches and virtual nodes supporting 1000’s of virtual nodes on a single OS [22]. It requires a
knowledge of python scripting language to work with Mininet.


```
ISSN (Print): 2347- 6710
```
## International Journal of Innovative Research in Science,

## Engineering and Technology

```
(An ISO 3297: 2007 Certified Organization)
Website: http://www.ijirset.com
Vol. 6, Issue 7, July 2017
```
Features are [21],

```
● It creates an instant virtual network in laptop [24]
● It provides ease of use, scalability, performance and accuracy [24]
● It shares experiment with OpenFlow and Software-Defined Networking systems [23]
I. NetKit
```
NetKit is a command line simulation tool. It uses user-mode Linux to create the virtual machines in which a full
Linux OS can run on each machine [25][26]. NetKit works on Linux Host or machines. It does the running of routing
daemon, configuring Ethernet Bridge and makes the virtual hub to make run on Linux host. It is primarily focused to
work on virtual machine and virtual hub.

```
J. NetSim
```
Netsim is a network simulator used for modelling protocols, analyse networks in terms of depth, power and
flexibility. It is mainly applicable in research and development and defence applications. Basically, most of the
networks related to communication among data is complex to provide an accurate analysis of system behaviour. Hence,
Netsim Analyses the parameters such as arrival time of the packet, queuing time of the data in buffer, payload of data,
overhead, and error for every packet as it flows through the network. It also records the event traces logging every
single event in the protocol and finite state machine transitions along with associated information like time-stamp,
event id, and event type.

It provides the simulation visualization to animate the packet flow via wired and wireless links, the control packets,
data packets, and error packets. Apart from animation, result analyses the output performance metrics such as network,
sub network, link, queue, application, throughput, delay, loss, packet error, link utilization. Application [27] that
simulates Cisco systems networking hardware and software using command structure.

```
K. ns
```
Network simulator version 2, widely known as NS2, an event driven simulation tool used for communication in
network. Simulation of wired as well as wireless network uses the routing algorithms, protocols such as TCP, UDP. It
is written not only in OTcl (Object oriented Tool Command Language) but in C++ also. NS2 helps to create network
topologies, trace the log events which takes place under any kind of load, analyses events to understand the network
behaviour.


```
ISSN (Print): 2347- 6710
```
## International Journal of Innovative Research in Science,

## Engineering and Technology

```
(An ISO 3297: 2007 Certified Organization)
Website: http://www.ijirset.com
Vol. 6, Issue 7, July 2017
```
```
L. ns
```
ns3 is an open source discrete event simulator used in networking for research and education [27]. It is written
entirely in C++. The user code which includes the protocols and scenarios are written in C++ whereas python wraps the
user code. Simulation programs are C++ executables or python scripts [27]. It does direct code execution (DCE).

```
M. OMNet++
```
OMNet++ is an object oriented modular discrete event network simulator which is used for traffic modelling,
protocol modelling, modelling queuing networks, modelling multiprocessors and other distribute hardware systems.
The main components are simulation kernel, library and user interfaces. The speciality of OMNet++ is portable. Some
of the simulation models are INET framework, AdHoc Sim, Antnet, Mobility framework, IPV6, video interface,
Ethernet, P2P swarming protocol simulation, Hiperlan/2 model, Sim SANs, Queues, SCSI bus, etc.

```
N. OPNET
```
OPNET is a high level event based network level simulation tool. This tool is one of the most powerful simulation
tools for the analysis, planning and optimization of communication networks, devices and protocols. It is originated
form NETWARS programmed by department of US. It is an object oriented simulation approach supported by a series
of GUI.

```
O. QualNet
```
QualNet is mainly used for mobile adhoc networks. It is used to create different network models and new
protocols. It creates heterogeneous devices and networks with uniform platform. It supports WiFi, Wimax, and Sensors.
It uses interfaces such as CLI and GUI. CLI uses MS DOS supporting 2000 to 3000 nodes with less memory storage.It
supports cross layer communication using one protocol that runs in two different layers. It is a state-of-the-art simulator
used specially for large, heterogeneous networks and distributed applications that execute on such networks.

```
IV. CONCLUSION AND FUTURE SCOPE
```
The other network simulators we left to explain are PSimulator, Gos IP, NetViz, NIST, REAL, NEST, PTOLEMY.
The various network simulators are explained with some user interface diagrams. Various network simulators enable to
simulate the network but only few simulators are used by researchers. Our work stated many simulators is useful in
research and system networks. The future work may include explaining new simulators which we stated above.

```
REFERENCES
```
```
[1] E. E’gea-López, J. Vales-Alonso, A. S. Martínez-Sala, P. Pavón-Mariño, J. García-Haro_, “Simulation Tools for Wireless Sensor
Networks”, Department of Information Technologies and Communications Polytechnic University of Cartagena, Spain, Summer Simulation
Multiconference - SPECTS 2005.
[2] R. E. Shannon, “Introduction to the art and science of simulation,” in Proc. Of the 30th conference on winter simulation (WSC’98),
1989.
```

```
ISSN (Print): 2347- 6710
```
## International Journal of Innovative Research in Science,

## Engineering and Technology

```
(An ISO 3297: 2007 Certified Organization)
Website: http://www.ijirset.com
Vol. 6, Issue 7, July 2017
```
```
[3] T. Issariyakul, E. Hossain, Introduction to Network Simulator NS2, DOI: 10.1007/978- 0 - 387 71760-9 1, c_ Springer Science+Business
Media, LLC 2009.
[4] 1. S. Keshav, REAL: A Network Simulator,tech. report 88/472, Univ. California,Berkeley, 1988.
[5] A. Dupuy et al., “NEST: A Network Simulation and Prototyping Testbed,” Comm. ACM, Oct. 1990, pp. 64-74.
[6] D. Rehunathan, S. Bhatti University of St Andrews , V. Perrier , P. Hui Deutsche Telekom Laboratories (Berlin) , “The Study of Mobile
Network Protocols with Virtual Machines”, Barcelona, Spin, ICST 978- 1 - 936968 - 00 - 8.
```
#### [7] V. Perrier. Cloonix. http://clownix.net/.

```
[8] Anuj Sehgal “Using the Contiki Cooja Simulator Computer Science”, Jacobs University Bremen Campus Ring 1, 28759 Bremen,
```
#### Germany, s.anuj@jacobs-university.de, Elsevier, October 29, 2013.

```
[9] Joakim Eriksson, Fredrik Österlind, NiclasFinne, Nicolas Tsiftes, Adam Dunkels, Thiemo Voigt, “COOJA/MSPSim: Interoperability
Testing for Wireless Sensor Networks “ Swedish Institute of Computer Science {joakime,fros,nfi,nvt,adam,thiemo}@sics.se Robert Sauter,
Pedro José Marrón University of Bonn and Fraunhofer IAIS {sauter,pjmarron}@cs.uni-bonn.de,
```
#### [10] GNS3: http://www.gns3.net/

[11] [http://www.ipflow.utc.fr/blog/](http://www.ipflow.utc.fr/blog/)

#### [12] http://dyna-gen-sourceforge.net/

```
[13] GNS3 Graphical Network Simulator,By Mike Fuszner – version 1.
[14] Jorge Nuevo, “A Comprehensible GloMoSim Tutorial”, University of Quebee, March 26, 2003.
```
### [15] http://pcl.cs.ucla.edu/projects/glomosim/

### [16] http://www.imunes.net

```
[17] Z. Puljiz and M. Mikuc,” IMUNES Based Distributed Network Emulator“, Faculty of Electrical Engineering and Computing/Department
of Telecommunications, Zagreb, Croatia, 2004.
```
#### [18] https://github.com/nmcl/JavaSim

#### [19] http://www.marionnet.org/EN/

```
[20] Jean-Vincent Loddo, Luca Saiu, “Marionnet: a virtual network laboratory and simulation tool”, Simulation Works March 4, 2008,
Marseille, France.
[21] Te-Yuan Huang, Vimalkumar Jeyakumar Bob Lantz, Brian O'Connor Nick Feamster Keith Winstein, Anirudh Sivaraman, “Teaching
Computer Networking with Mininet”, Wi-Fi: HHonors, SGC
```
#### [22] http://www.mininet.org

```
[23] Karamjeet Kaur, Japinder Singh and Navtej Singh Ghumman, “Mininet as Software Defined Networking Testing Platform”, International
Conference on Communication, Computing & Systems (ICCCS–2014)
[24] Bob Lantz, Brian O’Connor work with Brandon Heller, Nikhil Handigol, Vimal Jeyakumar, and the Mininet Contributors, “Mininet: An
instant Virtual Network on your Laptop”.
```
#### [25] http://wiki.netkit.org

[26] Maurizio Pizzonia, Massimo Rimondini, “Netkit: Easy Emulation of Complex Networkson Inexpensive Hardware”, Dept. of Computer
Science and Automation, Roma Tre University
[27] [http://nsnam.org/](http://nsnam.org/)
[28] Fatemeh Saremi “Modeling and Analysis of Computer Networks”, Sharif University of Technology, spring 2009



