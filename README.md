NetClock
========

This repository provides resources for the ECE 4564 NetClock project.

To the Project Team:
--------------------

To build the image, you can execute the following command: 
```
docker build -t net-clock .
```

To run the built image, you can execute the following command:
```
docker run -it --rm net-clock
```

Note: the server works fine as a container but we could not connect the client to it. Though both the server and the client work if Docker is not involved. 

This might be because the client is not on the same (virtual) network to connect to the server.