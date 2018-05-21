---
name: Azure Virtual Network
x-slug: azure-virtual-network
description: Azure Virtual Network lets you create private networks in the cloud with
  full control over IP addresses, DNS servers, security rules, and traffic flows.
  Securely connect a virtual network to on-premises networks by using a VPN tunnel,
  or connect privately by using the ExpressRoute service.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
x-kinRank: "10"
x-alexaRank: ""
tags: Azure Virtual Network
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Virtual Network API Application Gateways Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified application gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways/{applicationGatewayName}
  tags: Application Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewayname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewayname-delete-openapi.md
- name: Azure Virtual Network API Application Gateways Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified application gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways/{applicationGatewayName}
  tags: Application Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewayname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewayname-get-openapi.md
- name: Azure Virtual Network API Application Gateways Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates the specified application gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways/{applicationGatewayName}
  tags: Application Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewayname-put-openapi.md
- name: Azure Virtual Network API Application Gateways List
  x-api-slug: azure-virtual-network-api
  description: Lists all application gateways in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways
  tags: Application Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgateways-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgateways-get-openapi.md
- name: Azure Virtual Network API Application Gateways List All
  x-api-slug: azure-virtual-network-api
  description: Gets all the application gateways in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/applicationGateways
  tags: Application Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkapplicationgateways-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkapplicationgateways-get-openapi.md
- name: Azure Virtual Network API Application Gateways Start
  x-api-slug: azure-virtual-network-api
  description: Starts the specified application gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways/{applicationGatewayName}/start
  tags: Application Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewaynamestart-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewaynamestart-post-openapi.md
- name: Azure Virtual Network API Application Gateways Stop
  x-api-slug: azure-virtual-network-api
  description: Stops the specified application gateway in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways/{applicationGatewayName}/stop
  tags: Application Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewaynamestop-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewaynamestop-post-openapi.md
- name: Azure Virtual Network API Application Gateways Backend Health
  x-api-slug: azure-virtual-network-api
  description: Gets the backend health of the specified application gateway in a resource
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways/{applicationGatewayName}/backendhealth
  tags: Application Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewaynamebackendhealth-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkapplicationgatewaysapplicationgatewaynamebackendhealth-post-openapi.md
- name: Azure Virtual Network API Application Gateways List Available Waf Rule Sets
  x-api-slug: azure-virtual-network-api
  description: Lists all available web application firewall rule sets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/applicationGatewayAvailableWafRuleSets
  tags: Application Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkapplicationgatewayavailablewafrulesets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkapplicationgatewayavailablewafrulesets-get-openapi.md
- name: Azure Virtual Network API Check Dns Name Availability
  x-api-slug: azure-virtual-network-api
  description: Checks whether a domain name in the cloudapp.net zone is available
    for use.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/locations/{location}/CheckDnsNameAvailability
  tags: Dns Name Availability
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworklocationslocationcheckdnsnameavailability-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworklocationslocationcheckdnsnameavailability-get-openapi.md
- name: Azure Virtual Network API Express Route Circuit Authorizations Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified authorization from the specified express route
    circuit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/authorizations/{authorizationName}
  tags: Express Route Circuit Authorizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnameauthorizationsauthorizationname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnameauthorizationsauthorizationname-delete-openapi.md
- name: Azure Virtual Network API Express Route Circuit Authorizations Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified authorization from the specified express route circuit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/authorizations/{authorizationName}
  tags: Express Route Circuit Authorizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnameauthorizationsauthorizationname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnameauthorizationsauthorizationname-get-openapi.md
- name: Azure Virtual Network API Express Route Circuit Authorizations Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates an authorization in the specified express route
    circuit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/authorizations/{authorizationName}
  tags: Express Route Circuit Authorizations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnameauthorizationsauthorizationname-put-openapi.md
- name: Azure Virtual Network API Express Route Circuit Authorizations List
  x-api-slug: azure-virtual-network-api
  description: Gets all authorizations in an express route circuit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/authorizations
  tags: Express Route Circuit Authorizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnameauthorizations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnameauthorizations-get-openapi.md
- name: Azure Virtual Network API Express Route Circuit Peerings Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified peering from the specified express route circuit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}
  tags: Express Route Circuit Peerings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringname-delete-openapi.md
