# **Education**

### **University of California, San Diego** | Graduated June 2018

**Major:**         Computer Science, B.S.
# **Skills**

**Programming Language:** C, C++, Python, Java, Ruby, x86/ARM assembly, PHP, OCaml, Haskell

**Operating Systems:** Linux, Windows

**Software:** Bash Shell, Git, Vim, tmux, valgrind, gdb, radare2, VirtualBox, Docker

# **Work History**

### **Google /** GRPC Contractor | October 2018 - March 2019

Debug user-reported issues related to Ruby and PHP for Google&#39;s open-source RPC project

- Enable Process forking support for PHP GRPC calls by cleaning up GRPC objects
- Gracefully shutdown GRPC servers by registering signal handlers in Ruby
- Couple GRPC Ruby code generator and Protobuf to support Ruby package namespace resolution
- Investigate adding server reflection to GRPC Ruby so users could debug using GRPC calls
- Investigate GRPC Ruby to detect a cancelled a cancelled GRPC call on the server side

### **Synopsys Inc. /** IT Global Solutions Intern | September 2015 - July 2016

Operate as Level 1 support (walk-ups, phone calls and chats) for internal Synopsys employees

- Troubleshoot problems with business applications and/or Windows computer systems
- Manage employee active directory accounts

# **Projects**

**Surfstore –** Distributed, replicated file system that implements two phase commit. Implemented in Java with GRPC

- Utilizes two phase commit for reliable data replication across follower servers
- Utilizes GRPC for communication between nodes (client, leader/follower servers)

**HTTP Server -** Server that serves HTTP 1.1 GET requests. Implemented in C++ Unix sockets API

- Utilizes Unix sockets API to communicate with clients over the network
- Utilizes C++&#39;s pthreads library to handle concurrent client requests

**Sliding Window -** Implementation of the sliding window protocol in TCP. Implemented using C

- Utilizes retransmission of lost/dropped frames to guarantee reliable transmission
- Utilizes a cyclic redundancy check to guarantee message transmitted is correct
- Utilizes a dynamically sized hash table to keep track of last acknowledged sequence number

**Simple Router** - Emulate a router that receives and routes raw Ethernet packets. Implemented in C

- Utilizes a routing table to match longest matching prefix to correctly route packets
- Handles ARP request/response, packet routing, and generating ICMP responses

**Anaconda -** Compiles a high-level language to X86 assembly. Implemented in Haskell and C

- Supports variable assignment, conditional branching, looping, recursion, and garbage collection

**UMIX OS** - A partial UNIX operating system implementation. Implemented in C

- Implements context switching by saving point of execution and yielding to another process
- Compare and benchmark 4 different ways of scheduling: fifo, lifo, round-robin and fair share
- Implements semaphores to synchronize emulated car traffic across a single-lane bridge
- Implements user-level threading by partitioning heap memory and saving current point of execution

**Great Cannon** – Emulated distributed denial-of-service attack. Implemented in Python

- Man-in-the-middle attack that takes unencrypted http packets and inserts an iframe to the target website
- Keeps track of TCP SYN/ACK numbers to trick server/client that connection is still valid
