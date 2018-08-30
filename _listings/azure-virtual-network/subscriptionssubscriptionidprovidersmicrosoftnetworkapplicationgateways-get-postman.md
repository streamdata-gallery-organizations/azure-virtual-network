{
  "info": {
    "name": "Azure Virtual Network API Application Gateways List All",
    "_postman_id": "a1ab0a64-e9e3-4bf9-b2ae-23aea5980201",
    "description": "Gets all the application gateways in a subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "application gateways",
      "item": [
        {
          "id": "8dee8a5e-9d44-43d5-88b5-9d2bd16a0579",
          "name": "ApplicationGateways_ListAll",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/Microsoft.Network/applicationGateways"
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
            "description": "Gets all the application gateways in a subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ad9b848-031f-48de-9d3f-c0b9a0744587"
            }
          ]
        }
      ]
    }
  ]
}