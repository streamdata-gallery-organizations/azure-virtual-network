{
  "info": {
    "name": "Azure Virtual Network API Virtual Network Gateways Reset",
    "_postman_id": "f1bb6142-fa8b-4026-9e58-35e37c74bb3b",
    "description": "Resets the primary of the virtual network gateway in the specified resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "virtual network gateways",
      "item": [
        {
          "id": "4af5dd49-ff86-49c4-8217-7cdf5e6c6433",
          "name": "VirtualNetworkGateways_Reset",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/virtualNetworkGateways/:virtualNetworkGatewayName/reset"
              ],
              "query": [
                {
                  "key": "gatewayVip",
                  "value": "%7B%7D",
                  "disabled": false
                },
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Resets the primary of the virtual network gateway in the specified resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "83cca31e-f6ea-4c08-af84-4e0181eda9fa"
            }
          ]
        }
      ]
    }
  ]
}