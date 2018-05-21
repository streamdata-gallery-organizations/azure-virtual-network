{
  "info": {
    "name": "Azure Virtual Network API Virtual Network Gateways Get",
    "_postman_id": "d8dd838c-9ca8-4219-9a03-c17c8d28f361",
    "description": "Gets the specified virtual network gateway by resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "virtual network gateways",
      "item": [
        {
          "id": "9a5fb5e7-9856-403d-8ad2-9ef7695d791c",
          "name": "VirtualNetworkGateways_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/virtualNetworkGateways/:virtualNetworkGatewayName"
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
                  "id": "virtualNetworkGatewayName",
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
            "description": "Gets the specified virtual network gateway by resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4514c6d8-135a-4b91-9dff-16099963bb29"
            }
          ]
        }
      ]
    }
  ]
}