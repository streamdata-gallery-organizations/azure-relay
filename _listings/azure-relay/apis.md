---
name: Azure Relay
x-slug: azure-relay
description: The Azure Relay service facilitates hybrid applications by enabling you
  to securely expose services that reside within a corporate enterprise network to
  the public cloud, without having to open a firewall connection, or require intrusive
  changes to a corporate network infrastructure. Relay supports a variety of different
  transport protocols and web services standards.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
x-kinRank: "10"
x-alexaRank: ""
tags: Azure Relay
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Relay API Operations List
  x-api-slug: azure-relay-api
  description: Lists all of the available Relay REST API operations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////providers/Microsoft.Relay/operations
  tags: Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/providersmicrosoftrelayoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/providersmicrosoftrelayoperations-get-openapi.md
- name: Azure Relay API Namespaces Check Name Availability
  x-api-slug: azure-relay-api
  description: Check the give namespace name availability.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Relay/CheckNameAvailability
  tags: Namespaces Name Availability
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidprovidersmicrosoftrelaychecknameavailability-post-openapi.md
- name: Azure Relay API Namespaces List
  x-api-slug: azure-relay-api
  description: Lists all the available namespaces within the subscription irrespective
    of the resourceGroups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Relay/Namespaces
  tags: Namespaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidprovidersmicrosoftrelaynamespaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidprovidersmicrosoftrelaynamespaces-get-openapi.md
- name: Azure Relay API Namespaces List By Resource Group
  x-api-slug: azure-relay-api
  description: Lists all the available namespaces within the ResourceGroup.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/Namespaces
  tags: Namespaces Resource Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespaces-get-openapi.md
- name: Azure Relay API Namespaces Create Or Update
  x-api-slug: azure-relay-api
  description: Create Azure Relay namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacename-put-openapi.md
- name: Azure Relay API Namespaces Delete
  x-api-slug: azure-relay-api
  description: Deletes an existing namespace. This operation also removes all associated
    resources under the namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacename-delete-openapi.md
- name: Azure Relay API Namespaces Get
  x-api-slug: azure-relay-api
  description: Returns the description for the specified namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacename-get-openapi.md
- name: Azure Relay API Namespaces Update
  x-api-slug: azure-relay-api
  description: Creates or updates a namespace. Once created, this namespace's resource
    manifest is immutable. This operation is idempotent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacename-patch-openapi.md
- name: Azure Relay API Namespaces List Authorization Rules
  x-api-slug: azure-relay-api
  description: Authorization rules for a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/AuthorizationRules
  tags: Namespaces Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenameauthorizationrules-get-openapi.md
- name: Azure Relay API Namespaces Create Or Update Authorization Rule
  x-api-slug: azure-relay-api
  description: Creates or Updates an authorization rule for a namespace
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}
  tags: Namespaces Authorization Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenameauthorizationrulesauthorizationrulename-put-openapi.md
- name: Azure Relay API Namespaces Delete Authorization Rule
  x-api-slug: azure-relay-api
  description: Deletes a namespace authorization rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}
  tags: Namespaces Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: Azure Relay API Namespaces Get Authorization Rule
  x-api-slug: azure-relay-api
  description: Authorization rule for a namespace by name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}
  tags: Namespaces Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenameauthorizationrulesauthorizationrulename-get-openapi.md
- name: Azure Relay API Namespaces List Keys
  x-api-slug: azure-relay-api
  description: Primary and Secondary ConnectionStrings to the namespace
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}/listKeys
  tags: Namespaces Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenameauthorizationrulesauthorizationrulenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenameauthorizationrulesauthorizationrulenamelistkeys-post-openapi.md
- name: Azure Relay API Namespaces Regenerate Keys
  x-api-slug: azure-relay-api
  description: Regenerates the Primary or Secondary ConnectionStrings to the namespace
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}/regenerateKeys
  tags: Namespaces Regenerate Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenameauthorizationrulesauthorizationrulenameregeneratekeys-post-openapi.md
- name: Azure Relay API Hybrid Connections List By Namespace
  x-api-slug: azure-relay-api
  description: Lists the HybridConnection within the namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/HybridConnections
  tags: Hybrid Connections Namespace
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnections-get-openapi.md
- name: Azure Relay API Hybrid Connections Create Or Update
  x-api-slug: azure-relay-api
  description: Creates or Updates a service HybridConnection. This operation is idempotent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/HybridConnections/{hybridConnectionName}
  tags: Hybrid Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionname-put-openapi.md
- name: Azure Relay API Hybrid Connections Delete
  x-api-slug: azure-relay-api
  description: Deletes a HybridConnection .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/HybridConnections/{hybridConnectionName}
  tags: Hybrid Connections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionname-delete-openapi.md
- name: Azure Relay API Hybrid Connections Get
  x-api-slug: azure-relay-api
  description: Returns the description for the specified HybridConnection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/HybridConnections/{hybridConnectionName}
  tags: Hybrid Connections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionname-get-openapi.md
- name: Azure Relay API Hybrid Connections List Authorization Rules
  x-api-slug: azure-relay-api
  description: Authorization rules for a HybridConnection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/HybridConnections/{hybridConnectionName}/authorizationRules
  tags: Hybrid Connections Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionnameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionnameauthorizationrules-get-openapi.md
- name: Azure Relay API Hybrid Connections Create Or Update Authorization Rule
  x-api-slug: azure-relay-api
  description: Creates or Updates an authorization rule for a HybridConnection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/HybridConnections/{hybridConnectionName}/authorizationRules/{authorizationRuleName}
  tags: Hybrid Connections Authorization Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionnameauthorizationrulesauthorizationrulename-put-openapi.md
