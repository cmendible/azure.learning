## Exercise 4: Create an Cosmos DB Database
  
### Scenario
  
In this exercise, you will create a Cosmos DB.

The main tasks for this exercise are as follows:

1. Create a Cosmos DB
1. Inspect the created Cosmos DB

#### Task 1: Create a Cosmos DB
  
1. In the **Console** window, type the following command to create the service:

    ``` powershell
    az cosmosdb create `
    --resource-group azure_fundamentals `
    --name mycosmosdbeveris `
    --kind GlobalDocumentDB `
    --locations "West Europe=0" "North Europe=1" `
    --default-consistency-level "Session" `
    --enable-multiple-write-locations true
    ```

1. In the **Console** window, type the following command to create the database:

    ``` powershell
    az cosmosdb database create `
    --resource-group azure_fundamentals `
    --name mycosmosdbeveris `
    --db-name fundamentals
    ```

1. In the **Console** window, type the following command to create a collection:

    ``` powershell
    az cosmosdb collection create `
    --resource-group azure_fundamentals `
    --collection-name tweets `
    --name mycosmosdbeveris `
    --db-name fundamentals `
    --partition-key-path /id `
    --throughput 1000
    ```

#### Task 2: Inspect the created AKS Cluster
  
1. Use Azure Data Studio to explorer the service