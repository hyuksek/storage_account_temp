{
    "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentTemplate.json#",
    "contentVersion": "1.0.0.0",
    "parameters": {},
    "functions": [],
    "variables": {},
    "resources": [

     {
        "name": "stassignment5",
        "type": "Microsoft.Storage/storageAccounts",
        "apiVersion": "2021-04-01",
        "tags": {
            "displayName": "stassignment5"
        },
        "location": "canadacentral",
        "kind": "StorageV2",
        "sku": {
            "name": "Premium_LRS",
            "tier": "Premium"
        }
     }



    ],
    "outputs": {}

}





