## Exercise 1: Using the Azure CLI
  
### Scenario
  
In this exercise, you will install and use the Azure CLI. 

The main tasks for this exercise are as follows:

1. Install the Azure CLI

1. Connect to your Azure subscription by using the Azure CLI

1. Manage your Azure subscription by using the Azure CLI

1. Prepare for the next module

#### Task 1: Install the Azure CLI
  
1. On MIA-CL1, in Microsoft Edge, browse to [https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest) and note the **Download the MSI installer** link.

1. Do not initiate the installation. Instead, close Microsoft Edge.

    > **Note**: Azure CLI is already preinstalled on the lab VM.

#### Task 2: Connect to your Azure subscription by using the Azure CLI
  
1. On MIA-CL1, start the command prompt as an administrator.

1. In the **Console** window, type the following command:

   ``` shell
   az
   ```

    > **Note**: A summary of the most-common Azure CLI commands displays.

1. At the command prompt, run the following command:

   ``` shell
   az login
   ```

1. When prompted, sign in with the Microsoft account that is the Service Administrator of your Azure subscription. 

1. Back in the **Console** window, note the JSON-formatted output displaying information about the current session, including the ID of the subscription that your account is associated with. 

1. In case of an error, repeat the steps 3 through 5.

#### Task 3: Manage your Azure subscription by using the Azure CLI
  
1. List your subscriptions by running the following command:

   ``` shell
   az account list
   ```

1. Copy the value of the **id** property displayed in the output of the preceding command.

1. Run the following command, pasting the copied entry to replace the value of the `<value of the subscription id property>` placeholder:

   ``` shell
   az account set --subscription <value of the subscription id property>
   ```

    > **Note**: If you had multiple subscriptions, you would use the preceding command to specify the Azure subscription you want to work with in the current Azure CLI session.

1. To retrieve the types of Azure Resource Manager providers available in your subscription, run the following command:

   ``` shell
   az provider list
   ```

    > **Note**: The output of the command contains each Azure Resource Provider available in your subscription and its registration state (the provider must be registered before you can use it).

1. To list all the Azure datacenters available in the current subscription, run the following command:

   ``` shell
   az account list-locations
   ```

1. To identify the list of resources that are implemented by the Microsoft.Compute provider (which includes Azure Virtual Machines) along with the list of locations where they are available, run the following command:

   ``` shell
   az provider show --namespace Microsoft.Compute
   ```

1. Close the **Console** window.
