{
  "info": {
    "name": "Azure Virtual Network API Application Gateways Delete",
    "_postman_id": "be4f137f-0a2e-4a36-b55c-531d908052b1",
    "description": "Deletes the specified application gateway.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "application gateways",
      "item": [
        {
          "id": "62c9b28e-5aeb-4ec7-b06f-d6cf82e7439e",
          "name": "ApplicationGateways_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified application gateway"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aaac802f-0b21-490a-99c1-e040afbd23f5"
            }
          ]
        }
      ]
    }
  ]
}