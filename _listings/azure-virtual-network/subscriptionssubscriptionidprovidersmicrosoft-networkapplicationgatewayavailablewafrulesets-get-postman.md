{
  "info": {
    "name": "Azure Virtual Network API Application Gateways List Available Waf Rule Sets",
    "_postman_id": "2e441295-51ce-4a96-85b4-121804494fc5",
    "description": "Lists all available web application firewall rule sets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "application gateways",
      "item": [
        {
          "id": "92b91bf0-2920-429e-af0d-84d133edacf9",
          "name": "ApplicationGateways_ListAvailableWafRuleSets",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/Microsoft.Network/applicationGatewayAvailableWafRuleSets"
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
            "description": "Lists all available web application firewall rule sets"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df460f1e-28b1-430b-a5d3-eecd460db649"
            }
          ]
        }
      ]
    }
  ]
}