provider "azurerm" {
    version = "=2.0.0"
    features {}
}

resource "azurerm_resource_group" "terraform-rg" {
    name     = "terraform-basic"
    location = "eastus"
    tags = {
        env = "dev"
    }
    
}