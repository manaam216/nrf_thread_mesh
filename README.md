# nrf_thread_mesh

### Introduction
A basic example to run thread mesh network on nRF52840 dev kits.

### Modification
Modification has been made to send ACK message from server to client if a message is received. When the Minimal Thread Device sends a message to server which is a FTD, it goes to sleep. After 100ms it wakes up again and polls the network to get the ACK message which was sent by server
