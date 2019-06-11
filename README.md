# ![LOGO](logo.png) BlueprintClient **flow**ground Connector

## Description

A generated **flow**ground connector for the BlueprintClient API (version 2018-11-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/blueprint-assignmentOperation/2018-11-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:13:46+03:00

## API Description

Azure Blueprints Client provides access to blueprint definitions, assignments, and artifacts, and related blueprint operations.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List operations for given blueprint assignment within a subscription.

*Tags:* `AssignmentOperations`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `assignmentName` - _required_ - Name of the blueprint assignment.

### Get a blueprint assignment operation.

*Tags:* `AssignmentOperations`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `assignmentName` - _required_ - Name of the blueprint assignment.
* `assignmentOperationName` - _required_ - Name of the blueprint assignment operation.

## License

**flow**ground :- Telekom iPaaS / azure-com-blueprint-assignment-operation-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
