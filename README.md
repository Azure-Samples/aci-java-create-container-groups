---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Containerinstance
  platforms: java
---

# Getting Started with Containerinstance - Manage Container Instance With Multiple Container Images - in Java #


  Azure Container Instance sample for managing container instances.
     - Create an Azure container group with two container instances using Docker images "microsoft/aci-helloworld" and "microsoft/aci-tutorial-sidecar"
     - Set the container group restart policy to "never"
     - Test that the container app can be reached via "curl" like HTTP GET calls
     - Retrieve container log content
     - Delete the container group resource
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/aci-java-create-container-groups.git

    cd aci-java-create-container-groups

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.