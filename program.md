---
layout: program
title: 1st Workshop on New IP and Beyond
tbl-colwidths: [10,60]
---
<!-- <h1 style="text-align: center;">1st Workshop on New IP and Beyond</h1> -->

<div style="clear: both;">
  <div style="float: left; padding-left:30px">
    <img src="assets/img/icnp_logo.png" width='60' height='YYY' alt="">
  </div>
  <div>
    <h1 style="text-align: center; padding-right:40px; line-height:1em;">1st Workshop on New IP and Beyond</h1>
  </div>
</div>

<h4 style="text-align: center;line-height:2em;">30th October 2022, Organized by: IEEE ICNP 2022</h4>
<h5 style="text-align: center; line-height:0em;">The 30th IEEE International Conference on Network Protocols</h5>
<h6 style="text-align: center;line-height:0em;">Lexington, Kentucky, USA, October 30-November 2, 2022</h6>

<h2 style="text-align: center;">New IP and Beyond - Full Day Workshop Program</h2>

## About the Workshop

The __New IP and Beyond__ workshop aims to discuss research challenges in fixed-network protocols complementing 5G, B5G and 6G technologies.The focus is on realization of large-scale, special-purpose industry verticals, autonomous operations, reliable supply-chains, metaverse and digital twins. Such networks require, an extremely reliant, intelligent, and lean networks.:s

--- 

## Agenda

##### 9:30-10:15 AM *Session 1 Keynote* 

|9:30 |Opening & Welcome	Note by Chairs (10 minutes)	|
|9:40:| __Keynote__: Topic -TBD |
| | <span style="color:#FA5E8B">Dr. Feng Qian</span>, Associate Professor, University of Minnesota|

#### 10:15 AM Coffee Break (30 m)	

#### 10:45 AM-12:30 PM	Session 2	*New  In-network services*

|10:45 | Behavior-decoupled Labeling Mechanism in Generalized SRv6<br>Authors: W. Wu, <span style="color:#FA5E8B">S. Li(remote)</span>, A. Pei, T. Huang|
|11:10 |Delay Laxity-Based Scheduling with Double-Deep Q-Learning for Time-Critical Applications<br> Authors: <span style="color:#FA5E8B">X. Ren </span>, J. Ji, L. Cai
|11:35 	|TinTin: Tiny In-Network Transport for High Precision INdustrial Communication<br>	Authors: K. Makhijani, B. Kataria, S. D., D. Devkota, <span style="color:#FA5E8B">M. Tahiliani(remote)</span> |
|11:55 	|Evolving the End-to-End Transport Layer in Times of Emerging Computing In The Network (COIN)<br>Authors: <span style="color:#FA5E8B">I. Kunze</span>, D. Trossen, K. Wehrle

#### 12:30 PM	Lunch	

#### 13:30-14:45 PM Session 3 -	*New  Routing Paradigms*

|13:30 	|Semiring Algebraic Structure for Metarouting with Automatic Tunneling<br> Authors: <span style="color:#FA5E8B">N. Mouhoub</span>, M. Lamali, D. Magoni|
|13:55 | New IP based semantic addressing and routing for LEO satellite networks<br> Authors: <span style="color:#FA5E8B">L. Han</span>, A. Retana, C. Westphal, R. Li, T. Jiang, M. Chen|
|14:20 | Supporting Dynamic Secure Interdomain Routing<br> Authors: L. Schulz, E. Moghadam, J. García-Pardo, D. Hausheer, <span style="color:#FA5E8B">K. Calvert</span>|

#### 14:45 15:15 PM	Coffee Break

#### 15:15:00 PM 	Session 4 - *Panel Discussion*

| Topic | <span style="color:#9B032F">Way Forward to 5G/6G: what is missing in network protocols and technologies.</span>|
|	Panelists| <span style="color:#FA5E8B">Ken Calvert</span> (UK, KY, USA),<br> <span style="color:#FA5E8B">Richard Li</span> (Futurewei, CA, USA)<br>	<span style="color:#FA5E8B">Nirmala Shenoy</span> (RIT, NY, USA)<br>	<span style="color:#FA5E8B">Marina Thottan</span>, (Amazon, remote, USA)	|

#### 4:15 |	Closing	

---
## Keynote
*coming soon*

---

## Panel Details
*coming soon*

----

## Submitted Paper Presentations

#### Tiny In-Network Transport for High Precision INdustrial Communication

*Abstract:* The design of a transport protocol for high precision
industrial networks is a complex problem since the industrial
applications are resource-critical, time-critical, session-less, and
safety-critical. These requirements make existing end-to-end
transport mechanisms unsuitable for use in the industry verticals
that require control-systems type communication. This paper
proposes a lightweight, connection-less, and reliable protocol
called TinTin. It utilizes the in-network capabilities to compensate
for end device constraints. The mechanisms adopted in TinTin
aim to reduce the communication overheads associated with well-
known connection-oriented protocols. This paper discusses the
design considerations of TinTin in detail and presents an early
stage proof-of-concept implementation of TinTin with New IP.

##### Authors: Kiran Makhijani (Futurewei), Bhaskar Kataria, Shashank D., Deepta Devkota, Mohit Tahiliani (NITK, Surathkal).

#### Behavior-decoupled Labeling Mechanism in Generalized SRv6

*Abstract:* In this paper, we study the problem of compression efficiency of SRH (Segment Routing Header) in G-SRv6 (Generalized SRv6). We propose the Function-decoupled Segment Routing Mechanism (FDSRM) to optimize the SID list in SRH while ensuring that the routing policy decision would not be affected. FDSRM logically decouples the functions of SID/G-SID according to the function in routing decision and instruction indication. Based on FDSRM, we propose a mathematical optimization framework that leverages the LSTM neural network to optimize the SID allocation to adapt to future traffic. Simulation results indicate that FDSRM can improve the probability of SRH compression by 50.86\%, and compress more than 24.50 bytes when the hop count is greater than 20.

