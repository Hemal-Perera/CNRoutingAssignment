# CNRoutingAssignment

This repo contains my Packet Tracer files and the final report for the Computer Networks routing assignment. The main goal was to set up routers, configure different routing protocols, and make sure all the networks could actually communicate. 

Here is a quick breakdown of what I did:

**Task 1: Basic Router Setup**
Just doing the initial config on the router. I changed the hostname to match the `KandyNSBM_StudentID` format and secured the console access by setting up a login authentication with the password `NSBM`.

**Task 2: Static Routing**
For this one, I worked with a topology that had three routers and three separate networks. I manually configured all the IP addresses and set up static routes on every router so that all three networks could ping each other successfully.

**Task 3: Dynamic Routing (RIP & EIGRP)**
This part was split into two steps using a different network layout:
* First, I configured RIP routing across all the routers and verified the connections were working.
* After that was done and tested, I removed the RIP configurations entirely and set up EIGRP routing instead, checking the pings again to ensure full network communication.

**What's inside this repo:**
* Three `.pkt` (Cisco Packet Tracer) files covering the different tasks.
* The main Assignment Report (PDF) containing all my configuration commands, screenshots of the routing tables, and the ping test evidence.
