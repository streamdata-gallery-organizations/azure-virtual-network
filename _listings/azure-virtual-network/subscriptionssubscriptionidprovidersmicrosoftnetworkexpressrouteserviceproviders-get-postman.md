{
  "info": {
    "name": "Azure Virtual Network API Express Route Service Providers List",
    "_postman_id": "0fdce4c2-3137-48fa-aff2-9b2254473f6d",
    "description": "Gets all the available express route service providers.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "express route service providers",
      "item": [
        {
          "id": "4f83c9d2-c459-4cc4-96b2-db68b5402c2b",
          "name": "ExpressRouteServiceProviders_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/Microsoft.Network/expressRouteServiceProviders"
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
            "description": "Gets all the available express route service providers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dac92c1c-c984-4c70-9b5a-21c46cb73930"
            }
          ]
        }
      ]
    }
  ]
}