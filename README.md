# Azure-Stream-Stock-Data
Azure(Event Hubs, Stream Analytics Jobs) &amp; Python 


Python code for sending streaming data from Yahoo Finance API to Azure Event Hubs

Prerequisites(in Azure):
  - Resource Group
  - Storage account in that resource group
  - Container in storage account (for storing the data)
  - Creation of Event Hubs
  - Creation of Stream Analytics Job (connects the Event Hubs(input) and the Storage Account(output) through a query)

