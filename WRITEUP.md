# Reasource Option i used

## Available resource option for deploying the app
 
###  **Virtual Machine**
 With VM, you get full access to virtual machines, so purchasing af hardware wouldn't be necessary. We can get both Linux and windows.Flexible types and sizes are available. Also support custom images/

 ### **App Service**
 With App Servive, its an http based service for hosting web applications, APIs and mobile backends. It support multiple languages like NodeJS, Java, dotNet Core, Ruby, PHP, and Python, 

- It provides High availability and auto scaling, for both Linux and Windows
- it supports CI/CD using github, azure devops or any git repos,

App Service can scale  either vertically or horizontally.
Vertical scaling is such that (there can be increases or decreases in resources allocated to our app services such as the amount of CPUs or RAMs by changing the pricing tier

Horizontally scaling is such that (there can be increases or decreases in the number of VMs instances our app service is running)



## **Costs, scalability, availability, and workflow**
**Cost:** VMs seems to be more expensive compared to Azure app service because its an Infrastructure as a servive. You don't have to worry about purchasing or maintaining hardware. Usually, a designated personel is fully responsible for maintaining the VM, so its also labour intensive.

 On the other hand, Azure app service is a Plartform as a service and its cost varies based on the plan one chooses, the three tier availabe are  Dev/Test (free option), Production, Isolated.
Therefore, Azure VMs are more expensive to run in comparison to Azure App Service.


**Scalability:** Azure VMs enables you to quickly scale up resources to accommodate spikes in demand for your application, then scale resources back down again when activity decreases to save money.

Azure App Service have constraints such as RAM and CPU capacity in comparison to Azure VMs. Hence, Azure VMs are preferred for application development, management and maintenace, which have scope to expand for future purpose.


**Availability:** Azure VM Improves business continuity and disaster recovery. this will help in achieving high uptime for the business. 

In comparison, App Service provides framework that developers can build upon to develop or customize cloud-based applications using built-in software components. Here the availabilty is limited to the capacity of plan that is used.


**Workflow:** Azure VMs gives us a full control of the OS or customer software, they are excellent choice for testing and development, one can quickly spin up different OSs and application configurations and turn them down once, they are no longer needed. 

On the other hand app service helps us deploy lightweight applications and services with low performance compute with use case of 14GB of RAM and less than 4 virtual CPUs


## **Why i chose App Service**
It is the excellence choice for deplying lightweight application and services, used for application that does not need high performance compute. Since we need less than 14GB of RAm and less than 4 virtual CPUs

## **Conclusion**
I used App Service because the flask application is a lightweight web application and requires less than 14GB of RAM and 4 CPUs

## **Factors that can influence my decision in the future.**
in a case where the application has grown and is being used by millions of users. RAM capacity higher than 14GB will be needed, also 4 CPUS provided by App service, will not be enough.

Here,VM will be the best choice because we will get full control of the hardware and software.