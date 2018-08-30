{
  "info": {
    "name": "Azure Virtual Network API Application Gateways Stop",
    "_postman_id": "4f7a14ee-fdbf-488e-b171-c5d51c780ac2",
    "description": "Stops the specified application gateway in a resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "application gateways",
      "item": [
        {
          "id": "e41a74f8-ec13-47bc-957d-ea20798bda6a",
          "name": "ApplicationGateways_Stop",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/applicationGateways/:applicationGatewayName/stop"
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
                  "id": "applicationGatewayName",
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Stops the specified application gateway in a resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a2e33ed-f7b4-468a-9a7b-969faff21bb6"
            }
          ]
        }
      ]
    }
  ]
}