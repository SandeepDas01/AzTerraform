# Terraform Script to Create Azure Virtual Network (VNet) and Azure Cognitive Search Service

This Terraform script creates an Azure Virtual Network (VNet) with a subnet and an Azure Cognitive Search service (AI Search) in a specified Azure resource group.

## Maintainer
- **Maintainer**: Sandeep Das

## Prerequisites

Before using this script, you will need to have the following:

1. **Terraform**: Install Terraform by following the official documentation [here](https://www.terraform.io/downloads).
2. **Azure Account**: Ensure you have an Azure account and that your credentials are properly set up for Terraform to interact with Azure.
3. **Azure CLI (Optional)**: If you want to authenticate using the Azure CLI, you can install it [here](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli).

## Azure Authentication

To authenticate Terraform to Azure, you can either:

- Use Azure CLI authentication by running `az login` in your terminal.
- Use a Service Principal with a client secret or certificate.

For the Azure CLI authentication, ensure you are logged in using:

```bash
az login
