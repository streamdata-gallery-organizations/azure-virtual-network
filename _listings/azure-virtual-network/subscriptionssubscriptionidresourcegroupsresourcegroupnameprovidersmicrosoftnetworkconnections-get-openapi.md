---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 0
info:
  title: Azure Virtual Network API Virtual Network Gateway Connections List
  description: The List VirtualNetworkGatewayConnections operation retrieves all the
    virtual network gateways connections created.
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewayname-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewayname-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewayname-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgateways-get
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
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/applicationGateways:
    get:
      summary: Application Gateways List All
      description: Gets all the application gateways in a subscription.
      operationId: ApplicationGateways_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworkapplicationgateways-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Application Gateways
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways/{applicationGatewayName}/start
  : post:
      summary: Application Gateways Start
      description: Starts the specified application gateway.
      operationId: ApplicationGateways_Start
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewaynamestart-post
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways/{applicationGatewayName}/stop
  : post:
      summary: Application Gateways Stop
      description: Stops the specified application gateway in a resource group.
      operationId: ApplicationGateways_Stop
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewaynamestop-post
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways/{applicationGatewayName}/backendhealth
  : post:
      summary: Application Gateways Backend Health
      description: Gets the backend health of the specified application gateway in
        a resource group.
      operationId: ApplicationGateways_BackendHealth
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewaynamebackendhealth-post
      parameters:
      - in: query
        name: $expand
        description: Expands BackendAddressPool and BackendHttpSettings referenced
          in backend health
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
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/applicationGatewayAvailableWafRuleSets:
    get:
      summary: Application Gateways List Available Waf Rule Sets
      description: Lists all available web application firewall rule sets.
      operationId: ApplicationGateways_ListAvailableWafRuleSets
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworkapplicationgatewayavailablewafrulesets-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Application Gateways
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/locations/{location}/CheckDnsNameAvailability:
    get:
      summary: Check Dns Name Availability
      description: Checks whether a domain name in the cloudapp.net zone is available
        for use.
      operationId: CheckDnsNameAvailability
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworklocationslocationcheckdnsnameavailability-get
      parameters:
      - in: query
        name: domainNameLabel
        description: The domain name to be verified
      - in: path
        name: location
        description: The location of the domain name
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Dns Name Availability
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/authorizations/{authorizationName}
  : delete:
      summary: Express Route Circuit Authorizations Delete
      description: Deletes the specified authorization from the specified express
        route circuit.
      operationId: ExpressRouteCircuitAuthorizations_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnameauthorizationsauthorizationname-delete
      parameters:
      - in: path
        name: authorizationName
        description: The name of the authorization
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuit Authorizations
    get:
      summary: Express Route Circuit Authorizations Get
      description: Gets the specified authorization from the specified express route
        circuit.
      operationId: ExpressRouteCircuitAuthorizations_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnameauthorizationsauthorizationname-get
      parameters:
      - in: path
        name: authorizationName
        description: The name of the authorization
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuit Authorizations
    put:
      summary: Express Route Circuit Authorizations Create Or Update
      description: Creates or updates an authorization in the specified express route
        circuit.
      operationId: ExpressRouteCircuitAuthorizations_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnameauthorizationsauthorizationname-put
      parameters:
      - in: path
        name: authorizationName
        description: The name of the authorization
      - in: body
        name: authorizationParameters
        description: Parameters supplied to the create or update express route circuit
          authorization operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuit Authorizations
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/authorizations
  : get:
      summary: Express Route Circuit Authorizations List
      description: Gets all authorizations in an express route circuit.
      operationId: ExpressRouteCircuitAuthorizations_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnameauthorizations-get
      parameters:
      - in: path
        name: circuitName
        description: The name of the circuit
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuit Authorizations
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}
  : delete:
      summary: Express Route Circuit Peerings Delete
      description: Deletes the specified peering from the specified express route
        circuit.
      operationId: ExpressRouteCircuitPeerings_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringname-delete
      parameters:
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: query
        name: No Name
      - in: path
        name: peeringName
        description: The name of the peering
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuit Peerings
    get:
      summary: Express Route Circuit Peerings Get
      description: Gets the specified authorization from the specified express route
        circuit.
      operationId: ExpressRouteCircuitPeerings_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringname-get
      parameters:
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: query
        name: No Name
      - in: path
        name: peeringName
        description: The name of the peering
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuit Peerings
    put:
      summary: Express Route Circuit Peerings Create Or Update
      description: Creates or updates a peering in the specified express route circuits.
      operationId: ExpressRouteCircuitPeerings_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringname-put
      parameters:
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: query
        name: No Name
      - in: path
        name: peeringName
        description: The name of the peering
      - in: body
        name: peeringParameters
        description: Parameters supplied to the create or update express route circuit
          peering operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuit Peerings
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings
  : get:
      summary: Express Route Circuit Peerings List
      description: Gets all peerings in a specified express route circuit.
      operationId: ExpressRouteCircuitPeerings_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeerings-get
      parameters:
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuit Peerings
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}
  : delete:
      summary: Express Route Circuits Delete
      description: Deletes the specified express route circuit.
      operationId: ExpressRouteCircuits_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitname-delete
      parameters:
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuits
    get:
      summary: Express Route Circuits Get
      description: Gets information about the specified express route circuit.
      operationId: ExpressRouteCircuits_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitname-get
      parameters:
      - in: path
        name: circuitName
        description: The name of express route circuit
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuits
    put:
      summary: Express Route Circuits Create Or Update
      description: Creates or updates an express route circuit.
      operationId: ExpressRouteCircuits_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitname-put
      parameters:
      - in: path
        name: circuitName
        description: The name of the circuit
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update express route circuit
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
      - Express Route Circuits
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}/arpTables/{devicePath}
  : post:
      summary: Express Route Circuits List Arp Table
      description: Gets the currently advertised ARP table associated with the express
        route circuit in a resource group.
      operationId: ExpressRouteCircuits_ListArpTable
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringnamearptablesdevicepath-post
      parameters:
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: path
        name: devicePath
        description: The path of the device
      - in: query
        name: No Name
      - in: path
        name: peeringName
        description: The name of the peering
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuits
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}/routeTables/{devicePath}
  : post:
      summary: Express Route Circuits List Routes Table
      description: Gets the currently advertised routes table associated with the
        express route circuit in a resource group.
      operationId: ExpressRouteCircuits_ListRoutesTable
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringnameroutetablesdevicepath-post
      parameters:
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: path
        name: devicePath
        description: The path of the device
      - in: query
        name: No Name
      - in: path
        name: peeringName
        description: The name of the peering
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuits
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}/routeTablesSummary/{devicePath}
  : post:
      summary: Express Route Circuits List Routes Table Summary
      description: Gets the currently advertised routes table summary associated with
        the express route circuit in a resource group.
      operationId: ExpressRouteCircuits_ListRoutesTableSummary
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringnameroutetablessummarydevicepath-post
      parameters:
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: path
        name: devicePath
        description: The path of the device
      - in: query
        name: No Name
      - in: path
        name: peeringName
        description: The name of the peering
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuits
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/stats
  : get:
      summary: Express Route Circuits Get Stats
      description: Gets all the stats from an express route circuit in a resource
        group.
      operationId: ExpressRouteCircuits_GetStats
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamestats-get
      parameters:
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuits
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}/stats
  : get:
      summary: Express Route Circuits Get Peering Stats
      description: Gets all stats from an express route circuit in a resource group.
      operationId: ExpressRouteCircuits_GetPeeringStats
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringnamestats-get
      parameters:
      - in: path
        name: circuitName
        description: The name of the express route circuit
      - in: query
        name: No Name
      - in: path
        name: peeringName
        description: The name of the peering
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuits
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits:
    get:
      summary: Express Route Circuits List
      description: Gets all the express route circuits in a resource group.
      operationId: ExpressRouteCircuits_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuits-get
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
      - Express Route Circuits
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/expressRouteCircuits:
    get:
      summary: Express Route Circuits List All
      description: Gets all the express route circuits in a subscription.
      operationId: ExpressRouteCircuits_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworkexpressroutecircuits-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Express Route Circuits
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/expressRouteServiceProviders:
    get:
      summary: Express Route Service Providers List
      description: Gets all the available express route service providers.
      operationId: ExpressRouteServiceProviders_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworkexpressrouteserviceproviders-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Express Route Service Providers
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers/{loadBalancerName}:
    delete:
      summary: Load Balancers Delete
      description: Deletes the specified load balancer.
      operationId: LoadBalancers_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkloadbalancersloadbalancername-delete
      parameters:
      - in: path
        name: loadBalancerName
        description: The name of the load balancer
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
    get:
      summary: Load Balancers Get
      description: Gets the specified load balancer.
      operationId: LoadBalancers_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkloadbalancersloadbalancername-get
      parameters:
      - in: query
        name: $expand
        description: Expands referenced resources
      - in: path
        name: loadBalancerName
        description: The name of the load balancer
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
    put:
      summary: Load Balancers Create Or Update
      description: Creates or updates a load balancer.
      operationId: LoadBalancers_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkloadbalancersloadbalancername-put
      parameters:
      - in: path
        name: loadBalancerName
        description: The name of the load balancer
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update load balancer operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/loadBalancers:
    get:
      summary: Load Balancers List All
      description: Gets all the load balancers in a subscription.
      operationId: LoadBalancers_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworkloadbalancers-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Load Balancers All
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers:
    get:
      summary: Load Balancers List
      description: Gets all the load balancers in a resource group.
      operationId: LoadBalancers_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkloadbalancers-get
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
      - Load Balancers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkInterfaces/{networkInterfaceName}
  : delete:
      summary: Network Interfaces Delete
      description: Deletes the specified network interface.
      operationId: NetworkInterfaces_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacename-delete
      parameters:
      - in: path
        name: networkInterfaceName
        description: The name of the network interface
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Interfaces
    get:
      summary: Network Interfaces Get
      description: Gets information about the specified network interface.
      operationId: NetworkInterfaces_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacename-get
      parameters:
      - in: query
        name: $expand
        description: Expands referenced resources
      - in: path
        name: networkInterfaceName
        description: The name of the network interface
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Interfaces
    put:
      summary: Network Interfaces Create Or Update
      description: Creates or updates a network interface.
      operationId: NetworkInterfaces_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacename-put
      parameters:
      - in: path
        name: networkInterfaceName
        description: The name of the network interface
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update network interface
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
      - Network Interfaces
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/networkInterfaces:
    get:
      summary: Network Interfaces List All
      description: Gets all network interfaces in a subscription.
      operationId: NetworkInterfaces_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworknetworkinterfaces-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Network Interfaces
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkInterfaces:
    get:
      summary: Network Interfaces List
      description: Gets all network interfaces in a resource group.
      operationId: NetworkInterfaces_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfaces-get
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
      - Network Interfaces
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkInterfaces/{networkInterfaceName}/effectiveRouteTable
  : post:
      summary: Network Interfaces Get Effective Route Table
      description: Gets all route tables applied to a network interface.
      operationId: NetworkInterfaces_GetEffectiveRouteTable
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacenameeffectiveroutetable-post
      parameters:
      - in: path
        name: networkInterfaceName
        description: The name of the network interface
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Interfaces
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkInterfaces/{networkInterfaceName}/effectiveNetworkSecurityGroups
  : post:
      summary: Network Interfaces List Effective Network Security Groups
      description: Gets all network security groups applied to a network interface.
      operationId: NetworkInterfaces_ListEffectiveNetworkSecurityGroups
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacenameeffectivenetworksecuritygroups-post
      parameters:
      - in: path
        name: networkInterfaceName
        description: The name of the network interface
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Interfaces
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}
  : delete:
      summary: Network Security Groups Delete
      description: Deletes the specified network security group.
      operationId: NetworkSecurityGroups_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupname-delete
      parameters:
      - in: path
        name: networkSecurityGroupName
        description: The name of the network security group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Security Groups
    get:
      summary: Network Security Groups Get
      description: Gets the specified network security group.
      operationId: NetworkSecurityGroups_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupname-get
      parameters:
      - in: query
        name: $expand
        description: Expands referenced resources
      - in: path
        name: networkSecurityGroupName
        description: The name of the network security group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Security Groups
    put:
      summary: Network Security Groups Create Or Update
      description: Creates or updates a network security group in the specified resource
        group.
      operationId: NetworkSecurityGroups_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupname-put
      parameters:
      - in: path
        name: networkSecurityGroupName
        description: The name of the network security group
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update network security
          group operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Security Groups
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/networkSecurityGroups:
    get:
      summary: Network Security Groups List All
      description: Gets all network security groups in a subscription.
      operationId: NetworkSecurityGroups_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworknetworksecuritygroups-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Network Security Groups
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups:
    get:
      summary: Network Security Groups List
      description: Gets all network security groups in a resource group.
      operationId: NetworkSecurityGroups_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroups-get
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
      - Network Security Groups
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules/{securityRuleName}
  : delete:
      summary: Security Rules Delete
      description: Deletes the specified network security rule.
      operationId: SecurityRules_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-delete
      parameters:
      - in: path
        name: networkSecurityGroupName
        description: The name of the network security group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: securityRuleName
        description: The name of the security rule
      responses:
        200:
          description: OK
      tags:
      - Security Rules
    get:
      summary: Security Rules Get
      description: Get the specified network security rule.
      operationId: SecurityRules_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-get
      parameters:
      - in: path
        name: networkSecurityGroupName
        description: The name of the network security group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: securityRuleName
        description: The name of the security rule
      responses:
        200:
          description: OK
      tags:
      - Security Rules
    put:
      summary: Security Rules Create Or Update
      description: Creates or updates a security rule in the specified network security
        group.
      operationId: SecurityRules_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-put
      parameters:
      - in: path
        name: networkSecurityGroupName
        description: The name of the network security group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: securityRuleName
        description: The name of the security rule
      - in: body
        name: securityRuleParameters
        description: Parameters supplied to the create or update network security
          rule operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Security Rules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules
  : get:
      summary: Security Rules List
      description: Gets all security rules in a network security group.
      operationId: SecurityRules_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupnamesecurityrules-get
      parameters:
      - in: path
        name: networkSecurityGroupName
        description: The name of the network security group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Security Rules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}
  : put:
      summary: Network Watchers Create Or Update
      description: Creates or updates a network watcher in the specified resource
        group.
      operationId: NetworkWatchers_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchername-put
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters that define the network watcher resource
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
    get:
      summary: Network Watchers Get
      description: Gets the specified network watcher by resource group.
      operationId: NetworkWatchers_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchername-get
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
    delete:
      summary: Network Watchers Delete
      description: Deletes the specified network watcher resource.
      operationId: NetworkWatchers_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchername-delete
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers:
    get:
      summary: Network Watchers List
      description: Gets all network watchers by resource group.
      operationId: NetworkWatchers_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchers-get
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
      - Network Watchers
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/networkWatchers:
    get:
      summary: Network Watchers List All
      description: Gets all network watchers by subscription.
      operationId: NetworkWatchers_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworknetworkwatchers-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/topology
  : post:
      summary: Network Watchers Get Topology
      description: Gets the current network topology by resource group.
      operationId: NetworkWatchers_GetTopology
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernametopology-post
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters that define the representation of topology
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/ipFlowVerify
  : post:
      summary: Network Watchers Verify IPFlow
      description: Verify IP flow from the specified VM to a location given the currently
        configured NSG rules.
      operationId: NetworkWatchers_VerifyIPFlow
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernameipflowverify-post
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters that define the IP flow to be verified
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/nextHop
  : post:
      summary: Network Watchers Get Next Hop
      description: Gets the next hop from the specified VM.
      operationId: NetworkWatchers_GetNextHop
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamenexthop-post
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters that define the source and destination endpoint
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/securityGroupView
  : post:
      summary: Network Watchers Get VMSecurity Rules
      description: Gets the configured and effective security group rules on the specified
        VM.
      operationId: NetworkWatchers_GetVMSecurityRules
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamesecuritygroupview-post
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters that define the VM to check security groups for
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/packetCaptures/{packetCaptureName}
  : put:
      summary: Packet Captures Create
      description: Create and start a packet capture on the specified VM.
      operationId: PacketCaptures_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcapturespacketcapturename-put
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher
      - in: query
        name: No Name
      - in: path
        name: packetCaptureName
        description: The name of the packet capture session
      - in: body
        name: parameters
        description: Parameters that define the create packet capture operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Packet Captures
    get:
      summary: Packet Captures Get
      description: Gets a packet capture session by name.
      operationId: PacketCaptures_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcapturespacketcapturename-get
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher
      - in: query
        name: No Name
      - in: path
        name: packetCaptureName
        description: The name of the packet capture session
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Packet Captures
    delete:
      summary: Packet Captures Delete
      description: Deletes the specified packet capture session.
      operationId: PacketCaptures_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcapturespacketcapturename-delete
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher
      - in: query
        name: No Name
      - in: path
        name: packetCaptureName
        description: The name of the packet capture session
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Packet Captures
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/packetCaptures/{packetCaptureName}/stop
  : post:
      summary: Packet Captures Stop
      description: Stops a specified packet capture session.
      operationId: PacketCaptures_Stop
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcapturespacketcapturenamestop-post
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher
      - in: query
        name: No Name
      - in: path
        name: packetCaptureName
        description: The name of the packet capture session
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Packet Captures
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/packetCaptures/{packetCaptureName}/queryStatus
  : post:
      summary: Packet Captures Get Status
      description: Query the status of a running packet capture session.
      operationId: PacketCaptures_GetStatus
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcapturespacketcapturenamequerystatus-post
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the Network Watcher resource
      - in: query
        name: No Name
      - in: path
        name: packetCaptureName
        description: The name given to the packet capture session
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Packet Captures
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/packetCaptures
  : get:
      summary: Packet Captures List
      description: Lists all packet capture sessions within the specified resource
        group.
      operationId: PacketCaptures_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcaptures-get
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the Network Watcher resource
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Packet Captures
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/troubleshoot
  : post:
      summary: Network Watchers Get Troubleshooting
      description: Initiate troubleshooting on a specified resource
      operationId: NetworkWatchers_GetTroubleshooting
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernametroubleshoot-post
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher resource
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters that define the resource to troubleshoot
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/queryTroubleshootResult
  : post:
      summary: Network Watchers Get Troubleshooting Result
      description: Get the last completed troubleshooting result on a specified resource
      operationId: NetworkWatchers_GetTroubleshootingResult
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamequerytroubleshootresult-post
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher resource
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters that define the resource to query the troubleshooting
          result
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/configureFlowLog
  : post:
      summary: Network Watchers Set Flow Log Configuration
      description: Configures flow log on a specified resource.
      operationId: NetworkWatchers_SetFlowLogConfiguration
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernameconfigureflowlog-post
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher resource
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters that define the configuration of flow log
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the network watcher resource group
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/queryFlowLogStatus
  : post:
      summary: Network Watchers Get Flow Log Status
      description: Queries status of flow log on a specified resource.
      operationId: NetworkWatchers_GetFlowLogStatus
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamequeryflowlogstatus-post
      parameters:
      - in: path
        name: networkWatcherName
        description: The name of the network watcher resource
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters that define a resource to query flow log status
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the network watcher resource group
      responses:
        200:
          description: OK
      tags:
      - Network Watchers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/publicIPAddresses/{publicIpAddressName}
  : delete:
      summary: Public IPAddresses Delete
      description: Deletes the specified public IP address.
      operationId: PublicIPAddresses_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkpublicipaddressespublicipaddressname-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: publicIpAddressName
        description: The name of the subnet
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Public IP Address
    get:
      summary: Public IPAddresses Get
      description: Gets the specified public IP address in a specified resource group.
      operationId: PublicIPAddresses_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkpublicipaddressespublicipaddressname-get
      parameters:
      - in: query
        name: $expand
        description: Expands referenced resources
      - in: query
        name: No Name
      - in: path
        name: publicIpAddressName
        description: The name of the subnet
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Public IP Address
    put:
      summary: Public IPAddresses Create Or Update
      description: Creates or updates a static or dynamic public IP address.
      operationId: PublicIPAddresses_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkpublicipaddressespublicipaddressname-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update public IP address
          operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: publicIpAddressName
        description: The name of the public IP address
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Public IP Address
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/publicIPAddresses:
    get:
      summary: Public IPAddresses List All
      description: Gets all the public IP addresses in a subscription.
      operationId: PublicIPAddresses_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworkpublicipaddresses-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Public IP Address
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/publicIPAddresses:
    get:
      summary: Public IPAddresses List
      description: Gets all public IP addresses in a resource group.
      operationId: PublicIPAddresses_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkpublicipaddresses-get
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
      - Public IP Address
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}:
    delete:
      summary: Route Filters Delete
      description: Deletes the specified route filter.
      operationId: RouteFilters_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefiltername-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      responses:
        200:
          description: OK
      tags:
      - Route Filters
    get:
      summary: Route Filters Get
      description: Gets the specified route filter.
      operationId: RouteFilters_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefiltername-get
      parameters:
      - in: query
        name: $expand
        description: Expands referenced express route bgp peering resources
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      responses:
        200:
          description: OK
      tags:
      - Route Filters
    put:
      summary: Route Filters Create Or Update
      description: Creates or updates a route filter in a specified resource group.
      operationId: RouteFilters_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefiltername-put
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      - in: body
        name: routeFilterParameters
        description: Parameters supplied to the create or update route filter operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Route Filters
    patch:
      summary: Route Filters Update
      description: Updates a route filter in a specified resource group.
      operationId: RouteFilters_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefiltername-patch
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      - in: body
        name: routeFilterParameters
        description: Parameters supplied to the update route filter operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Route Filters
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters:
    get:
      summary: Route Filters List By Resource Group
      description: Gets all route filters in a resource group.
      operationId: RouteFilters_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefilters-get
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
      - Route Filters
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/routeFilters:
    get:
      summary: Route Filters List
      description: Gets all route filters in a subscription.
      operationId: RouteFilters_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworkroutefilters-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Route Filters
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules/{ruleName}
  : delete:
      summary: Route Filter Rules Delete
      description: Deletes the specified rule from a route filter.
      operationId: RouteFilterRules_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrulesrulename-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      - in: path
        name: ruleName
        description: The name of the rule
      responses:
        200:
          description: OK
      tags:
      - Route Filter Rules
    get:
      summary: Route Filter Rules Get
      description: Gets the specified rule from a route filter.
      operationId: RouteFilterRules_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrulesrulename-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      - in: path
        name: ruleName
        description: The name of the rule
      responses:
        200:
          description: OK
      tags:
      - Route Filter Rules
    put:
      summary: Route Filter Rules Create Or Update
      description: Creates or updates a route in the specified route filter.
      operationId: RouteFilterRules_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrulesrulename-put
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      - in: body
        name: routeFilterRuleParameters
        description: Parameters supplied to the create or update route filter rule
          operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: ruleName
        description: The name of the route filter rule
      responses:
        200:
          description: OK
      tags:
      - Route Filter Rules
    patch:
      summary: Route Filter Rules Update
      description: Updates a route in the specified route filter.
      operationId: RouteFilterRules_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrulesrulename-patch
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      - in: body
        name: routeFilterRuleParameters
        description: Parameters supplied to the update route filter rule operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: ruleName
        description: The name of the route filter rule
      responses:
        200:
          description: OK
      tags:
      - Route Filter Rules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules
  : get:
      summary: Route Filter Rules List By Route Filter
      description: Gets all RouteFilterRules in a route filter.
      operationId: RouteFilterRules_ListByRouteFilter
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrules-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      responses:
        200:
          description: OK
      tags:
      - Route Filter Rules
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables/{routeTableName}:
    delete:
      summary: Route Tables Delete
      description: Deletes the specified route table.
      operationId: RouteTables_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablename-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeTableName
        description: The name of the route table
      responses:
        200:
          description: OK
      tags:
      - Route Tables
    get:
      summary: Route Tables Get
      description: Gets the specified route table.
      operationId: RouteTables_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablename-get
      parameters:
      - in: query
        name: $expand
        description: Expands referenced resources
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeTableName
        description: The name of the route table
      responses:
        200:
          description: OK
      tags:
      - Route Tables
    put:
      summary: Route Tables Create Or Update
      description: Create or updates a route table in a specified resource group.
      operationId: RouteTables_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablename-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update route table operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeTableName
        description: The name of the route table
      responses:
        200:
          description: OK
      tags:
      - Route Tables
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables:
    get:
      summary: Route Tables List
      description: Gets all route tables in a resource group.
      operationId: RouteTables_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetables-get
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
      - Route Tables
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/routeTables:
    get:
      summary: Route Tables List All
      description: Gets all route tables in a subscription.
      operationId: RouteTables_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworkroutetables-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Route Tables
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables/{routeTableName}/routes/{routeName}
  : delete:
      summary: Routes Delete
      description: Deletes the specified route from a route table.
      operationId: Routes_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablenameroutesroutename-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeName
        description: The name of the route
      - in: path
        name: routeTableName
        description: The name of the route table
      responses:
        200:
          description: OK
      tags:
      - Routes
    get:
      summary: Routes Get
      description: Gets the specified route from a route table.
      operationId: Routes_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablenameroutesroutename-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeName
        description: The name of the route
      - in: path
        name: routeTableName
        description: The name of the route table
      responses:
        200:
          description: OK
      tags:
      - Routes
    put:
      summary: Routes Create Or Update
      description: Creates or updates a route in the specified route table.
      operationId: Routes_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablenameroutesroutename-put
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeName
        description: The name of the route
      - in: body
        name: routeParameters
        description: Parameters supplied to the create or update route operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: routeTableName
        description: The name of the route table
      responses:
        200:
          description: OK
      tags:
      - Routes
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables/{routeTableName}/routes
  : get:
      summary: Routes List
      description: Gets all routes in a route table.
      operationId: Routes_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablenameroutes-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeTableName
        description: The name of the route table
      responses:
        200:
          description: OK
      tags:
      - Routes
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/bgpServiceCommunities:
    get:
      summary: Bgp Service Communities List
      description: Gets all the available bgp service communities.
      operationId: BgpServiceCommunities_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworkbgpservicecommunities-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Bgp Service Communities
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/locations/{location}/usages:
    get:
      summary: Usages List
      description: Lists compute usages for a subscription.
      operationId: Usages_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworklocationslocationusages-get
      parameters:
      - in: path
        name: location
        description: The location where resource usage is queried
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Usages
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}
  : delete:
      summary: Virtual Networks Delete
      description: Deletes the specified virtual network.
      operationId: VirtualNetworks_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworkname-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
    get:
      summary: Virtual Networks Get
      description: Gets the specified virtual network by resource group.
      operationId: VirtualNetworks_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworkname-get
      parameters:
      - in: query
        name: $expand
        description: Expands referenced resources
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
    put:
      summary: Virtual Networks Create Or Update
      description: Creates or updates a virtual network in the specified resource
        group.
      operationId: VirtualNetworks_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworkname-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update virtual network operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/virtualNetworks:
    get:
      summary: Virtual Networks List All
      description: Gets all virtual networks in a subscription.
      operationId: VirtualNetworks_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftnetworkvirtualnetworks-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks:
    get:
      summary: Virtual Networks List
      description: Gets all virtual networks in a resource group.
      operationId: VirtualNetworks_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworks-get
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
      - Virtual Networks
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/subnets/{subnetName}
  : delete:
      summary: Subnets Delete
      description: Deletes the specified subnet.
      operationId: Subnets_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamesubnetssubnetname-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: subnetName
        description: The name of the subnet
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Subnets
    get:
      summary: Subnets Get
      description: Gets the specified subnet by virtual network and resource group.
      operationId: Subnets_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamesubnetssubnetname-get
      parameters:
      - in: query
        name: $expand
        description: Expands referenced resources
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: subnetName
        description: The name of the subnet
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Subnets
    put:
      summary: Subnets Create Or Update
      description: Creates or updates a subnet in the specified virtual network.
      operationId: Subnets_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamesubnetssubnetname-put
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: subnetName
        description: The name of the subnet
      - in: body
        name: subnetParameters
        description: Parameters supplied to the create or update subnet operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Subnets
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/subnets
  : get:
      summary: Subnets List
      description: Gets all subnets in a virtual network.
      operationId: Subnets_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamesubnets-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Subnets
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/virtualNetworkPeerings/{virtualNetworkPeeringName}
  : delete:
      summary: Virtual Network Peerings Delete
      description: Deletes the specified virtual network peering.
      operationId: VirtualNetworkPeerings_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamevirtualnetworkpeeringsvirtualnetworkpeeringname-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      - in: path
        name: virtualNetworkPeeringName
        description: The name of the virtual network peering
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Peerings
    get:
      summary: Virtual Network Peerings Get
      description: Gets the specified virtual network peering.
      operationId: VirtualNetworkPeerings_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamevirtualnetworkpeeringsvirtualnetworkpeeringname-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      - in: path
        name: virtualNetworkPeeringName
        description: The name of the virtual network peering
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Peerings
    put:
      summary: Virtual Network Peerings Create Or Update
      description: Creates or updates a peering in the specified virtual network.
      operationId: VirtualNetworkPeerings_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamevirtualnetworkpeeringsvirtualnetworkpeeringname-put
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      - in: path
        name: virtualNetworkPeeringName
        description: The name of the peering
      - in: body
        name: VirtualNetworkPeeringParameters
        description: Parameters supplied to the create or update virtual network peering
          operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Peerings
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/virtualNetworkPeerings
  : get:
      summary: Virtual Network Peerings List
      description: Gets all virtual network peerings in a virtual network.
      operationId: VirtualNetworkPeerings_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamevirtualnetworkpeerings-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Peerings
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/CheckIPAddressAvailability
  : get:
      summary: Virtual Networks Check IPAddress Availability
      description: Checks whether a private IP address is available for use.
      operationId: VirtualNetworks_CheckIPAddressAvailability
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamecheckipaddressavailability-get
      parameters:
      - in: query
        name: ipAddress
        description: The private IP address to be verified
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkName
        description: The name of the virtual network
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}
  : put:
      summary: Virtual Network Gateways Create Or Update
      description: Creates or updates a virtual network gateway in the specified resource
        group.
      operationId: VirtualNetworkGateways_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewayname-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to create or update virtual network gateway
          operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayName
        description: The name of the virtual network gateway
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateways
    get:
      summary: Virtual Network Gateways Get
      description: Gets the specified virtual network gateway by resource group.
      operationId: VirtualNetworkGateways_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewayname-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayName
        description: The name of the virtual network gateway
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateways
    delete:
      summary: Virtual Network Gateways Delete
      description: Deletes the specified virtual network gateway.
      operationId: VirtualNetworkGateways_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewayname-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayName
        description: The name of the virtual network gateway
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateways
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways:
    get:
      summary: Virtual Network Gateways List
      description: Gets all virtual network gateways by resource group.
      operationId: VirtualNetworkGateways_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgateways-get
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
      - Virtual Network Gateways
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}/reset
  : post:
      summary: Virtual Network Gateways Reset
      description: Resets the primary of the virtual network gateway in the specified
        resource group.
      operationId: VirtualNetworkGateways_Reset
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamereset-post
      parameters:
      - in: query
        name: gatewayVip
        description: Virtual network gateway vip address supplied to the begin reset
          of the active-active feature enabled gateway
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayName
        description: The name of the virtual network gateway
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateways
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}/generatevpnclientpackage
  : post:
      summary: Virtual Network Gateways Generatevpnclientpackage
      description: Generates VPN client package for P2S client of the virtual network
        gateway in the specified resource group.
      operationId: VirtualNetworkGateways_Generatevpnclientpackage
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamegeneratevpnclientpackage-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the generate virtual network gateway VPN
          client package operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayName
        description: The name of the virtual network gateway
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateways
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}/getBgpPeerStatus
  : post:
      summary: Virtual Network Gateways Get Bgp Peer Status
      description: The GetBgpPeerStatus operation retrieves the status of all BGP
        peers.
      operationId: VirtualNetworkGateways_GetBgpPeerStatus
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamegetbgppeerstatus-post
      parameters:
      - in: query
        name: No Name
      - in: query
        name: peer
        description: The IP address of the peer to retrieve the status of
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayName
        description: The name of the virtual network gateway
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateways
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}/getLearnedRoutes
  : post:
      summary: Virtual Network Gateways Get Learned Routes
      description: This operation retrieves a list of routes the virtual network gateway
        has learned, including routes learned from BGP peers.
      operationId: VirtualNetworkGateways_GetLearnedRoutes
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamegetlearnedroutes-post
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayName
        description: The name of the virtual network gateway
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateways
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}/getAdvertisedRoutes
  : post:
      summary: Virtual Network Gateways Get Advertised Routes
      description: This operation retrieves a list of routes the virtual network gateway
        is advertising to the specified peer.
      operationId: VirtualNetworkGateways_GetAdvertisedRoutes
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamegetadvertisedroutes-post
      parameters:
      - in: query
        name: No Name
      - in: query
        name: peer
        description: The IP address of the peer
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayName
        description: The name of the virtual network gateway
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateways
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections/{virtualNetworkGatewayConnectionName}
  : put:
      summary: Virtual Network Gateway Connections Create Or Update
      description: Creates or updates a virtual network gateway connection in the
        specified resource group.
      operationId: VirtualNetworkGatewayConnections_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionname-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update virtual network gateway
          connection operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayConnectionName
        description: The name of the virtual network gateway connection
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
    get:
      summary: Virtual Network Gateway Connections Get
      description: Gets the specified virtual network gateway connection by resource
        group.
      operationId: VirtualNetworkGatewayConnections_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionname-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayConnectionName
        description: The name of the virtual network gateway connection
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
    delete:
      summary: Virtual Network Gateway Connections Delete
      description: Deletes the specified virtual network Gateway connection.
      operationId: VirtualNetworkGatewayConnections_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionname-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayConnectionName
        description: The name of the virtual network gateway connection
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections/{virtualNetworkGatewayConnectionName}/sharedkey
  : put:
      summary: Virtual Network Gateway Connections Set Shared Key
      description: The Put VirtualNetworkGatewayConnectionSharedKey operation sets
        the virtual network gateway connection shared key for passed virtual network
        gateway connection in the specified resource group through Network resource
        provider.
      operationId: VirtualNetworkGatewayConnections_SetSharedKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionnamesharedkey-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the Begin Set Virtual Network Gateway
          connection Shared key operation throughNetwork resource provider
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayConnectionName
        description: The virtual network gateway connection name
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
    get:
      summary: Virtual Network Gateway Connections Get Shared Key
      description: The Get VirtualNetworkGatewayConnectionSharedKey operation retrieves
        information about the specified virtual network gateway connection shared
        key through Network resource provider.
      operationId: VirtualNetworkGatewayConnections_GetSharedKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionnamesharedkey-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayConnectionName
        description: The virtual network gateway connection shared key name
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections:
    get:
      summary: Virtual Network Gateway Connections List
      description: The List VirtualNetworkGatewayConnections operation retrieves all
        the virtual network gateways connections created.
      operationId: VirtualNetworkGatewayConnections_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnections-get
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
      - Virtual Network Gateway Connections
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