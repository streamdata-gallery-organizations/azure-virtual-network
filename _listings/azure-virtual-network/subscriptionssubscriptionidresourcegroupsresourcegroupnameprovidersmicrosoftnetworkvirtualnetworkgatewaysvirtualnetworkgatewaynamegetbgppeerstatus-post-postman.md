{
  "info": {
    "name": "Azure Virtual Network API Virtual Network Gateways Get Bgp Peer Status",
    "_postman_id": "4108b8ae-70f6-410a-982b-6663874e04e8",
    "description": "The GetBgpPeerStatus operation retrieves the status of all BGP peers.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "virtual network gateways",
      "item": [
        {
          "id": "22dd2ce3-66e6-49a4-8d39-314a6bd61691",
          "name": "VirtualNetworkGateways_GetBgpPeerStatus",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/virtualNetworkGateways/:virtualNetworkGatewayName/getBgpPeerStatus"
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
            "description": "The GetBgpPeerStatus operation retrieves the status of all BGP peers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b0987c9-a916-493a-9416-537f6b50c8a6"
            }
          ]
        }
      ]
    }
  ]
}