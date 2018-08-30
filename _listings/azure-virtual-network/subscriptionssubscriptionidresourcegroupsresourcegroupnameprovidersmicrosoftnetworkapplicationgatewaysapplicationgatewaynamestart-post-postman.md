{
  "info": {
    "name": "Azure Virtual Network API Application Gateways Start",
    "_postman_id": "23b955bf-c6b6-4e18-951b-3b6e1d3dc43b",
    "description": "Starts the specified application gateway.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "application gateways",
      "item": [
        {
          "id": "4a3cdb0c-9c52-4b8c-9e46-6af20c7bc97b",
          "name": "ApplicationGateways_Start",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/applicationGateways/:applicationGatewayName/start"
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
            "description": "Starts the specified application gateway"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "824c3f6a-d3bb-4281-8e81-d6db955d3dfb"
            }
          ]
        }
      ]
    }
  ]
}