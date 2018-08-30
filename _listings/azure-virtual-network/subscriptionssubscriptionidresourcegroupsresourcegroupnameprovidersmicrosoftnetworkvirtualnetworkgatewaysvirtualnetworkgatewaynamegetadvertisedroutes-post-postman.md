{
  "info": {
    "name": "Azure Virtual Network API Virtual Network Gateways Get Advertised Routes",
    "_postman_id": "651f764e-1a76-4f27-a9b2-0f1cd5364bf1",
    "description": "This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "virtual network gateways",
      "item": [
        {
          "id": "d4b75d91-8eda-4ad5-b7a7-79fe82e1248e",
          "name": "VirtualNetworkGateways_GetAdvertisedRoutes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/virtualNetworkGateways/:virtualNetworkGatewayName/getAdvertisedRoutes"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "peer",
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
            "description": "This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "815fd5be-cf65-4cfe-9d82-6a85a800a89d"
            }
          ]
        }
      ]
    }
  ]
}