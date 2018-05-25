{
  "info": {
    "name": "Azure Virtual Network API Local Network Gateways Get",
    "_postman_id": "014fe8d8-53a4-4a66-a679-26dbc8aa089c",
    "description": "Gets the specified local network gateway in a resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "local network gateways",
      "item": [
        {
          "id": "3da6a497-aaa4-43e9-a7c7-b098c9503d6b",
          "name": "LocalNetworkGateways_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/localNetworkGateways/:localNetworkGatewayName"
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
                  "id": "localNetworkGatewayName",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Gets the specified local network gateway in a resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f373918e-0a51-4fe3-b4c3-a1e6446e578c"
            }
          ]
        }
      ]
    }
  ]
}