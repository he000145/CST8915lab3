# CST8915 Lab 3: Algonquin Pet Store

**Student Name**: Yiming He
**Student ID**: 041-282-545
**Course**: CST8915 Full-stack Cloud-native Development
**Semester**: Winter 2026

---

## Demo Video

🎥 [Watch Demo Video](https://youtu.be/UwGGfYot3D0)

---

## Reflection Questions

### What challenges did you encounter when configuring environment variables in the GitHub Actions workflow?

     It's not like setting the environment in env. file. Actions workflow is a build-deploy pipeline, so I need setting envirnoment in that process. I probably won't find this way if I deploy this storefront web without mentions.

### How does deploying microservices on Azure Web App Service differ from running them locally?

    Running them locally do not need set up any port setting or any specified URL for each service. they can communicate to localhost and local ports, and configuration is simple based on the same machine. Moreover, deploying on Azure Web App Service also need take care the problem of CORS or firewall. 

### Why is it important to use environment variables for configurations in a cloud environment?

    Using environment variables for configurations is the way to improve security. Don't expose any sensitive information to the public. Moreover, it also makes application deployments repeatable across environments without changing code or rebuilding. For example, testing and deploying in different environments only need to change variables in env. file.

## Links to the three service repositories you created

- order-service: https://github.com/he000145/order-service
- product-service: https://github.com/he000145/product-service-L3P
- store-front: https://github.com/he000145/store-front