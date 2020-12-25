# Aim: To understand and design the point-to-point network structure. Also here we understand the working of TCP and UDP transport protocol.
# Theory: 
    • Create a simulator object. 
    • We open a file for writing that is going to be used for the “nam” trace data
    • Monitor the queue and set Queue limit. 
    • We now attach the agent to the nodes. 
    • Now we attach the application to run on top of these nodes
    • We now connect the agent and the application for its working
    • Set the simulation time
    • The next step is to add a 'finish' procedure that closes the trace file and starts nam. 

# Expected output: Animated 4 node structure is displayed. We need to see the trace file to understand what has happened to the data flow.



# Grep

# grep “^r” ex1.tr       #packets received

# To run the awk script you need to execute the command shown bellow on the terminal.

 # awk   –f   ex1.awk   ex1.tr 
