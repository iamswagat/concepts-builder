# Cloud - Amazon Web Service (Notes)

## Level 0: Prerequisites

1. Understanding of Cloud computing
2. Microsoft / Linux Essentials
3. Networking Essentials
4. Working Knowledge of Virtualization
5. Storage Fundamentals
6. AWS Newsletter *(optional)*
7. Free Account with AWS

## Level 0: Intro to Cloud

Cloud categorized under
 1. __Cloud Application__ ( also called Software as a Service or SaaS )

 **understand :** application running remotely which is managed by service provider, accessible vis internet

 **aside :** multi-tenant | shared instance with many customer | service provider responsible for security and storing customer data

 **risk :** trust on service provider for availabilty and security | storing client data outside the boundary of resident country

 2. Cloud Platform

 **understand :** VMs, Storage, etc remotely provided managed by service provider, accessible via internet

 **aside :** similar to classical hosting | difference >>> immeditate access to the broader services & pay as you use

 **aside :** cloud platform technologies || __IaaS__ or _Infrastructure as a Service_ ( Elastic Cloud Compute EC2 ) >>> Developer create, use and manage VMs, Storage etc || __PaaS__ or _Platform as a Service_ ( Elastic Beanstalk ) >>> Developer create, use, manage applications without viewing VMs, storage etc || __CaaS__ or _Container as a Service_ ( Elastic Container Service ECS ) >>> rather using VM, deploy and manage Containers and run apps within the container || __FaaS__ or _Function as a Service_ ( Lambda ) >>> serverless computing, build, manage application as functions and invoke the function directly | charged based on the execution time

 ![Cloud Platform Services](https://cdn-images-1.medium.com/max/1600/1*g-3sIos1ekWYdP2rXODj9Q.png)

 3. Private Cloud

 **understand :** approaches >>> || providing public cloud technologies for on-premise servers ( Azure Stack ) || open source software offering cloud services for on-premise servers ( OpenStack ) || providing public cloud technologies in IOT devices (AWS Greengrass).

 **aside :** Automation of repeatable process for on-premise infrastructure

![Cloud](https://cdn-images-1.medium.com/max/1200/1*DYoadhgfpZCMRCMKNUpQ6A.png)
