# Azure Mini Project: Data Factory
![Design Blocks](https://images.unsplash.com/photo-1507823690283-48b0929e727b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=800)
Image by: Quinten de Graaf


## Table of contents
* [What is this?](#what-is-this)
* [Business problem](business-problem)
* [Goal](#goal)


## What is this?
In this mini-project, I have engineered and deployed an End-to-End Azure Extract Load Transformation (ELT) solution. I have done this using Azure Data Factory (ADF) and Mapping Dataflows to perform ELT process using Azure Blob storage and Azure SQL DB. I have also used Azure DevOps repositories to perform source control over ADF pipelines. Lastly, I have use Azure DevOps pipelines to deploy this project across multiple environments including Dev, Test, and Production.

This hands-on mini-project is designed to provide exposure to many of Microsoft’s transformative lines of business applications. The goal is to show an end-to-end solution, leveraging many of these technologies, but not necessarily doing work in every component possible. 

> __The lab architecture is below and includes:__

> * Azure Data Factory (ADF)
> * Azure Storage
> * Azure Data Factory Mapping Dataflows
> * Azure SQL Database
> * Azure Key vault
> * Azure DevOps

## Business problem:
Wide World Importers (WWI) imports products then resells them both to retailers and directly to the public. In an increasingly crowded market, they are always looking for ways to differentiate themselves and provide additional value to their customers.They are looking to pilot a data warehouse to provide additional information useful to their internal sales and marketing agents. They want to enable their agents to perform as-is and as-was analysis in order to price the items accurately and predict the product demand throughout the year.

To extend their physical presence WWI recently acquired Smart Food, a supermarket business who provides comprehensive nutritional information to customers so they can make healthy decisions. SmartFoods runs a loyalty program where customers accumulate points on their purchases. WWI CIO is hoping to use the loyalty program information and the food nutrients database of SmartFoods to provide customers with a HealthSmart portal. The portal will be showing aggregated information on customers' important food nutrients (carbs, saturated fats, etc.) to promote healthy shopping.

In this hands-on mini-project, I have built an end-to-end solution for data warehousing using modern data lake methodology.

## Goal:
The goal here is to demonstrate proficiency in creating and utilizing ELT pipelines utilizing MS AZURE technologies.

__Deliverables:__
> * (Optional) A document with screenshots of each step as performed according to this lab.

> 1. Why should one use Azure Key Vault when working in the Azure environment? What are the pros and cons? What are the alternatives?
> 2. How do you achieve loop functionality within a Azure Data Factory pipeline? Why would you need to use this functionality in a data pipeline?
> 3. What are expressions in Azure Data Factory? How are they helpful when designing a data pipeline? Please explain with an example.
> 4. What are the pros and cons of parametrizing a dataset’s activity in Azure Data Factory?
> 5. What are the different supported file formats and compression codecs in Azure Data Factory? When will you use a Parquet file over an ORC file? Why would you choose an AVRO file format over a Parquet file format.
_____