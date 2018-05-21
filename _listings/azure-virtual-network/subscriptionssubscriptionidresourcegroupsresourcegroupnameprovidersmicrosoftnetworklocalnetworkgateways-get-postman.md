{
  "info": {
    "name": "Azure Virtual Network API Local Network Gateways List",
    "_postman_id": "721863b7-33a5-42c5-a31f-2abae46daad3",
    "description": "Gets all the local network gateways in a resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "local network gateways",
      "item": [
        {
          "id": "51f92a95-0982-4896-93a6-48e75c50e69a",
          "name": "LocalNetworkGateways_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/localNetworkGateways"
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
            "description": "Gets all the local network gateways in a resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bae8ca77-e435-44a3-aca0-c15d1a4a79a8"
            }
          ]
        }
      ]
    }
  ]
}