- name: Azure Virtual Network API Express Route Circuit Peerings Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified authorization from the specified express route circuit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}
  tags: Express Route Circuit Peerings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringname-get-openapi.md
- name: Azure Virtual Network API Express Route Circuit Peerings Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a peering in the specified express route circuits.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}
  tags: Express Route Circuit Peerings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringname-put-openapi.md
- name: Azure Virtual Network API Express Route Circuit Peerings List
  x-api-slug: azure-virtual-network-api
  description: Gets all peerings in a specified express route circuit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings
  tags: Express Route Circuit Peerings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeerings-get-openapi.md
- name: Azure Virtual Network API Express Route Circuits Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified express route circuit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}
  tags: Express Route Circuits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitname-delete-openapi.md
- name: Azure Virtual Network API Express Route Circuits Get
  x-api-slug: azure-virtual-network-api
  description: Gets information about the specified express route circuit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}
  tags: Express Route Circuits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitname-get-openapi.md
- name: Azure Virtual Network API Express Route Circuits Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates an express route circuit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}
  tags: Express Route Circuits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitname-put-openapi.md
- name: Azure Virtual Network API Express Route Circuits List Arp Table
  x-api-slug: azure-virtual-network-api
  description: Gets the currently advertised ARP table associated with the express
    route circuit in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}/arpTables/{devicePath}
  tags: Express Route Circuits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringnamearptablesdevicepath-post-openapi.md
- name: Azure Virtual Network API Express Route Circuits List Routes Table
  x-api-slug: azure-virtual-network-api
  description: Gets the currently advertised routes table associated with the express
    route circuit in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}/routeTables/{devicePath}
  tags: Express Route Circuits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringnameroutetablesdevicepath-post-openapi.md
- name: Azure Virtual Network API Express Route Circuits List Routes Table Summary
  x-api-slug: azure-virtual-network-api
  description: Gets the currently advertised routes table summary associated with
    the express route circuit in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}/routeTablesSummary/{devicePath}
  tags: Express Route Circuits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringnameroutetablessummarydevicepath-post-openapi.md
- name: Azure Virtual Network API Express Route Circuits Get Stats
  x-api-slug: azure-virtual-network-api
  description: Gets all the stats from an express route circuit in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/stats
  tags: Express Route Circuits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamestats-get-openapi.md
- name: Azure Virtual Network API Express Route Circuits Get Peering Stats
  x-api-slug: azure-virtual-network-api
  description: Gets all stats from an express route circuit in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits/{circuitName}/peerings/{peeringName}/stats
  tags: Express Route Circuits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuitscircuitnamepeeringspeeringnamestats-get-openapi.md
- name: Azure Virtual Network API Express Route Circuits List
  x-api-slug: azure-virtual-network-api
  description: Gets all the express route circuits in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits
  tags: Express Route Circuits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkexpressroutecircuits-get-openapi.md
- name: Azure Virtual Network API Express Route Circuits List All
  x-api-slug: azure-virtual-network-api
  description: Gets all the express route circuits in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/expressRouteCircuits
  tags: Express Route Circuits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkexpressroutecircuits-get-openapi.md
- name: Azure Virtual Network API Express Route Service Providers List
  x-api-slug: azure-virtual-network-api
  description: Gets all the available express route service providers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/expressRouteServiceProviders
  tags: Express Route Service Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkexpressrouteserviceproviders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkexpressrouteserviceproviders-get-openapi.md
- name: Azure Virtual Network API Load Balancers Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified load balancer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers/{loadBalancerName}
  tags: Load Balancers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkloadbalancersloadbalancername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkloadbalancersloadbalancername-delete-openapi.md
- name: Azure Virtual Network API Load Balancers Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified load balancer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers/{loadBalancerName}
  tags: Load Balancers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkloadbalancersloadbalancername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkloadbalancersloadbalancername-get-openapi.md
