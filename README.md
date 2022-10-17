# Implementing Azure Cosmos DB Change Feed

Change feed in Azure Cosmos DB is a persistent record of changes to a container in the order they occur. Change feed support in Azure Cosmos DB works by listening to an Azure Cosmos DB container for any changes. It then outputs the sorted list of documents that were changed in the order in which they were modified. The persisted changes can be processed asynchronously and incrementally, and the output can be distributed across one or more consumers for parallel processing.

The objective of this lab is to provide participants required skills for implementing  Azure Cosmos DB. The intended audience for the lab is architects and developers who design, build, and troubleshoot Cosmos DB solutions that meet business and technical requirements.