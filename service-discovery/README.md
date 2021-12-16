# Service Discovery

The service discovery is the automatic detection of devices and services over the network. 
In other words, service discovery is how an application and microservices connect in the distributed environment. Service discovery implementations include both:
- The **central server** that maintains a global view of the address.
- The **clients** that connect to the central server can update and retrieve the address.

![image](https://user-images.githubusercontent.com/8929789/146406296-1a2006ac-d85d-4ec5-b1a5-a70e5eb5bb19.png)

## Run the applications
1. Run [Discovery EurekaServer](discovery-server)

3. Run two instances of the [Service](service) using following configuration paramters:
<img src="https://user-images.githubusercontent.com/8929789/146409120-a7c11647-6f25-44a1-9836-dfe5e6170877.png" width="600" height="200">
<img src="https://user-images.githubusercontent.com/8929789/146409058-bc106bc6-2107-4946-9771-d9b1dccd6b09.png" width="600" height="200">

4. Run [Client](client)
 
6. Visit following link - `http://localhost:8888/`
