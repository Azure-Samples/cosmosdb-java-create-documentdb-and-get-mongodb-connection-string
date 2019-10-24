---
page_type: sample
languages:
- java
products:
- azure
- azure-cosmos-db
description: "Azure Cosmos DB sample for high availability."
urlFragment: cosmosdb-java-create-documentdb-and-get-mongodb-connection-string
---

# Create Azure Cosmos DB with MongoDB support (Java)

Azure Cosmos DB sample for high availability.

- Create a Cosmos DB configured with MongoDB kind.
- Get the mongodb connection string
- Delete the Cosmos DB.
 

## Running this sample

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

```bash
git clone https://github.com/Azure-Samples/cosmosdb-java-create-documentdb-and-get-mongodb-connection-string.git
cd cosmosdb-java-create-documentdb-and-get-mongodb-connection-string
mvn clean compile exec:java
```

## More information

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
