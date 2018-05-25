---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 0
info:
  title: Azure Virtual Network API Application Gateways List
  description: Lists all application gateways in a resource group.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways/{applicationGatewayName}
  : delete:
      summary: Application Gateways Delete
      description: Deletes the specified application gateway.
      operationId: ApplicationGateways_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewayname-delete
      parameters:
      - in: path
        name: applicationGatewayName
        description: The name of the application gateway
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Application Gateways
    get:
      summary: Application Gateways Get
      description: Gets the specified application gateway.
      operationId: ApplicationGateways_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewayname-get
      parameters:
      - in: path
        name: applicationGatewayName
        description: The name of the application gateway
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Application Gateways
    put:
      summary: Application Gateways Create Or Update
      description: Creates or updates the specified application gateway.
      operationId: ApplicationGateways_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewayname-put
      parameters:
      - in: path
        name: applicationGatewayName
        description: The name of the application gateway
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update application gateway
          operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Application Gateways
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways:
    get:
      summary: Application Gateways List
      description: Lists all application gateways in a resource group.
      operationId: ApplicationGateways_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgateways-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Application Gateways
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---