# ![LOGO](logo.png) ApplicationInsightsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApplicationInsightsManagementClient API (version 2017-10-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/applicationinsights-componentFeaturesAndPricing_API/2017-10-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:18+03:00

## API Description

Azure Application Insights client for selecting pricing plans and options.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns the current pricing plan setting for an Application Insights component.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.

### Update current pricing plan for an Application Insights component.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.

### Replace current pricing plan for an Application Insights component.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.

## License

**flow**ground :- Telekom iPaaS / azure-com-applicationinsights-component-features-and-pricing-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
