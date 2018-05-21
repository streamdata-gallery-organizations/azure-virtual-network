---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 0
info:
  title: Azure Virtual Network API Security Rules List
  description: Gets all security rules in a network security group.
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