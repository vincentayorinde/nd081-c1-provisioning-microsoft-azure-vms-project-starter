# Reasource Option i used

## Available resource option for deploying the app
 
###  **Virtual Machine**
 With VM, you get full access to virtual machines, so purchasing af hardware wouldn't be necessary. We can get both Linux and windows.Flexible types and sizes are available. Also support custom images, high availability and scalability. They are more expensive and labor intensive as completed to the App services

 ### **App Service**
 With App Servive, its an http based service for hosting web applications, APIs and mobile backends. It support multiple languages like NodeJS, Java, dotNet Core, Ruby, PHP, and Python, 

- It provides High availability and auto scaling, for both Linux and Windows
- it supports CI/CD using github, azure devops or any git repos,

App Service can scale  either vertically or horizontally.
Vertical scaling is such that (there can be increases or decreases in resources allocated to our app services such as the amount of CPUs or RAMs by changing the pricing tier

Horizontally scaling is such that (there can be increases or decreases in the number of VMs instances our app service is running)

Moreover App Service is a PaaS. It has an app services plan that sets the amount of hardware for our application like Dev/Test (free option), Production, Isolated.


## **Why i chose App Service**
It is the excellence choice for deplying lightweight application and services, used for application that does not need high performance compute. Since we need less than 14GB of RAm and less than 4 virtual CPUs

## **Conclusion**
I used App Service because the flask application is a lightweight web application and requires less than 14GB of RAM and 4 CPUs

## **Factors that can influence my decision in the future.**
in a case where the application has grown and is being used by millions of users. RAM capacity higher than 14GB will be needed, also 4 CPUS provided by App service, will not be enough.

Here,VM will be the best choice because we will get full control of the hardware and software.