- name: Azure Virtual Network API Load Balancers Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a load balancer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers/{loadBalancerName}
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkloadbalancersloadbalancername-put-openapi.md
- name: Azure Virtual Network API Load Balancers List All
  x-api-slug: azure-virtual-network-api
  description: Gets all the load balancers in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/loadBalancers
  tags: Load Balancers All
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkloadbalancers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkloadbalancers-get-openapi.md
- name: Azure Virtual Network API Load Balancers List
  x-api-slug: azure-virtual-network-api
  description: Gets all the load balancers in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers
  tags: Load Balancers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkloadbalancers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkloadbalancers-get-openapi.md
- name: Azure Virtual Network API Network Interfaces Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkInterfaces/{networkInterfaceName}
  tags: Network Interfaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacename-delete-openapi.md
- name: Azure Virtual Network API Network Interfaces Get
  x-api-slug: azure-virtual-network-api
  description: Gets information about the specified network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkInterfaces/{networkInterfaceName}
  tags: Network Interfaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacename-get-openapi.md
- name: Azure Virtual Network API Network Interfaces Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkInterfaces/{networkInterfaceName}
  tags: Network Interfaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacename-put-openapi.md
- name: Azure Virtual Network API Network Interfaces List All
  x-api-slug: azure-virtual-network-api
  description: Gets all network interfaces in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/networkInterfaces
  tags: Network Interfaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworknetworkinterfaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworknetworkinterfaces-get-openapi.md
- name: Azure Virtual Network API Network Interfaces List
  x-api-slug: azure-virtual-network-api
  description: Gets all network interfaces in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkInterfaces
  tags: Network Interfaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfaces-get-openapi.md
- name: Azure Virtual Network API Network Interfaces Get Effective Route Table
  x-api-slug: azure-virtual-network-api
  description: Gets all route tables applied to a network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkInterfaces/{networkInterfaceName}/effectiveRouteTable
  tags: Network Interfaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacenameeffectiveroutetable-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacenameeffectiveroutetable-post-openapi.md
- name: Azure Virtual Network API Network Interfaces List Effective Network Security
    Groups
  x-api-slug: azure-virtual-network-api
  description: Gets all network security groups applied to a network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkInterfaces/{networkInterfaceName}/effectiveNetworkSecurityGroups
  tags: Network Interfaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacenameeffectivenetworksecuritygroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkinterfacesnetworkinterfacenameeffectivenetworksecuritygroups-post-openapi.md
- name: Azure Virtual Network API Network Security Groups Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified network security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}
  tags: Network Security Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupname-delete-openapi.md
- name: Azure Virtual Network API Network Security Groups Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified network security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}
  tags: Network Security Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupname-get-openapi.md
- name: Azure Virtual Network API Network Security Groups Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a network security group in the specified resource
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}
  tags: Network Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupname-put-openapi.md
- name: Azure Virtual Network API Network Security Groups List All
  x-api-slug: azure-virtual-network-api
  description: Gets all network security groups in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/networkSecurityGroups
  tags: Network Security Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworknetworksecuritygroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworknetworksecuritygroups-get-openapi.md
- name: Azure Virtual Network API Network Security Groups List
  x-api-slug: azure-virtual-network-api
  description: Gets all network security groups in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups
  tags: Network Security Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroups-get-openapi.md
- name: Azure Virtual Network API Security Rules Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified network security rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules/{securityRuleName}
  tags: Security Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-delete-openapi.md
- name: Azure Virtual Network API Security Rules Get
  x-api-slug: azure-virtual-network-api
  description: Get the specified network security rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules/{securityRuleName}
  tags: Security Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-get-openapi.md
- name: Azure Virtual Network API Security Rules Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a security rule in the specified network security
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules/{securityRuleName}
  tags: Security Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-put-openapi.md
- name: Azure Virtual Network API Security Rules List
  x-api-slug: azure-virtual-network-api
  description: Gets all security rules in a network security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules
  tags: Security Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupnamesecurityrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworksecuritygroupsnetworksecuritygroupnamesecurityrules-get-openapi.md
- name: Azure Virtual Network API Network Watchers Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a network watcher in the specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchername-put-openapi.md
- name: Azure Virtual Network API Network Watchers Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified network watcher by resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchername-get-openapi.md
- name: Azure Virtual Network API Network Watchers Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified network watcher resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchername-delete-openapi.md
- name: Azure Virtual Network API Network Watchers List
  x-api-slug: azure-virtual-network-api
  description: Gets all network watchers by resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchers-get-openapi.md
