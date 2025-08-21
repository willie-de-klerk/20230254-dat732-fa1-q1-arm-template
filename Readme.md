## DAT732 Formative Assignment 1 Question 1 C
An template that can be used to provision an SQL Database Managed Instance, with basic firewall and networking rules. 

## ⚙️ Utilizing the template using Powerhsell and the Azure CLI

```
$resourcegroup="user-hvcmgbbewgdj"
$location="eastus"
$managedInstanceName="williesqlmi"
$administratorLogin="willie"
$administratorLoginPassword="t#7y43I052$Q2541^!D!"
$virtualNetworkName="williesqlmivnet"
$vCores="4"
$storageSizeInGB="32"
az deployment group create --resource-group $resourcegroup --template-file 20230254_arm_template.json --parameters location=$location managedInstanceName=$managedInstanceName administratorLogin=$administratorLogin administratorLoginPassword=$administratorLoginPassword virtualNetworkName=$virtualNetworkName vCores=$vCores storageSizeInGB=$storageSizeInGB
```

## ✍️ willie@williedeklerk.com

Student - [CTU Training Solutions](https://www.linkedin.com/company/ctu-training-solutions-pty-ltd/) (2025)

Student Number: `20230254`