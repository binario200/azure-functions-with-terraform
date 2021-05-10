# Azure functions with Terraform
Configure and deploy an Azure function with Terraform

This Terraform solution the related resources to deploy an azure function app. 

Then provide the settings for the actual Azure function poiting to a external source control repository. 

It also instructs to azure to provision the Azure function with a systema assigned managed indentity. 

The actual azure function will be provided in another repository, in this one we focus in the Terraform configurations to provision all the azure resources required for the function app. 

# Prerequesites

In order to be able to play with this code you will need:

- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli) 2.4+ You must be [logged in](https://docs.microsoft.com/en-us/cli/azure/authenticate-azure-cli#sign-in-interactively) to the CLI 
- [Terraform](https://www.terraform.io/downloads.html) to manage infrastructure in the cloud
- Azure account. You can start for [free](https://azure.microsoft.com/en-us/free/s)

