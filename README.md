# DOCKER_FILE_Implentation-of-network-function-virtualization_NFV

As technology advances, the way of implementing the network functions has been changed. Network Function Virtualization (NFV) becomes the popular and easiest way of running the network function. Network functions, including switches, routers, and firewalls, can be virtualized using a technique called network functions virtualization (NFV). Each of these network functions in a traditional network requires running on specialized hardware. but with the help of NFV, these network functions run on the virtual machine. Docker is a software platform which helps to virtualize and manage the NFV using containers. Although each network function is executed in a separate container, security challenges exist because each container is running on the same host machine. The security issues of operating NFV on a container platform are discussed by this implemetation. Different runt imes for Docker have a significant influence in security. The service function chain (SFC) was built as part of this project utilizing different Docker run times. the run-time used in this implementation are runc and kata containers. the performance of both docker run-time has been evaluated in this  with respect to boot time, memory utilization, network performance and security related. threats.

Created the virtual router. Which will route the packets among multiple clients. Clients will be in the different subnets. router is the network layer device which helps to communicate between the clients and access the internet. It routes the packets from source to the destination. And it communicates between multiple subnets in the network. This virtual router perform the same operation as the physical router.

This network structure has two subnets. the client1, client3 and client5 are resides in the same subnet, Similarly client2, client4 and client6 resides in same subnets. If these two subnets want to communicate between them then it need a router to send the packets. One router is also created in this network. This router could able to communicate between these two subnets. due to this network structure, Clients in the different network could communicate through the router image. This virtual network structure implemented  using docker platform. and the similar network structure implemented using different docker run time.