- name: Azure Virtual Network API Network Watchers List All
  x-api-slug: azure-virtual-network-api
  description: Gets all network watchers by subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/networkWatchers
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworknetworkwatchers-get-openapi.md
- name: Azure Virtual Network API Network Watchers Get Topology
  x-api-slug: azure-virtual-network-api
  description: Gets the current network topology by resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/topology
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernametopology-post-openapi.md
- name: Azure Virtual Network API Network Watchers Verify IPFlow
  x-api-slug: azure-virtual-network-api
  description: Verify IP flow from the specified VM to a location given the currently
    configured NSG rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/ipFlowVerify
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernameipflowverify-post-openapi.md
- name: Azure Virtual Network API Network Watchers Get Next Hop
  x-api-slug: azure-virtual-network-api
  description: Gets the next hop from the specified VM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/nextHop
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamenexthop-post-openapi.md
- name: Azure Virtual Network API Network Watchers Get VMSecurity Rules
  x-api-slug: azure-virtual-network-api
  description: Gets the configured and effective security group rules on the specified
    VM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/securityGroupView
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamesecuritygroupview-post-openapi.md
- name: Azure Virtual Network API Packet Captures Create
  x-api-slug: azure-virtual-network-api
  description: Create and start a packet capture on the specified VM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/packetCaptures/{packetCaptureName}
  tags: Packet Captures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcapturespacketcapturename-put-openapi.md
- name: Azure Virtual Network API Packet Captures Get
  x-api-slug: azure-virtual-network-api
  description: Gets a packet capture session by name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/packetCaptures/{packetCaptureName}
  tags: Packet Captures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcapturespacketcapturename-get-openapi.md
- name: Azure Virtual Network API Packet Captures Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified packet capture session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/packetCaptures/{packetCaptureName}
  tags: Packet Captures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcapturespacketcapturename-delete-openapi.md
- name: Azure Virtual Network API Packet Captures Stop
  x-api-slug: azure-virtual-network-api
  description: Stops a specified packet capture session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/packetCaptures/{packetCaptureName}/stop
  tags: Packet Captures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcapturespacketcapturenamestop-post-openapi.md
- name: Azure Virtual Network API Packet Captures Get Status
  x-api-slug: azure-virtual-network-api
  description: Query the status of a running packet capture session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/packetCaptures/{packetCaptureName}/queryStatus
  tags: Packet Captures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcapturespacketcapturenamequerystatus-post-openapi.md
- name: Azure Virtual Network API Packet Captures List
  x-api-slug: azure-virtual-network-api
  description: Lists all packet capture sessions within the specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/packetCaptures
  tags: Packet Captures
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamepacketcaptures-get-openapi.md
- name: Azure Virtual Network API Network Watchers Get Troubleshooting
  x-api-slug: azure-virtual-network-api
  description: Initiate troubleshooting on a specified resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/troubleshoot
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernametroubleshoot-post-openapi.md
- name: Azure Virtual Network API Network Watchers Get Troubleshooting Result
  x-api-slug: azure-virtual-network-api
  description: Get the last completed troubleshooting result on a specified resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/queryTroubleshootResult
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamequerytroubleshootresult-post-openapi.md
- name: Azure Virtual Network API Network Watchers Set Flow Log Configuration
  x-api-slug: azure-virtual-network-api
  description: Configures flow log on a specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/configureFlowLog
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernameconfigureflowlog-post-openapi.md
- name: Azure Virtual Network API Network Watchers Get Flow Log Status
  x-api-slug: azure-virtual-network-api
  description: Queries status of flow log on a specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers/{networkWatcherName}/queryFlowLogStatus
  tags: Network Watchers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworknetworkwatchersnetworkwatchernamequeryflowlogstatus-post-openapi.md
- name: Azure Virtual Network API Public IPAddresses Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified public IP address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/publicIPAddresses/{publicIpAddressName}
  tags: Public IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkpublicipaddressespublicipaddressname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkpublicipaddressespublicipaddressname-delete-openapi.md
- name: Azure Virtual Network API Public IPAddresses Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified public IP address in a specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/publicIPAddresses/{publicIpAddressName}
  tags: Public IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkpublicipaddressespublicipaddressname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkpublicipaddressespublicipaddressname-get-openapi.md
