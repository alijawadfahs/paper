---
author:
- 'LIG - Verimag'
title: 'Paper Outline / Road Map '
---

Abstract
========

we will keep it to the end.

Introduction
============

General intoduction
-------------------

-   IEEE 802.15.4 overview (1 paragraph).

-   TSCH Table Structure.

-   6top protocol and cell reservation.

The project objectives and Results
----------------------------------

-   Randomity of cell selection in 6 top.

-   Identifying the problem.(collision in the Dedicated cells of the
    TSCH tables between neighbor nodes)

-   The suggested solution. (local mutual execlusion while reserving
    cells using 6top protocol)

Background
==========

6top cell reservation
---------------------

-   The rule of 6top.

-   2-step 6top Transaction

-   3-step 6top Transaction

-   The communication of the cell reservation and deletion in the shared
    slot.

filtering of the RX at the mac sublayer
---------------------------------------

currently reading for This section ***to be updated soon***

The concept of collision, hidden and exposed terminal.
------------------------------------------------------

(collision only occurs at the reception)

Proposed Mechanism
==================

-   The new created structure that will reserve the cells taken by the
    neighbors.

-   The use of the cell reservation Response to update the created
    structure.

-   An schematics to explain the problem and the solution.

-   Why we need to buffer the reserved cells , and how it’s going to
    improve our approach.

-   The calculation of the buffer length.

-   The used value and why it fits the topologies.

Results
=======

***to be discussed with the supervisor, I will supply many options for
the representions to choose the best fit for us***

Related Work
============

-   The work done by Muraoka et al (the simulator creators), *“6 Top
    Housekeeping”*

-   The work done by Phan Duy et al , a paper published in 22/03/2017
    dealed with the same problem we are trying to solve.(I will supply
    you with the paper)

-   Compariasno between Housekeeping and our approach.

Conclusion
==========

we will keep it to the end.

[1]{}

Q.Wang, and X. Vilajosana, *6top Protocol (6P). Internet Engineering
Task Force, Tech. Rep. draft-ietf-6tisch-6top-protocol-00* 1em plus
0.5em minus
0.4emhttps://tools.ietf.org/html/draft-ietf-6tisch-6top-protocol-00 ,
April 2016.

T. Watteyne et al, *Using IEEE 802.15.4e Time-Slotted Channel Hopping
(TSCH) in the Internet of Things (IoT): Problem Statement* 1em plus
0.5em minus 0.4emhttps://tools.ietf.org/html/rfc7554 , May 2015.

T. Winter et al, *RPL: IPv6 Routing Protocol for Low-Power and Lossy
Networks* 1em plus 0.5em minus 0.4emhttps://tools.ietf.org/html/rfc6550
, March 2012.

D. Dujovne et al, *6tisch: deterministic ip-enabled industrial
internet(of things)* 1em plus 0.5em minus 0.4emIEEE Communications
Magazine — Communications Standards Supplement ,December 2014.

J. Tripathi et al, *A Performance Evaluation Study of RPL: Routing
Protocol for Low Power and Lossy Networks* 1em plus 0.5em minus
0.4emInformation Sciences and Systems (CISS), 44th Annual Conference on
(pp. 1-6). IEEE , March 2010.

F. Theoleyre and G. Papadopoulos, *Experimental Validation of a
Distributed Self-Configured 6TiSCH with Traffic Isolation in Low Power
Lossy Networks* 1em plus 0.5em minus 0.4emProceedings of the 19th ACM
International Conference on Modeling, Analysis and Simulation of
Wireless and Mobile Systems (pp. 102-110). ACM , November 2017.

N. Accettura et al, *A Decentralized Traffic Aware Scheduling in 6TiSCH
Networks: Design and Experimental Evaluation* 1em plus 0.5em minus
0.4emIEEE Internet of Things Journal, 2(6), 455-470 , December 2015.

M. R. Palattella et al, *On-the-Fly Bandwidth Reservation for 6TiSCH
Wireless Industrial Networks* 1em plus 0.5em minus 0.4emIEEE Sensors
Journal, 16(2), 550-560, September 2015.

M. R. Palattella et al, *Traffic Aware Scheduling Algorithm for Reliable
Low-Power Multi-Hop IEEE 802.15.4e Networks* 1em plus 0.5em minus
0.4emIEEE 23rd International Symposium on Personal, Indoor and Mobile
Radio Communications - (PIMRC), September 2012.

N. Accettura et al, *Decentralized Traffic Aware Scheduling for
Multi-hop Low Power Lossy Networks in the Internet of Things* 1em plus
0.5em minus 0.4emIn World of Wireless, Mobile and Multimedia Networks
(WoWMoM), 2013 IEEE 14th International Symposium and Workshops on a (pp.
1-6). IEEE, June 2013.

S. Duquennoy et al, *Orchestra: Robust Mesh Networks Through
Autonomously Scheduled TSCH* 1em plus 0.5em minus 0.4emProceedings of
the 13th ACM Conference on Embedded Networked Sensor Systems (pp.
337-350). ACM, November 2015.

K. Muraoka et al, *Simple Distributed Scheduling With Collision
Detection in TSCH Networks* 1em plus 0.5em minus 0.4emIEEE Sensors
Journal, 16(15), 5848-5849, May 2016.

L. Lamport, *Time, clocks, and the ordering of events in a distributed
system* 1em plus 0.5em minus 0.4emCommunications of the ACM, 21(7),
558-565, July 1978.

T. P. Duy , *Distributed cell selection for scheduling function in
6TiSCH networks* 1em plus 0.5em minus 0.4emComputer Standards and
Interfaces, 53, 80-88, March 2017.
