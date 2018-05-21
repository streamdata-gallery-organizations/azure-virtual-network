{
  "info": {
    "name": "Azure Virtual Network API Virtual Network Gateways Get Learned Routes",
    "_postman_id": "733e73b8-ed74-4e57-a42c-b3d3390d5b14",
    "description": "This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "virtual network gateways",
      "item": [
        {
          "id": "c9973724-9fc7-4ba6-abd2-9dfd20886ecd",
          "name": "VirtualNetworkGateways_GetLearnedRoutes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/virtualNetworkGateways/:virtualNetworkGatewayName/getLearnedRoutes"
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5029fc2f-ce8c-407b-ae30-5762b4e0919d"
            }
          ]
        }
      ]
    }
  ]
}