- name: Azure Virtual Network API Public IPAddresses Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a static or dynamic public IP address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/publicIPAddresses/{publicIpAddressName}
  tags: Public IP Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkpublicipaddressespublicipaddressname-put-openapi.md
- name: Azure Virtual Network API Public IPAddresses List All
  x-api-slug: azure-virtual-network-api
  description: Gets all the public IP addresses in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/publicIPAddresses
  tags: Public IP Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkpublicipaddresses-get-openapi.md
- name: Azure Virtual Network API Public IPAddresses List
  x-api-slug: azure-virtual-network-api
  description: Gets all public IP addresses in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/publicIPAddresses
  tags: Public IP Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkpublicipaddresses-get-openapi.md
- name: Azure Virtual Network API Route Filters Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}
  tags: Route Filters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefiltername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefiltername-delete-openapi.md
- name: Azure Virtual Network API Route Filters Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}
  tags: Route Filters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefiltername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefiltername-get-openapi.md
- name: Azure Virtual Network API Route Filters Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a route filter in a specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}
  tags: Route Filters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefiltername-put-openapi.md
- name: Azure Virtual Network API Route Filters Update
  x-api-slug: azure-virtual-network-api
  description: Updates a route filter in a specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}
  tags: Route Filters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefiltername-patch-openapi.md
- name: Azure Virtual Network API Route Filters List By Resource Group
  x-api-slug: azure-virtual-network-api
  description: Gets all route filters in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters
  tags: Route Filters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefilters-get-openapi.md
- name: Azure Virtual Network API Route Filters List
  x-api-slug: azure-virtual-network-api
  description: Gets all route filters in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/routeFilters
  tags: Route Filters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkroutefilters-get-openapi.md
- name: Azure Virtual Network API Route Filter Rules Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified rule from a route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules/{ruleName}
  tags: Route Filter Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrulesrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrulesrulename-delete-openapi.md
- name: Azure Virtual Network API Route Filter Rules Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified rule from a route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules/{ruleName}
  tags: Route Filter Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrulesrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrulesrulename-get-openapi.md
- name: Azure Virtual Network API Route Filter Rules Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a route in the specified route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules/{ruleName}
  tags: Route Filter Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrulesrulename-put-openapi.md
- name: Azure Virtual Network API Route Filter Rules Update
  x-api-slug: azure-virtual-network-api
  description: Updates a route in the specified route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules/{ruleName}
  tags: Route Filter Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrulesrulename-patch-openapi.md
- name: Azure Virtual Network API Route Filter Rules List By Route Filter
  x-api-slug: azure-virtual-network-api
  description: Gets all RouteFilterRules in a route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules
  tags: Route Filter Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutefiltersroutefilternameroutefilterrules-get-openapi.md
- name: Azure Virtual Network API Route Tables Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified route table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables/{routeTableName}
  tags: Route Tables
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablename-delete-openapi.md
- name: Azure Virtual Network API Route Tables Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified route table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables/{routeTableName}
  tags: Route Tables
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablename-get-openapi.md
- name: Azure Virtual Network API Route Tables Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Create or updates a route table in a specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables/{routeTableName}
  tags: Route Tables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablename-put-openapi.md
- name: Azure Virtual Network API Route Tables List
  x-api-slug: azure-virtual-network-api
  description: Gets all route tables in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables
  tags: Route Tables
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetables-get-openapi.md
- name: Azure Virtual Network API Route Tables List All
  x-api-slug: azure-virtual-network-api
  description: Gets all route tables in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/routeTables
  tags: Route Tables
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkroutetables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkroutetables-get-openapi.md
- name: Azure Virtual Network API Routes Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified route from a route table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables/{routeTableName}/routes/{routeName}
  tags: Routes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablenameroutesroutename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablenameroutesroutename-delete-openapi.md
- name: Azure Virtual Network API Routes Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified route from a route table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables/{routeTableName}/routes/{routeName}
  tags: Routes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablenameroutesroutename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablenameroutesroutename-get-openapi.md
- name: Azure Virtual Network API Routes Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a route in the specified route table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables/{routeTableName}/routes/{routeName}
  tags: Routes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablenameroutesroutename-put-openapi.md
