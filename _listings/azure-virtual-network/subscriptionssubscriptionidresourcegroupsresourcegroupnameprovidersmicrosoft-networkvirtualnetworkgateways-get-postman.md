{
  "info": {
    "name": "Azure Virtual Network API Virtual Network Gateways List",
    "_postman_id": "a6059805-3402-4ea9-9e82-8a4dd76dde83",
    "description": "Gets all virtual network gateways by resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "virtual network gateways",
      "item": [
        {
          "id": "7b6f8f1e-22d0-4f05-9cb8-f0acadc37fe9",
          "name": "VirtualNetworkGateways_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/virtualNetworkGateways"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets all virtual network gateways by resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "08c0e329-4d0f-4a6c-b249-c42402d660fa"
            }
          ]
        }
      ]
    }
  ]
}