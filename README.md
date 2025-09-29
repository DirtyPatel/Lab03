## What challenges did you encounter when configuring environment variables in the GitHub Actions workflow?
- We didn’t use GitHub Actions since the student subscription didn’t let us make a Static Web App. Instead, we ran it on a VM, so we didn’t really face environment variable issues in GitHub.


## How does deploying microservices on Azure Web App Service differ from running them locally?
- Locally, everything runs on one machine and is easy to debug. On Azure Web App, services run separately, configs come from Azure settings, and Azure handles scaling, networking, and logs.


## Why is it important to use environment variables for configurations in a cloud environment?
- They keep secrets safe, make it easy to switch between dev/test/prod, and ensure all app instances use the same settings 


## Youtube Video

https://youtu.be/VRHq5JJnwKw

## Links to the repos
 
https://github.com/DirtyPatel/store-front

https://github.com/DirtyPatel/product-service

https://github.com/DirtyPatel/order-service