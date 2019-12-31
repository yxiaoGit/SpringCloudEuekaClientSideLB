# SpringCloudEuekaClientSideLB
A demo Eureka client side load balancer by Eureka micro serice discovery from client to route calls to server instance 1 or 2

Start Eureka server on port 1,
start 2 identical aplication server on port 2 and 3, both registered to Eureka as same service name, with different output msg to identify them
start spring boot app web app client, which uses load balancer to get the server instance
demo that the access the service endpoint will alternate between two servers. 
