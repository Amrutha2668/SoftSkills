# Soltion for Performance and Scaling

## **Description**
**A possible approach to overcome the performance and scaling issues**

## **Abstract**
Problems causing to the project's **performance by increasing in workload and scaling issues due to less availability of the resources**,
suggested to use load balancers acts as **traffic cop** also using **vertical scaling** that adds the resources as on-demand and using **horizontal scaling** is the most required technology whenever a high availability of service is required.

## **Overview**:
We are implementing the balance loaders, vertical/up scaling and horizontal/out scaling in order to overcome the problems we are facing due to performance and scaling issues and using these technologies we must make sure to maintain the performance outcome.

## **Introduction**
As we are facing the performance issues, we can overcome them by using *Load balancers*, and the scaling problem can overcome by using the horizontal scaling and vertical scaling.


## **Method**
### **Performance issues**:

When a large amount of requests is made at a time our server must be able to handle all that requests and should be able to deliver the correct data to the requested client.

When our system fails to handle multiple requests simultaneously when the large number of requests is made performance will be affected.

* **To overcome this we have load balancers approach**:

  * Load balancers are also known as a server farm or server pool, a group of separate physical machines that are configured with the same applications and work like one logical server. 

  * Load balancers distribute workload among the clustered servers and make sure that no server is overworked, this solves the performance by using load balancers, and hence we can make use of load balancers in our project to overcome this issue.

### **Scaling issues**:

Scaling is the characteristic of an organization, 
system model, or function that describes its capability to cope and perform well under the increased or expanding workload. 

As we are facing scaling issues, our system is lagging in handling the workload, A system that scales well will be able to maintain or even increase its level of performance or efficiency under a large workload.

**There are two approaches for the load balancers :**

 * Vertical Scaling (Scaling Up) :
     * Vertical scaling means upgrade of server hardware. Adding additional hardware equipment to cope with an increasing workload.

     * Keeps the existing infrastructure but adds computing power, it allows us to run the existing code on machine with better specifications, by vertical scaling, we can increase the capacity of a single machine results in increasing its throughput.

* Horizontal Scaling (Scaling Out):
    * Horizontal scaling must be used whenever the high availability of services is required.

    * It involves adding more processing physical machines to the server. Increases the number of nodes in the cluster, that would reduce the responsibilities of each member node. It is used for high level computing and for applications and services.

These two approaches will effectively resolve the scaling problem our project is going through.

## **Conclusion:**
The Approached methods and ideologies can be implemented in the project to minimize the issues that occurred in the project.

## **References**
[1] Refferd load balancers from Website.

Available: https://www.nginx.com/resources/glossary/load-balancing/

[2] Reffered Vertical Scaling and horizontal scaling from Websites.

Available: 
[1] https://www.missioncloud.com/blog/horizontal-vs-vertical-scaling-which-is-right-for-your-app
           [2] https://www.section.io/blog/scaling-horizontally-vs-vertically/
           [3] https://www.esds.co.in/blog/what-is-the-difference-between-horizontal-vertical-scaling/#sthash.la1jXuuy.dpbs
           [4] https://touchstonesecurity.com/horizontal-vs-vertical-scaling-what-you-need-to-know/
