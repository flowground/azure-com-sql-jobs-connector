# ![LOGO](logo.png) SqlManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SqlManagementClient API (version 2017-03-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-jobs/2017-03-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:39:05+03:00

## API Description

The Azure SQL Database management API provides a RESTful set of web APIs that interact with Azure SQL Database services to manage your databases. The API enables users to create, retrieve, update, and delete databases, servers, and other entities.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets a list of job agents in a server.

*Tags:* `JobAgents`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Deletes a job agent.

*Tags:* `JobAgents`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent to be deleted.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a job agent.

*Tags:* `JobAgents`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent to be retrieved.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Updates a job agent.

*Tags:* `JobAgents`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent to be updated.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Creates or updates a job agent.

*Tags:* `JobAgents`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent to be created or updated.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a list of jobs credentials.

*Tags:* `JobCredentials`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Deletes a job credential.

*Tags:* `JobCredentials`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `credentialName` - _required_ - The name of the credential.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a jobs credential.

*Tags:* `JobCredentials`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `credentialName` - _required_ - The name of the credential.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Creates or updates a job credential.

*Tags:* `JobCredentials`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `credentialName` - _required_ - The name of the credential.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Lists all executions in a job agent.

*Tags:* `JobExecutions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `createTimeMin` - _optional_ - If specified, only job executions created at or after the specified time are included.
* `createTimeMax` - _optional_ - If specified, only job executions created before the specified time are included.
* `endTimeMin` - _optional_ - If specified, only job executions completed at or after the specified time are included.
* `endTimeMax` - _optional_ - If specified, only job executions completed before the specified time are included.
* `isActive` - _optional_ - If specified, only active or only completed job executions are included.
* `$skip` - _optional_ - The number of elements in the collection to skip.
* `$top` - _optional_ - The number of elements to return from the collection.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a list of jobs.

*Tags:* `Jobs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Deletes a job.

*Tags:* `Jobs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to delete.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a job.

*Tags:* `Jobs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Creates or updates a job.

*Tags:* `Jobs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Lists a job's executions.

*Tags:* `JobExecutions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `createTimeMin` - _optional_ - If specified, only job executions created at or after the specified time are included.
* `createTimeMax` - _optional_ - If specified, only job executions created before the specified time are included.
* `endTimeMin` - _optional_ - If specified, only job executions completed at or after the specified time are included.
* `endTimeMax` - _optional_ - If specified, only job executions completed before the specified time are included.
* `isActive` - _optional_ - If specified, only active or only completed job executions are included.
* `$skip` - _optional_ - The number of elements in the collection to skip.
* `$top` - _optional_ - The number of elements to return from the collection.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a job execution.

*Tags:* `JobExecutions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job.
* `jobExecutionId` - _required_ - The id of the job execution
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Creates or updates a job execution.

*Tags:* `JobExecutions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `jobExecutionId` - _required_ - The job execution id to create the job execution under.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Requests cancellation of a job execution.

*Tags:* `JobExecutions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job.
* `jobExecutionId` - _required_ - The id of the job execution to cancel.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Lists the step executions of a job execution.

*Tags:* `JobStepExecutions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `jobExecutionId` - _required_ - The id of the job execution
* `createTimeMin` - _optional_ - If specified, only job executions created at or after the specified time are included.
* `createTimeMax` - _optional_ - If specified, only job executions created before the specified time are included.
* `endTimeMin` - _optional_ - If specified, only job executions completed at or after the specified time are included.
* `endTimeMax` - _optional_ - If specified, only job executions completed before the specified time are included.
* `isActive` - _optional_ - If specified, only active or only completed job executions are included.
* `$skip` - _optional_ - The number of elements in the collection to skip.
* `$top` - _optional_ - The number of elements to return from the collection.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a step execution of a job execution.

*Tags:* `JobStepExecutions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `jobExecutionId` - _required_ - The unique id of the job execution
* `stepName` - _required_ - The name of the step.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Lists the target executions of a job step execution.

*Tags:* `JobTargetExecutions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `jobExecutionId` - _required_ - The id of the job execution
* `stepName` - _required_ - The name of the step.
* `createTimeMin` - _optional_ - If specified, only job executions created at or after the specified time are included.
* `createTimeMax` - _optional_ - If specified, only job executions created before the specified time are included.
* `endTimeMin` - _optional_ - If specified, only job executions completed at or after the specified time are included.
* `endTimeMax` - _optional_ - If specified, only job executions completed before the specified time are included.
* `isActive` - _optional_ - If specified, only active or only completed job executions are included.
* `$skip` - _optional_ - The number of elements in the collection to skip.
* `$top` - _optional_ - The number of elements to return from the collection.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a target execution.

*Tags:* `JobTargetExecutions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `jobExecutionId` - _required_ - The unique id of the job execution
* `stepName` - _required_ - The name of the step.
* `targetId` - _required_ - The target id.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Lists target executions for all steps of a job execution.

*Tags:* `JobTargetExecutions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `jobExecutionId` - _required_ - The id of the job execution
* `createTimeMin` - _optional_ - If specified, only job executions created at or after the specified time are included.
* `createTimeMax` - _optional_ - If specified, only job executions created before the specified time are included.
* `endTimeMin` - _optional_ - If specified, only job executions completed at or after the specified time are included.
* `endTimeMax` - _optional_ - If specified, only job executions completed before the specified time are included.
* `isActive` - _optional_ - If specified, only active or only completed job executions are included.
* `$skip` - _optional_ - The number of elements in the collection to skip.
* `$top` - _optional_ - The number of elements to return from the collection.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Starts an elastic job execution.

*Tags:* `JobExecutions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets all job steps for a job's current version.

*Tags:* `JobSteps`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Deletes a job step. This will implicitly create a new job version.

*Tags:* `JobSteps`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job.
* `stepName` - _required_ - The name of the job step to delete.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a job step in a job's current version.

*Tags:* `JobSteps`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job.
* `stepName` - _required_ - The name of the job step.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Creates or updates a job step. This will implicitly create a new job version.

*Tags:* `JobSteps`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job.
* `stepName` - _required_ - The name of the job step.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets all versions of a job.

*Tags:* `JobVersions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a job version.

*Tags:* `JobVersions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job.
* `jobVersion` - _required_ - The version of the job to get.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets all job steps in the specified job version.

*Tags:* `JobSteps`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job to get.
* `jobVersion` - _required_ - The version of the job to get.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets the specified version of a job step.

*Tags:* `JobSteps`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `jobName` - _required_ - The name of the job.
* `jobVersion` - _required_ - The version of the job to get.
* `stepName` - _required_ - The name of the job step.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets all target groups in an agent.

*Tags:* `JobTargetGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Deletes a target group.

*Tags:* `JobTargetGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `targetGroupName` - _required_ - The name of the target group.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a target group.

*Tags:* `JobTargetGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `targetGroupName` - _required_ - The name of the target group.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Creates or updates a target group.

*Tags:* `JobTargetGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `jobAgentName` - _required_ - The name of the job agent.
* `targetGroupName` - _required_ - The name of the target group.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-jobs-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
