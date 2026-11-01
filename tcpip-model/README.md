# How the TCP/IP Model Actually Works
This lesson will give you a big picture on how networks work. We'll go over it more on detail, such as how each protocol specifically works, in more detail throughout the course.

## The Importance of Protocols and Standards
- A **protocol** is a set of rules defining how data should be communicated between devices over a network
  - For humans, we have specific social rules for different aspects of communication. For networks, those rules are protocols.
- A **standard** is an agreed-upon way for how a protocol or technology should work
  - A group of people could define a protocol to understand each other, but it if you apply that protocol to a different group, they will not understand you as it has not been agreed-upon and they have a defined how to communicate differently.
  - In the past, vendors or computers would create their own proprietary protocols, which meant only devices of the same vendor could understand each other. Standard organizations have made standards for protocols and technologies to combat this.
  - Standard Organizations are independent organizations that create standards containing people from various companies
    - IEEE = Institute of Electrical and Electronic Engineers
      - developed many of the technologies used in LANs: Ethernet (IEEE 802.3) and WiFI (802.11)
    - IETF = Internet Engineering Task Force -
      - open community that defines protocols used in the internet: TCP, IP, UDP, HTTP, DNS
      - publishes standards in documents called RFCs = Request for Comments

## What is a network model?
- a way of grouping protocols into layers based on the job they do
