---
title: About
layout: page
---
# Projects

## MVRLU
Multi-Version Read-Log-Update is a synchronization mechanism that
extends RLU using mutli-versioning, while preserving the benefits of
RLU like multi-pointer update, a simple & intuitive programming model,
and good performance for read-mostly workloads.  MV-RLU alleviates
problems such as high contention of global clock (using a hardware
clock-based timestamp); slow read performance with an autonomous
garbage collector design, and slow garbage collection with
a concurrent garbage collector design that are ubiquitous to most MVCC
designs.  As a result, MV-RLU outperforms other synchronization
mechanisms in a variety of workloads and shows unmatched scalability
even in write-intensive workloads.

## Key Value Store on FPGA
During my time at Reniac, I wrote a key value store on FPGA which was
loosely based on research at ETH Zurich. The project was demoed at
Cassandra Summit 2016. [Here is a video by one of the
participant.](https://www.youtube.com/watch?v=dR41kdGglQQ)

## HDMI2USB
I contributed to the Tim's Video Project as part of Google Summer of
Code 2014. The org is trying to create open soure solution for
live streaming and recording of conference. As part of my project,
I worked on the improving the frame rate of HDMI2USB, a FPGA based
video capture device. At the end of the summer, I was able to improve
the frame rate from 10 fps to 30 fps (and hence making it usable). My
project was showcased by my mentor, [Joel Stanley](https://jms.id.au/)
, at linux.conf.au 2015. The video of his talk can be found
[here](https://www.youtube.com/watch?v=O4D-6IPX308). 

## CANSAT 2014
CANSAT is a mini-satellite building competition sponsored by NASA.
I worked as system programmer for Oorjayaan, IIIT's entry to CANSAT
2014.
![cansat]({{"assets/images/cansat.jpg" | absolute_url}})
