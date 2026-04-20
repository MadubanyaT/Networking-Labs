# STP Loop Prevention Practical

## Overview
In this practical lab I will be touching the surface of Spanning Tree Protocol (STP) explaining:
- Loops created in Ethernet Layer 2 switches.
- What STP is.
- How STP prevents those loops from occurring.

There is a packet-tracer file attached that I will be using to demonstrate everything, there is also a docx file with questions and answers for this practical.

## How loops are created in Ethernet Layer 2 switches?
In a network design (Hierarchical) we often create redundant paths, this implements fault-tolerance within a network. Fault tolerance is very crucial in a network because it accommodates single-point failure ensuring that the network is operating efficiently. This works perfectly with intermediary network devices such as routers because they are Layer 3 devices meaning a packet will not be alive forever if it does not finds its destination, it will eventually be dropped due to Hop-count and Time-to-Live (TTL). But with switches this is a problem because they are Layer 2 devices, they do not have the Layer 3 mechanisms like TTL. Therefore a loop is created when broadcast frames are sent and there is no implementation of STP causing the network to be unusable.  
*The shaded area of the figure below shows an example of a network design that would cause a loop if STP is not implemented.*![Without STP](./images/Without-STP.png)

## What is STP?

## How does STP prevents those loops from occurring?



