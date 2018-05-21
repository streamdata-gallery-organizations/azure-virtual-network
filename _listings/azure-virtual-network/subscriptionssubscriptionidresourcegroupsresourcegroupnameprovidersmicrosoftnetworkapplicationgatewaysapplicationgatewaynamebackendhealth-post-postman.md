{
  "info": {
    "name": "Azure Virtual Network API Application Gateways Backend Health",
    "_postman_id": "5ab35f7a-3843-4a4a-b34b-d155dc15cda4",
    "description": "Gets the backend health of the specified application gateway in a resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "application gateways",
      "item": [
        {
          "id": "c055b225-d621-4f5e-ad22-935d0a5a68dd",
          "name": "ApplicationGateways_BackendHealth",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/applicationGateways/:applicationGatewayName/backendhealth"
              ],
              "query": [
                {
                  "key": "$expand",
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
            "description": "Gets the backend health of the specified application gateway in a resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10073a16-3cc9-41b4-b415-27f03c806a72"
            }
          ]
        }
      ]
    }
  ]
}