- name: Azure Virtual Network API Routes List
  x-api-slug: azure-virtual-network-api
  description: Gets all routes in a route table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeTables/{routeTableName}/routes
  tags: Routes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablenameroutes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkroutetablesroutetablenameroutes-get-openapi.md
- name: Azure Virtual Network API Bgp Service Communities List
  x-api-slug: azure-virtual-network-api
  description: Gets all the available bgp service communities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/bgpServiceCommunities
  tags: Bgp Service Communities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkbgpservicecommunities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkbgpservicecommunities-get-openapi.md
- name: Azure Virtual Network API Usages List
  x-api-slug: azure-virtual-network-api
  description: Lists compute usages for a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/locations/{location}/usages
  tags: Usages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworklocationslocationusages-get-openapi.md
- name: Azure Virtual Network API Virtual Networks Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified virtual network.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}
  tags: Virtual Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworkname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworkname-delete-openapi.md
- name: Azure Virtual Network API Virtual Networks Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified virtual network by resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}
  tags: Virtual Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworkname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworkname-get-openapi.md
- name: Azure Virtual Network API Virtual Networks Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a virtual network in the specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}
  tags: Virtual Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworkname-put-openapi.md
- name: Azure Virtual Network API Virtual Networks List All
  x-api-slug: azure-virtual-network-api
  description: Gets all virtual networks in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/virtualNetworks
  tags: Virtual Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkvirtualnetworks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoftnetworkvirtualnetworks-get-openapi.md
- name: Azure Virtual Network API Virtual Networks List
  x-api-slug: azure-virtual-network-api
  description: Gets all virtual networks in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks
  tags: Virtual Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworks-get-openapi.md
- name: Azure Virtual Network API Subnets Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified subnet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/subnets/{subnetName}
  tags: Subnets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamesubnetssubnetname-delete-openapi.md
- name: Azure Virtual Network API Subnets Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified subnet by virtual network and resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/subnets/{subnetName}
  tags: Subnets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamesubnetssubnetname-get-openapi.md
- name: Azure Virtual Network API Subnets Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a subnet in the specified virtual network.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/subnets/{subnetName}
  tags: Subnets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamesubnetssubnetname-put-openapi.md
- name: Azure Virtual Network API Subnets List
  x-api-slug: azure-virtual-network-api
  description: Gets all subnets in a virtual network.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/subnets
  tags: Subnets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamesubnets-get-openapi.md
- name: Azure Virtual Network API Virtual Network Peerings Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified virtual network peering.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/virtualNetworkPeerings/{virtualNetworkPeeringName}
  tags: Virtual Network Peerings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamevirtualnetworkpeeringsvirtualnetworkpeeringname-delete-openapi.md
- name: Azure Virtual Network API Virtual Network Peerings Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified virtual network peering.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/virtualNetworkPeerings/{virtualNetworkPeeringName}
  tags: Virtual Network Peerings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamevirtualnetworkpeeringsvirtualnetworkpeeringname-get-openapi.md
- name: Azure Virtual Network API Virtual Network Peerings Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a peering in the specified virtual network.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/virtualNetworkPeerings/{virtualNetworkPeeringName}
  tags: Virtual Network Peerings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamevirtualnetworkpeeringsvirtualnetworkpeeringname-put-openapi.md
- name: Azure Virtual Network API Virtual Network Peerings List
  x-api-slug: azure-virtual-network-api
  description: Gets all virtual network peerings in a virtual network.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/virtualNetworkPeerings
  tags: Virtual Network Peerings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamevirtualnetworkpeerings-get-openapi.md
- name: Azure Virtual Network API Virtual Networks Check IPAddress Availability
  x-api-slug: azure-virtual-network-api
  description: Checks whether a private IP address is available for use.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}/CheckIPAddressAvailability
  tags: Virtual Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamecheckipaddressavailability-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworksvirtualnetworknamecheckipaddressavailability-get-openapi.md
- name: Azure Virtual Network API Virtual Network Gateways Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a virtual network gateway in the specified resource
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}
  tags: Virtual Network Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewayname-put-openapi.md
- name: Azure Virtual Network API Virtual Network Gateways Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified virtual network gateway by resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}
  tags: Virtual Network Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewayname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewayname-get-openapi.md
