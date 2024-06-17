# Azure Event Hubs System API Example
This repository contains resources to assist in implementing Azure Event Hubs integrations using the [Azure Event Hubs REST API](https://learn.microsoft.com/en-us/rest/api/eventhub) and the MuleSoft Anypoint Platform.

- The folder **anypoint-studio-project** includes the implementation of a simple API that exposes a single resource, `/events`, and one method, `POST`, which publishes the request body to Azure Event Hubs.
- The folder **documentation** contains a [how to guide](documentation/how-to-guide.md) for integrating with Azure Event Hubs. First, it guides you through an approach to configuring your Azure account and provisioning all the required resources. Then, it describes the sample system API to illustrate how to integrate with Azure Event Hubs.
- The folder **postman-collection** contains a basic Postman collection you could use for testing your Azure configuration.
