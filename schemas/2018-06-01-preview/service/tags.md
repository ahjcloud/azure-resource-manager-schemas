# Microsoft.ApiManagement/service/tags template reference
API Version: 2018-06-01-preview
## Template format

To create a Microsoft.ApiManagement/service/tags resource, add the following JSON to the resources section of your template.

```json
{
  "name": "string",
  "type": "Microsoft.ApiManagement/service/tags",
  "apiVersion": "2018-06-01-preview",
  "properties": {
    "displayName": "string"
  }
}
```
## Property values

The following tables describe the values you need to set in the schema.

<a id="Microsoft.ApiManagement/service/tags" />
### Microsoft.ApiManagement/service/tags object
|  Name | Type | Required | Value |
|  ---- | ---- | ---- | ---- |
|  name | string | Yes | Tag identifier. Must be unique in the current API Management service instance. |
|  type | enum | Yes | Microsoft.ApiManagement/service/tags |
|  apiVersion | enum | Yes | 2018-06-01-preview |
|  properties | object | Yes | Properties supplied to Create Tag operation. - [TagContractProperties object](#TagContractProperties) |


<a id="TagContractProperties" />
### TagContractProperties object
|  Name | Type | Required | Value |
|  ---- | ---- | ---- | ---- |
|  displayName | string | Yes | Tag name. |