- name: Azure Virtual Network API Virtual Network Gateways Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified virtual network gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}
  tags: Virtual Network Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewayname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewayname-delete-openapi.md
- name: Azure Virtual Network API Virtual Network Gateways List
  x-api-slug: azure-virtual-network-api
  description: Gets all virtual network gateways by resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways
  tags: Virtual Network Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgateways-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgateways-get-openapi.md
- name: Azure Virtual Network API Virtual Network Gateways Reset
  x-api-slug: azure-virtual-network-api
  description: Resets the primary of the virtual network gateway in the specified
    resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}/reset
  tags: Virtual Network Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamereset-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamereset-post-openapi.md
- name: Azure Virtual Network API Virtual Network Gateways Generatevpnclientpackage
  x-api-slug: azure-virtual-network-api
  description: Generates VPN client package for P2S client of the virtual network
    gateway in the specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}/generatevpnclientpackage
  tags: Virtual Network Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamegeneratevpnclientpackage-post-openapi.md
- name: Azure Virtual Network API Virtual Network Gateways Get Bgp Peer Status
  x-api-slug: azure-virtual-network-api
  description: The GetBgpPeerStatus operation retrieves the status of all BGP peers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}/getBgpPeerStatus
  tags: Virtual Network Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamegetbgppeerstatus-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamegetbgppeerstatus-post-openapi.md
- name: Azure Virtual Network API Virtual Network Gateways Get Learned Routes
  x-api-slug: azure-virtual-network-api
  description: This operation retrieves a list of routes the virtual network gateway
    has learned, including routes learned from BGP peers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}/getLearnedRoutes
  tags: Virtual Network Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamegetlearnedroutes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamegetlearnedroutes-post-openapi.md
- name: Azure Virtual Network API Virtual Network Gateways Get Advertised Routes
  x-api-slug: azure-virtual-network-api
  description: This operation retrieves a list of routes the virtual network gateway
    is advertising to the specified peer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways/{virtualNetworkGatewayName}/getAdvertisedRoutes
  tags: Virtual Network Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamegetadvertisedroutes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkvirtualnetworkgatewaysvirtualnetworkgatewaynamegetadvertisedroutes-post-openapi.md
- name: Azure Virtual Network API Virtual Network Gateway Connections Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a virtual network gateway connection in the specified
    resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections/{virtualNetworkGatewayConnectionName}
  tags: Virtual Network Gateway Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionname-put-openapi.md
- name: Azure Virtual Network API Virtual Network Gateway Connections Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified virtual network gateway connection by resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections/{virtualNetworkGatewayConnectionName}
  tags: Virtual Network Gateway Connections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionname-get-openapi.md
- name: Azure Virtual Network API Virtual Network Gateway Connections Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified virtual network Gateway connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections/{virtualNetworkGatewayConnectionName}
  tags: Virtual Network Gateway Connections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionname-delete-openapi.md
- name: Azure Virtual Network API Virtual Network Gateway Connections Set Shared Key
  x-api-slug: azure-virtual-network-api
  description: The Put VirtualNetworkGatewayConnectionSharedKey operation sets the
    virtual network gateway connection shared key for passed virtual network gateway
    connection in the specified resource group through Network resource provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections/{virtualNetworkGatewayConnectionName}/sharedkey
  tags: Virtual Network Gateway Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionnamesharedkey-put-openapi.md
- name: Azure Virtual Network API Virtual Network Gateway Connections Get Shared Key
  x-api-slug: azure-virtual-network-api
  description: The Get VirtualNetworkGatewayConnectionSharedKey operation retrieves
    information about the specified virtual network gateway connection shared key
    through Network resource provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections/{virtualNetworkGatewayConnectionName}/sharedkey
  tags: Virtual Network Gateway Connections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionnamesharedkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionnamesharedkey-get-openapi.md
- name: Azure Virtual Network API Virtual Network Gateway Connections List
  x-api-slug: azure-virtual-network-api
  description: The List VirtualNetworkGatewayConnections operation retrieves all the
    virtual network gateways connections created.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections
  tags: Virtual Network Gateway Connections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnections-get-openapi.md
