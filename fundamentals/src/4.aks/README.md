## Exercise 3: Create an AKS cluster
  
### Scenario
  
In this exercise, you will create an AKS cluster.

The main tasks for this exercise are as follows:

1. Create an AKS cluster
1. Inspect the created AKS Cluster

#### Task 1: Create an AKS cluster
  
1. In the **Console** window, type the following command:

   ``` shell
   az aks create -g azure_fundamentals -n myaks --generate-ssh-keys
   ```

#### Task 2: Inspect the created AKS Cluster
  
1. In the **Console** window, type the following command:

   ``` shell
   az aks get-credentials -g azure_fundamentals -n myaks
   ```

1. Use **kubectl** or **VS Code** to inspect the cluster