##### Authors: Weihong Wu, Sijia Li, Anbang Pei(Beijing University of Posts and Telecommunications), Tao Huang(Purple Mountain Laboratories)

#### Delay Laxity-Based Scheduling with Double-Deep Q-Learning for Time-Critical Applications

*Abstract:* In this paper, we propose a novel delay-aware selective admission and scheduling algorithm for time-critical applications to guarantee the delay requirement of each packet in a single-hop downlink network.
We consider a series of priorities among packets. To avoid always starving low-priority packets, we define a delay-laxity concept and introduce a new output gain model as our network utility function. In this context, we formulate a multi-objective optimization problem that minimizes the average queue backlog and maximizes the average network utility under the constraints of guaranteeing per-packet delay and achieving fairness among users. To solve this problem, we model our problem as a Markov Decision Process and propose a Double Deep Q Network-based algorithm to learn the optimal policy.
Simulation results show that the proposed algorithm can achieve significant improvements in average delay, delay-outage drop rate, and goodput compared with the existing stochastic schemes. Moreover, the proposed algorithm outperforms the conventional Q-learning algorithm in terms of reward and learning speed.

##### Authors: Xiangyu Ren, Jiequ Ji, Lin Cai (University of Victoria).

#### Semiring Algebraic Structure for Metarouting with Automatic Tunneling

*Abstract*: Metarouting models routing protocols in the form of an algebraic structure called routing algebra. It aims to help designing or validating routing protocols. Most research work on routing algebras have been applied to routing protocols used in networks having a single addressing and forwarding protocol. In this context, some of the basic algebraic structures used are semirings. In this paper, we define a new algebraic structure for dealing with networks containing multiple forwarding protocols, which may induce many (and possibly nested) tunnels. We widely generalize the semiring structure for modeling the routing problem with automatic tunneling. We define a new model of routing algebra with tunneling.  It is defined as a semi-direct product of two structures, the well-know shortest paths algebra and a new proposed valid paths algebra. It is isotonic and non-monotonic with a partial order. We show that it has a fixed point and we prove the iterative convergence to the optimal solution of the valid shortest paths problem.

##### Authors: Noureddine Mouhoub, Mohamed Lamine Lamali, Damien Magoni (LaBRI - Université de Bordeaux).

#### New IP based semantic addressing and routing for LEO satellite networks

*Abstract* :
This document proposes a method of addressing and routing for massive Low Earth Orbit (LEO) satellite constellations. It is based on the concepts and technologies of New IP. LEO satellite networks can be used for Internet access and for the Non-Terrestrial Network (NTN) integration with 5G and beyond. Our new addressing method leverages the characteristics of satellites with known orbit elements; and simplifies the satellite identification by using limited indexes. The new routing method combines semantic addressing with source routing and generates a new semantic routing scheme. Compared with traditional methods, the new proposal dramatically reduces the workload in satellite, such as table size, TCAM (Ternary Content-addressable Memory) lookups, and packet header size. Thus, it is more suitable to network in space where the harsh environment will restrict the hardware performance, power consumption, link bandwidth and system complexity.

##### Authors: Lin Han, Alvaro Retana, Cedric Westphal, Richard Li (Futurewei Technologies, Inc.), Tianji Jiang, Meiling Chen (China Mobile Communication Research Institute)

#### Supporting Dynamic Secure Interdomain Routing

*Abstract*: Path aware networking (PAN) is an approach that allows endpoints to participate in the end-to-end path selection, letting them choose paths best suited for each application. This approach offers numerous potential benefits including rapid fail-over, concurrent use of parallel paths, and QoS enabled networks, even spanning multiple domains. The dynamic interconnection of different autonomous systems (ASes) in path aware networks offers both challenges and opportunities for network service providers, which in turn provide opportunities for traffic engineering previously not possible.
The SCION path-aware network architecture has been designed from the ground up with security in mind, and features a trust structure that can serve as a basis for more dynamic interconnection between ASes.  In this paper, we describe a prototype *spot market* that lets the ASes sell time-limited excess capacity, allowing buyers to divert traffic to cheaper alternatives temporarily. We believe this market allows for new opportunities both in traffic engineering and inter-domain connectivity that have not existed before. The market benefits all parties involved, as the formerly wasted bandwidth is now used, and provides additional revenue -in varying degrees- to all the participating entities.

##### Authors: Lars-Christian Schulz, David Hausheer (OVGU Magdeburg), Elham Ehsani Moghadam, Juan Angel García-Pardo (ETH Zurich), Ken Calvert (University of Kentucky)

#### Evolving the End-to-End Transport Layer in Times of Emerging Computing In The Network (COIN)

*Abstract*: The possibility of richer computing capabilities within Internet network elements, often captured as Computing in the Network (COIN), promises performance and flexibility gains to the wider Internet, akin to those seen in recent data center advances. At the same time, moving computation into the
network is seemingly at odds with the fundamental end-to-end principle underlying the development of key technologies in the Internet. In this paper, we do not only argue that the latter is not the case, but we also shed light on what ‘in the network’ may or may not entail, aiming to sharpen a possible research agenda for COIN. Taking the transport layer as an example due to its typical end-to-end realization in and importance for today’s Internet, we outline key design considerations for evolving towards a COIN-enabled transport capability. By further creating linkages to existing efforts and concepts, we provide possible future directions for the design of protocols for the future Internet.

##### Authors: Ike Kunze (RWTH Aachen University), Dirk Trossen (Huawei), Klaus Wehrle (RWTH Aachen University)