- name: Azure Virtual Network API Virtual Network Gateway Connections Reset Shared
    Key
  x-api-slug: azure-virtual-network-api
  description: The VirtualNetworkGatewayConnectionResetSharedKey operation resets
    the virtual network gateway connection shared key for passed virtual network gateway
    connection in the specified resource group through Network resource provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections/{virtualNetworkGatewayConnectionName}/sharedkey/reset
  tags: Virtual Network Gateway Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworkconnectionsvirtualnetworkgatewayconnectionnamesharedkeyreset-post-openapi.md
- name: Azure Virtual Network API Local Network Gateways Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a local network gateway in the specified resource
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/localNetworkGateways/{localNetworkGatewayName}
  tags: Local Network Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworklocalnetworkgatewayslocalnetworkgatewayname-put-openapi.md
- name: Azure Virtual Network API Local Network Gateways Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified local network gateway in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/localNetworkGateways/{localNetworkGatewayName}
  tags: Local Network Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworklocalnetworkgatewayslocalnetworkgatewayname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworklocalnetworkgatewayslocalnetworkgatewayname-get-openapi.md
- name: Azure Virtual Network API Local Network Gateways Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified local network gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/localNetworkGateways/{localNetworkGatewayName}
  tags: Local Network Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworklocalnetworkgatewayslocalnetworkgatewayname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworklocalnetworkgatewayslocalnetworkgatewayname-delete-openapi.md
- name: Azure Virtual Network API Local Network Gateways List
  x-api-slug: azure-virtual-network-api
  description: Gets all the local network gateways in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/localNetworkGateways
  tags: Local Network Gateways
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworklocalnetworkgateways-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworklocalnetworkgateways-get-openapi.md
- name: Azure Virtual Network API Network Interfaces List Virtual Machine Scale Set
    VMNetwork Interfaces
  x-api-slug: azure-virtual-network-api
  description: Gets information about all network interfaces in a virtual machine
    in a virtual machine scale set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/microsoft.Compute/virtualMachineScaleSets/{virtualMachineScaleSetName}/virtualMachines/{virtualmachineIndex}/networkInterfaces
  tags: Network Interfaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcomputevirtualmachinescalesetsvirtualmachinescalesetnamevirtualmachinesvirtualmachineindexnetworkinterfaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcomputevirtualmachinescalesetsvirtualmachinescalesetnamevirtualmachinesvirtualmachineindexnetworkinterfaces-get-openapi.md
- name: Azure Virtual Network API Network Interfaces List Virtual Machine Scale Set
    Network Interfaces
  x-api-slug: azure-virtual-network-api
  description: Gets all network interfaces in a virtual machine scale set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/microsoft.Compute/virtualMachineScaleSets/{virtualMachineScaleSetName}/networkInterfaces
  tags: Network Interfaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcomputevirtualmachinescalesetsvirtualmachinescalesetnamenetworkinterfaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcomputevirtualmachinescalesetsvirtualmachinescalesetnamenetworkinterfaces-get-openapi.md
- name: Azure Virtual Network API Network Interfaces Get Virtual Machine Scale Set
    Network Interface
  x-api-slug: azure-virtual-network-api
  description: Get the specified network interface in a virtual machine scale set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/microsoft.Compute/virtualMachineScaleSets/{virtualMachineScaleSetName}/virtualMachines/{virtualmachineIndex}/networkInterfaces/{networkInterfaceName}
  tags: Network Interfaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcomputevirtualmachinescalesetsvirtualmachinescalesetnamevirtualmachinesvirtualmachineindexnetworkinterfacesnetworkinterfacename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcomputevirtualmachinescalesetsvirtualmachinescalesetnamevirtualmachinesvirtualmachineindexnetworkinterfacesnetworkinterfacename-get-openapi.md
- name: Azure Virtual Network API
  x-api-slug: azure-virtual-network-api
  description: Azure Virtual Network lets you create private networks in the cloud
    with full control over IP addresses, DNS servers, security rules, and traffic
    flows. Securely connect a virtual network to on-premises networks by using a VPN
    tunnel, or connect privately by using the ExpressRoute service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Azure Virtual Network
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-virtual-network/master/_listings/azure-virtual-network/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/virtual-network/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/virtual-network/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/virtual-network/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---