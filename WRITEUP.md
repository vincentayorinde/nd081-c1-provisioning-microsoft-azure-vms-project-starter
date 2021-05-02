# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- Pros
for VM, you get full access to virtual machines because no purchasing an hardware wouldn't be necessary.
We can get both Linux and windows.Flexible tyes and sizes are available. Also support custom images, high availabilty and scalabity
- Cons
they are more expensive as complered to the App services and labor intensive

- Pros
For App Serves, its an http based service for hosting web applications, APIs and mobile backends. It support multiple languages like NodeJS, Java, dotNet Core, Ruby, PHP, and Python, 

High availablity and auto scaling, for both Linux and Windows

it supports CI/CD using github, azure devops or any git repos,

Can scale vertically (increases or decreases resources allocated to our app services such as the amount of CPUs or RAMs by changing the pricing tier) or horizontally (increases or decreases the number of VMs instances our app service is running)

Its a PaaS. It has an app services plan sets the amount of hardware for our application like Dev/Test (free option), Production, Isolated.

Linux app service plans are cheaper than windows
 - Cons
Its limited to host server
Max 14GB ram per instance
Max of 4 CPUs
- *Choose the appropriate solution (VM or App Service) for deploying the app*
 - VM - if we need full control of the hardware or customer software, good for testing and development, you can easilly spin up a server and turn them down onces they are not needed

- App Service - excellence for deplying lightweight application and services, used for application that does not need high performance compute. Since we need less than 14GB of RAm and less than 4 virtual CPUs
- *Justify your choice*
I will use App Service because the flask application is a lightweight web application and requires less than 14GB of RAM and 4 CPUs
### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 