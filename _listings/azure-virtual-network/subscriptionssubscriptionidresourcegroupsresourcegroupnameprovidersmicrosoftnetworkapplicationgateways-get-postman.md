{
  "info": {
    "name": "Azure Virtual Network API Application Gateways List",
    "_postman_id": "b19e2e09-899c-4de6-8f3f-9215b764ed8b",
    "description": "Lists all application gateways in a resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "application gateways",
      "item": [
        {
          "id": "d6c5b1c0-74d7-4e89-982d-eb2a460ef4b4",
          "name": "ApplicationGateways_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/applicationGateways"
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
            "description": "Lists all application gateways in a resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3068a9d8-85c9-4de7-824b-e1751f8f4d45"
            }
          ]
        }
      ]
    }
  ]
}