- name: Azure Relay API Hybrid Connections Delete Authorization Rule
  x-api-slug: azure-relay-api
  description: Deletes a HybridConnection authorization rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/HybridConnections/{hybridConnectionName}/authorizationRules/{authorizationRuleName}
  tags: Hybrid Connections Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionnameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionnameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: Azure Relay API Hybrid Connections Get Authorization Rule
  x-api-slug: azure-relay-api
  description: HybridConnection authorizationRule for a HybridConnection by name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/HybridConnections/{hybridConnectionName}/authorizationRules/{authorizationRuleName}
  tags: Hybrid Connections Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionnameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionnameauthorizationrulesauthorizationrulename-get-openapi.md
- name: Azure Relay API Hybrid Connections List Keys
  x-api-slug: azure-relay-api
  description: Primary and Secondary ConnectionStrings to the HybridConnection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/HybridConnections/{hybridConnectionName}/authorizationRules/{authorizationRuleName}/ListKeys
  tags: Hybrid Connections Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionnameauthorizationrulesauthorizationrulenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionnameauthorizationrulesauthorizationrulenamelistkeys-post-openapi.md
- name: Azure Relay API Hybrid Connections Regenerate Keys
  x-api-slug: azure-relay-api
  description: Regenerates the Primary or Secondary ConnectionStrings to the HybridConnection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/HybridConnections/{hybridConnectionName}/authorizationRules/{authorizationRuleName}/regenerateKeys
  tags: Hybrid Connections Regenerate Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamehybridconnectionshybridconnectionnameauthorizationrulesauthorizationrulenameregeneratekeys-post-openapi.md
- name: Azure Relay API WCFRelays List By Namespace
  x-api-slug: azure-relay-api
  description: Lists the WCFRelays within the namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/WcfRelays
  tags: Wcfrelays Namespace
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelays-get-openapi.md
- name: Azure Relay API WCFRelays Create Or Update
  x-api-slug: azure-relay-api
  description: Creates or Updates a WCFRelay. This operation is idempotent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/WcfRelays/{relayName}
  tags: WCFRelays
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelayname-put-openapi.md
- name: Azure Relay API WCFRelays Delete
  x-api-slug: azure-relay-api
  description: Deletes a WCFRelays .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/WcfRelays/{relayName}
  tags: WCFRelays
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelayname-delete-openapi.md
- name: Azure Relay API WCFRelays Get
  x-api-slug: azure-relay-api
  description: Returns the description for the specified WCFRelays.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/WcfRelays/{relayName}
  tags: WCFRelays
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelayname-get-openapi.md
- name: Azure Relay API WCFRelays List Authorization Rules
  x-api-slug: azure-relay-api
  description: Authorization rules for a WCFRelays.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/WcfRelays/{relayName}/authorizationRules
  tags: WCFRelays Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelaynameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelaynameauthorizationrules-get-openapi.md
- name: Azure Relay API WCFRelays Create Or Update Authorization Rule
  x-api-slug: azure-relay-api
  description: Creates or Updates an authorization rule for a WCFRelays
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/WcfRelays/{relayName}/authorizationRules/{authorizationRuleName}
  tags: WCFRelays Authorization Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelaynameauthorizationrulesauthorizationrulename-put-openapi.md
- name: Azure Relay API WCFRelays Delete Authorization Rule
  x-api-slug: azure-relay-api
  description: Deletes a WCFRelays authorization rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/WcfRelays/{relayName}/authorizationRules/{authorizationRuleName}
  tags: WCFRelays Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelaynameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelaynameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: Azure Relay API WCFRelays Get Authorization Rule
  x-api-slug: azure-relay-api
  description: Get authorizationRule for a WCFRelays by name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/WcfRelays/{relayName}/authorizationRules/{authorizationRuleName}
  tags: WCFRelays Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelaynameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelaynameauthorizationrulesauthorizationrulename-get-openapi.md
- name: Azure Relay API WCFRelays List Keys
  x-api-slug: azure-relay-api
  description: Primary and Secondary ConnectionStrings to the WCFRelays.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/WcfRelays/{relayName}/authorizationRules/{authorizationRuleName}/ListKeys
  tags: WCFRelays Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelaynameauthorizationrulesauthorizationrulenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelaynameauthorizationrulesauthorizationrulenamelistkeys-post-openapi.md
- name: Azure Relay API WCFRelays Regenerate Keys
  x-api-slug: azure-relay-api
  description: Regenerates the Primary or Secondary ConnectionStrings to the WCFRelays
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Relay/namespaces/{namespaceName}/WcfRelays/{relayName}/authorizationRules/{authorizationRuleName}/regenerateKeys
  tags: WCFRelays Regenerate Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftrelaynamespacesnamespacenamewcfrelaysrelaynameauthorizationrulesauthorizationrulenameregeneratekeys-post-openapi.md
- name: Azure Relay API
  x-api-slug: azure-relay-api
  description: The Azure Relay service facilitates hybrid applications by enabling
    you to securely expose services that reside within a corporate enterprise network
    to the public cloud, without having to open a firewall connection, or require
    intrusive changes to a corporate network infrastructure. Relay supports a variety
    of different transport protocols and web services standards.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com//
  tags: Azure Relay
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-relay/master/_listings/azure-relay/openapi.md
x-common:
- type: x-blog
  url: https://blogs.msdn.microsoft.com/servicebus/
- type: x-blog-rss
  url: https://blogs.msdn.microsoft.com/servicebus/feed/
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/service-bus-relay/
- type: x-pricing
  url: https://azure.microsoft.com/pricing/details/service-bus/
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/azure-servicebusrelay
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---