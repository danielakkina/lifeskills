# **Performance and Scalability**

## **What is Performance?**
  
  - Basically, the performance of the system depends on two parameters speed and responsiveness. These two parameters decide the efficiency of the system. 
  - These issues arise when the system gets a heavy load from the users. Load on the system will affect the response time of the system.

## **What is Scalability?**
 
 - Scalability is the measurement of how well that system responds to changes by adding or removing resources to meet demands. 
 - There are two types of scaling:
 
    - Vertical Scaling.
    - Horizontal Scaling.

## **What is a Load Balancer?**

- Load balancing is a key technique used to improve the performance and scalability of a system. It involves distributing all incoming requests to multiple servers to avoid the load from a single server.
- This can improve the performance and availability of a system. The load balancer is act as a mediator between the client and server to control the load on the servers.

                
- There are two types of load balancers:
     
     - Hardware-based load balancers.
     - Software-based load balancers.
- when choosing a load balancer, it is important to consider the specific requirements like the number of requests per second and the size of the request.
- Hardware-based load balancers are more expensive than software because it provides better performance and reliability.

## **Vertical Scaling**

- Vertical scaling involves increasing the resources of a single server by adding more memory, CPU, or hard disk space. 
- This technic quickly improves the performance of a  server, but it is limited to some extent.

- Again there is a possibility of upgrading to more powerful hardware. 
- Due to only one server there is a risk if the server fails due to heavy load. 

## **Horizontal Scaling**

- Horizontal scaling involves adding more servers to a system so that the load can be shared to multiple servers. 
- This approach is more flexible and scalable and also improves the overall performance and availability of a system.

- Due to multiple servers there is less risk if any server fails.
- It is very helpful to scale down when the clients get reduced and also cost reduces.

## **Which Should You Choose And When?**

- **cost**: Initial hardware setup costs for horizontal upgrades are higher. If you are working on a low budget and need to add more resources to infrastructure then vertical scaling may be the best option for you.
- **Reliability**: Horizontal scaling gives you a more reliable system. It increases redundancy and if one machine fails, another may be able to pick up the slack temporarily.
- **Future-Proffing**: Adding additional machines through horizontal scaling will increase the overall performance, so it's better to use horizontal scaling.
- **Topographic distribution**: If you plan to have nationwide or global clients, It's better to use horizontal scaling.

## **Resources**

- https://www.dynatrace.com/resources/ebooks/javabook/performance-and-scalability/
- https://youtu.be/wte3dmk8fmc
- https://youtu.be/sHPVVdITpwc