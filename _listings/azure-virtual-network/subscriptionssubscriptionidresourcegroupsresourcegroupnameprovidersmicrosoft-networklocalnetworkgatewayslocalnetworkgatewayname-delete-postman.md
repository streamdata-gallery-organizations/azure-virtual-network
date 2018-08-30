{
  "info": {
    "name": "Azure Virtual Network API Local Network Gateways Delete",
    "_postman_id": "7e43fc91-4448-42e4-8716-529fae68731f",
    "description": "Deletes the specified local network gateway.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "local network gateways",
      "item": [
        {
          "id": "3f7d301b-d070-4ebe-95e9-3d56aa00eab7",
          "name": "LocalNetworkGateways_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified local network gateway"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d7d521c7-5a38-451d-b2f4-12626e46440e"
            }
          ]
        }
      ]
    }
  ]
}