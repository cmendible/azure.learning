## Exercise 2: Create Azure Virtual Machine
  
### Scenario
  
In this exercise, you will create an Azure Virtual Machine.

The main tasks for this exercise are as follows:

1. Create an Azure Virtual Machine
1. Inspect the Created Virtual Machine

#### Task 1: Create an Azure Virtual Machine
  
1. In the **Console** window, type the following command:

   ``` shell
   az vm create -n MyVM -g azure_fundamentals --image UbuntuLTS
   ```

#### Task 2: Inspect the Created Virtual Machine
  
1. In the **Console** window, type the following command:

   ``` shell
   az vm show -n MyVM -g azure_fundamentals
   ```