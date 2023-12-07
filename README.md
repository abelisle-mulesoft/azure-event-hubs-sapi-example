# Azure Event Hubs System API Example
In the current revision, this repository contains a sample system API to illustrate how to integrate with Azure Event Hubs.
- The folder `anypoint-studio-project` includes the implementation of a simple API that exposes a single resource, `/events`, and a single `Post` method. It publish JSON data to Azure Event Hubs.
- The folder `postman-collection` contains preconfigured requests we use for testing our Azure configuration. Using Postman allows us to fine-tune calling vendors' APIs more quickly. You can make changes and call APIs in seconds using Postman, whereas you need to rebuild the Mule application before you can test any changes, even if they are minor.

> :exclamation: Coming soon: a guide that provides a suggested approach for creating and configuring resources in Azure to support integrating with Azure Event Hubs. 
