# ![LOGO](logo.png) IotCentralClient **flow**ground Connector

## Description

A generated **flow**ground connector for the IotCentralClient API (version 2018-09-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/iotcentral/2018-09-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:14+03:00

## API Description

Use this API to manage IoT Central Applications in your Azure subscription.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available IoT Central application REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The version of the API.

### Get all IoT Central Applications in a subscription.

*Tags:* `Apps`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.

### Check if an IoT Central application name is available.

*Tags:* `Apps`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.

### Check if an IoT Central application subdomain is available.

*Tags:* `Apps`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.

### Get all the IoT Central Applications in a resource group.

*Tags:* `Apps`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the IoT Central application.

### Delete an IoT Central application.

*Tags:* `Apps`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the IoT Central application.
* `resourceName` - _required_ - The ARM resource name of the IoT Central application.

### Get the metadata of an IoT Central application.

*Tags:* `Apps`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the IoT Central application.
* `resourceName` - _required_ - The ARM resource name of the IoT Central application.

### Update the metadata of an IoT Central application.

*Tags:* `Apps`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the IoT Central application.
* `resourceName` - _required_ - The ARM resource name of the IoT Central application.

### Create or update the metadata of an IoT Central application. The usual pattern to modify a property is to retrieve the IoT Central application metadata and security metadata, and then combine them with the modified values in a new body to update the IoT Central application.

*Tags:* `Apps`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the IoT Central application.
* `resourceName` - _required_ - The ARM resource name of the IoT Central application.

## License

**flow**ground :- Telekom iPaaS / azure-com-iotcentral-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
