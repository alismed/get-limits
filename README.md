## Get Salesforce Limits

Lists information about limits in Salesforce org

Using [Postman](https://www.getpostman.com/) to lists information about Salesforce limits with [rest api](https://cnt.prd.itau/blogs/8d942221-ab88-4f33-86ba-1fa88a0229b6/entry/Rest_API).
 
 This use OAuth 2.0 protocol and [connected app](https://help.salesforce.com/articleView?id=connected_app_overview.htm&type=5) to authenticate before consume the api.


### Environments

 In the environment file is necessary define a few key to authenticate.

 * baseUrl
 * clientId
 * clientSecret
 * userName
 * password
 * securityToken
 * apiVersion


### Tests

 It is possible to run the collection to execute the Test Suite like

 * Result Status code is 200
 * Results contains Access Token
 * Results contains Instance url
 * Results in JSON format contains a especific value
 * Results contains a especific token type
 * Global Variable is present
 * Global Variable API Version is present
 * Results in JSON format contains DailyApiRequests
 * Results in JSON format contains SingleEmail
 * Results in JSON format contains MassEmail
 * File Storage Remaining is higher than 25%
 * Data Storage Remaining is higher than 25%
 * Daily Api Requests remaining is less than 20%
 * Daily Async Apex Executions remaning is less than 25%
 * Daily Bulk Api Requests remaning is less than 25%
 * Daily Generic Streaming Api Events remaning is less than 25%
 * Daily Streaming Api Events remaning is less than 25%
 * Daily Workflow Emails remaning is less than 25%
 * Mass Email remaning is less than 25%
 * Single Email remaning is less than 25%
 * Permission Sets remaning is less than 25%
 * Permission Sets Create Custom remaning is less than 25%

