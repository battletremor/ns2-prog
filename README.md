# ns2-wired-prog
CN lab part A programs

# 1st
Simulate a four node point-to-point network with duplex link as follows: n0-n2, n1-n2 and n2-n3. Apply TCP agent between n0-n3 and UDP agent between n1-n3. Apply relevant applications over TCP and UDP agents. Set the queue size and vary the bandwidth.Find the number of packet dropped and received by TCP/UDP using awk script and grep command.

# 2nd
Simulate the different types of Internet traffic such as FTP and Telnet over a network, Plot congestion window and analyze the throughput.

# 3rd
Set up the topology with 6 nodes, and demonstrate the working of Distance vector routing protocol. The link between 1 and 4 breaks at 1.0ms and comes up at 3.0ms. Assume that the source node 0 transmits packets to node 5. Plot the congestion window when TCP sends packets via 4, 5, 6. Assume your own parameters for bandwidth and delay.

# 4th
Consider a client and a server. The server is running a FTP application over TCP. The client sends a request to download a file of size 10 MB from the server. Write a TCL script to simulate this scenario. Let node n0 be the server and node n1 be the client. TCP packet size is 1500 Bytes.

# 5th
Set up topology and demonstrate the working of multicast routing protocol. Plot the congestion window for the source node and write your observation on protocol performance. Assume your own parameters for bandwidth and delay.
