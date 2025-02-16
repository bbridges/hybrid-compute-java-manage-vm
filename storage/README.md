# hybrid-storage-java-manage-storage-account

Azure Stack Storage sample for managing storage accounts:

- Create a storage account
- Get | regenerate storage account access keys
- Create another storage account
- List storage accounts
- Delete a storage account

## Running this Sample

To run this sample:

1. Clone the repository using the following command:

   ```
   $ git clone https://github.com/Azure-Samples/Hybrid-Java-Samples.git
   ```

2. Create an Azure service principal and assign a role to access the subscription. For instructions on creating a service principal in Azure Stack, see [Create a service principal with an application secret](https://docs.microsoft.com/en-us/azure/active-directory/develop/howto-create-service-principal-portal#option-2-create-a-new-application-secret).

3. Copy the settings file `azureAppSpConfig.json.dist` to `azureAppSpConfig.json` and fill in the configuration settings from the service principal.

4. Change directory to sample:

   ```
   $ cd storage
   ```

5. Run the sample:

   ```
   $ mvn clean compile
   $ mvn exec:java
   ```

## More information

[Java on Azure](https://azure.microsoft.com/develop/java/)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
