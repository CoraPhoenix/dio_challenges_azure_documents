# dio_challenges_azure_documents
Project made during DIO's "Microsoft Azure AI Fundamentals" Bootcamp, under the section "Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados"

Reference links:

- [Explore an Azure AI Search index (UI)](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

## Followed step-by-step

1. Create an "Azure AI Search" resource

![marketplace](img/print_1.png)

2. Fill in the necessary info, selecting pricing tier as "Basic", then click on "Review + create"

![creation_info](img/print_2.png)

3. After finished validation, click on "Create"

![review](img/print_3.png)

4. Wait for the deployment
5. After successfully deploying the created resource, create a new "Azure AI services" resource

![marketplace](img/print_4.png)

6. Fill in the necessary info, then click on "Review + create"

![creation_info](img/print_5.png)

7. After finished validation, click on "Create"

![review](img/print_6.png)

8. Wait for the deployment
9. After successfully deploying the created resource, go back to Azure Portal then click on "Storage accounts"

![storage account](img/print_7.png)

10. Click on "Create"
11. While filling in the required fields, give a unique storage account name, select "Standard" as Performance and select "Locally-redundant storage (LRS)" as Redundancy
12. Click on "Review", then click on "Create"

![storage acc creation](img/print_8.png)
![storage acc review](img/print_9.png)

13. Wait for the deployment
14. After finished deployment, click "Go to resource"

![successful storage deploy](img/print_10.png)

15. Go to "Settings" then "Configuration"

![storage config](img/print_11.png)

16. Toggle the option "Allow Blob anonymous access" to "Enabled" then click on "Save"
17. Go to "Data storage" then "Containers"

![storage containers](img/print_12.png)

18. Click on "Container" then fill in the appropriate fields, selecting the proper anonymous access level

![storage container creation](img/print_13.png)

19. Click on "Create"
20. Open the container then click on "Upload"

![storage container](img/print_14.png)

21. Upload the files downloaded from [zipped coffee reviews link](https://aka.ms/mslearn-coffee-reviews). Note it's necessary to unzip them first

![storage container upload](img/print_15.png)

22. Go to your Azure AI search resource then click on "Import data"

![import data](img/print_16.png)

23. Connect your uploaded data to the service, filling in the necessary configuration steps then clicking on "Submit"

![select data source](img/print_17.png)
![connect ai services](img/print_18.png)
![add skillset](img/print_19.png)
![select cognitive skills](img/print_20.png)
![enrichments](img/print_21.png)
![add target index](img/print_22.png)
![create indexer](img/print_23.png)

24. Return to Azure AI Search home page then go to "Search explorer"
25. Select the index and make a search

![search example 1](img/print_24.png)
![search example 2](img/print_25.png)

**Noted points:** This solution can be put inside an application
