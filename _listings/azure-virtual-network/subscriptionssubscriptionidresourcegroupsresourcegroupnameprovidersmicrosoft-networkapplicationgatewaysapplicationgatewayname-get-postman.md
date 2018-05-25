{
  "info": {
    "name": "Azure Virtual Network API Application Gateways Get",
    "_postman_id": "f9ec8e62-14f3-440d-bc2a-709cd12d880a",
    "description": "Gets the specified application gateway.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "application gateways",
      "item": [
        {
          "id": "365b975c-7fbb-44b9-a322-492cb2ea61fa",
          "name": "ApplicationGateways_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/applicationGateways/:applicationGatewayName"
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the specified application gateway"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be647cde-1995-4500-8536-032b73d7de07"
            }
          ]
        }
      ]
    }
  ]
}