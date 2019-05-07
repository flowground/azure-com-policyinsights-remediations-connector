# ![LOGO](logo.png) RemediationsClient **flow**ground Connector

## Description

A generated **flow**ground connector for the RemediationsClient API (version 2018-07-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/policyinsights-remediations/2018-07-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:36+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets all remediations for the management group.

#### Input Parameters
* `managementGroupsNamespace` - _required_ - The namespace for Microsoft Management RP; only "Microsoft.Management" is allowed.
    Possible values: Microsoft.Management.
* `managementGroupId` - _required_ - Management group ID.
* `$top` - _optional_ - Maximum number of records to return.
* `$filter` - _optional_ - OData filter expression.
* `api-version` - _required_ - Client Api Version.

### Deletes an existing remediation at management group scope.

#### Input Parameters
* `managementGroupsNamespace` - _required_ - The namespace for Microsoft Management RP; only "Microsoft.Management" is allowed.
    Possible values: Microsoft.Management.
* `managementGroupId` - _required_ - Management group ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Gets an existing remediation at management group scope.

#### Input Parameters
* `managementGroupsNamespace` - _required_ - The namespace for Microsoft Management RP; only "Microsoft.Management" is allowed.
    Possible values: Microsoft.Management.
* `managementGroupId` - _required_ - Management group ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Creates or updates a remediation at management group scope.

#### Input Parameters
* `managementGroupsNamespace` - _required_ - The namespace for Microsoft Management RP; only "Microsoft.Management" is allowed.
    Possible values: Microsoft.Management.
* `managementGroupId` - _required_ - Management group ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Cancels a remediation at management group scope.

#### Input Parameters
* `managementGroupsNamespace` - _required_ - The namespace for Microsoft Management RP; only "Microsoft.Management" is allowed.
    Possible values: Microsoft.Management.
* `managementGroupId` - _required_ - Management group ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Gets all deployments for a remediation at management group scope.

#### Input Parameters
* `managementGroupsNamespace` - _required_ - The namespace for Microsoft Management RP; only "Microsoft.Management" is allowed.
    Possible values: Microsoft.Management.
* `managementGroupId` - _required_ - Management group ID.
* `remediationName` - _required_ - The name of the remediation.
* `$top` - _optional_ - Maximum number of records to return.
* `api-version` - _required_ - Client Api Version.

### Gets all remediations for the subscription.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `$top` - _optional_ - Maximum number of records to return.
* `$filter` - _optional_ - OData filter expression.
* `api-version` - _required_ - Client Api Version.

### Deletes an existing remediation at subscription scope.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Gets an existing remediation at subscription scope.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Creates or updates a remediation at subscription scope.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Cancels a remediation at subscription scope.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Gets all deployments for a remediation at subscription scope.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `remediationName` - _required_ - The name of the remediation.
* `$top` - _optional_ - Maximum number of records to return.
* `api-version` - _required_ - Client Api Version.

### Gets all remediations for the subscription.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group name.
* `$top` - _optional_ - Maximum number of records to return.
* `$filter` - _optional_ - OData filter expression.
* `api-version` - _required_ - Client Api Version.

### Deletes an existing remediation at resource group scope.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group name.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Gets an existing remediation at resource group scope.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group name.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Creates or updates a remediation at resource group scope.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group name.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Cancels a remediation at resource group scope.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group name.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Gets all deployments for a remediation at resource group scope.

#### Input Parameters
* `subscriptionId` - _required_ - Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group name.
* `remediationName` - _required_ - The name of the remediation.
* `$top` - _optional_ - Maximum number of records to return.
* `api-version` - _required_ - Client Api Version.

### Gets all remediations for a resource.

#### Input Parameters
* `resourceId` - _required_ - Resource ID.
* `$top` - _optional_ - Maximum number of records to return.
* `$filter` - _optional_ - OData filter expression.
* `api-version` - _required_ - Client Api Version.

### Deletes an existing remediation at individual resource scope.

#### Input Parameters
* `resourceId` - _required_ - Resource ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Gets an existing remediation at resource scope.

#### Input Parameters
* `resourceId` - _required_ - Resource ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Creates or updates a remediation at resource scope.

#### Input Parameters
* `resourceId` - _required_ - Resource ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Cancel a remediation at resource scope.

#### Input Parameters
* `resourceId` - _required_ - Resource ID.
* `remediationName` - _required_ - The name of the remediation.
* `api-version` - _required_ - Client Api Version.

### Gets all deployments for a remediation at resource scope.

#### Input Parameters
* `resourceId` - _required_ - Resource ID.
* `remediationName` - _required_ - The name of the remediation.
* `$top` - _optional_ - Maximum number of records to return.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-policyinsights-remediations-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
