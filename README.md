## Simple port scanner ##
This is a simple representation of how sockets work in C. It scans a specified range of ports on a target IP address to identify open ports.

### Usage ###
#### Compile the code. ####
gcc -o scan port_scanner.c
#### Run the scanner. ####
./scan IPaddress Startport Endport
