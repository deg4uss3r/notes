# Network Monitoring with AMP

AMP == Active Measurement Project 

[WAND AMP](https://amp.wand.net.nz/browser)

    putting packets on the network and measuring how they behave 
        e.g. ping
    how quickly?
    how much? 
    who answers?
    what did they say?

Can interfere with "real" traffic on the network, and the own measturments too if they are not careful

Continous, distributed active network measurement 

data exploration 
    all the data is avaiable on the website to browser and compose

event detection 
    to save actually have to look at **all** the data

first probes installed in December 1998

160 probes across 25 countries

originally a combination cron, shell, and text files
    rewritten in C
    **maybe I could rewrite in rust??**

NSF funding ended in 2006

new version written over the last few years, using lessons learnt
    dependencies aren't always evil
    process vs threads

added test to infrastructure targets outside our control 
    dns http

protobufs to send data, and databases to store data vs flat files

using influx time series database

latency 
    ICMP, TCP, UDP, DNS

UDP traceroute

TCP upload and download throughput

HTTP page download

YouTube video streaming 
    uses Chromium

## AMP client

has a scheduler and sends jobs out via a schedule 

controller helps control jobs that require multiple nodes or interfaces




