# Azure REST API Postman Collections
Postman collections to simplify interaction with the Azure REST APIs.
## Azure Service Bus Messaging API

Send and receive messages using the [Service Bus Messaging API](https://docs.microsoft.com/en-us/rest/api/servicebus/service-bus-runtime-rest)

To get started, edit the collection variables: **namespaceUri**, **sasKeyName** and **sasKey**. Also set the variables **queueName**, **topicName** and **subscriptionName** in the pre request script for the folders Queue and Subscription. Both scripts and variables are found by right clicking and selecting edit on the collection or folder.

If you need multiple environments you can create environment variables with the same names, they will override the collection variables. If you need multiple e.g. queues, you can copy a folder and change the variables in the pre request script.

[Full documentation here](https://documenter.getpostman.com/view/856851/collection/7TKgY9H)

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/b5e5a9f46b7343994891)