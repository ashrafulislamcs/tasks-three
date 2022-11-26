![Untitled Diagram](https://user-images.githubusercontent.com/57341368/178077032-d671f34e-03b2-431d-b149-f6ab81339ca0.png)

We can host the microservice application in cloud platform such as in AWS, where they provide integrated console for Kubernetes clusters.
Kubernetes clusted can be deployed from infrastructure as code software tool like ansible, terraform which reduce the deployment time and complexity.
Over cloud platform hardware maintenance can be reduced as it is managed by the cloud provider.
Application will be hosted under network load balancing and multiple pods which will help to balance the traffic within the pods. If any pod dies, with the help of load balance traffic will be distribute to other pods. Moreover, under kubernetes cluster pods regenerate upon dying.
Monitoring tool such as zabbix, kibana, prometheus should be implemented for the routine inspection of the clusters resources
