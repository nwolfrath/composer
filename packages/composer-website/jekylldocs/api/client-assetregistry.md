---
layout: default
title: AssetRegistry (Client API)
section: api
sidebar: sidebars/accordion-toc0.md
excerpt: The Client, Admin, and Runtime components of Hyperledger Composer
index-order: 1212
---
[Overview](api-doc-index)  -  [Common API](allData#common-api)  -  [Client API](allData#client-api)  -  [Admin API](allData#admin-api)  -  [Runtime API](allData#runtime-api)
# AssetRegistry

The AssetRegistry is used to manage a set of assets stored on the Blockchain.
**Applications should retrieve instances from {@link BusinessNetworkConnection}**

### Details

- **Extends** Registry

- **Module** client



### See also
- See {@link Registry}





## Inherited Method Summary
| Supertype | Name | Returns | Description |
| :-------- | :--- | :-------- | :----------- |
| Registry |[remove](#remove) | `Promise` | Remove an asset with a given type and id from the registry  |
| Registry |[addAll](#addall) | `Promise` | Adds a list of new resources to the registry  |
| Registry |[updateAll](#updateall) | `Promise` | Updates a list of resources in the registry  |
| Registry |[update](#update) | `Promise` | Updates a resource in the registry  |
| Registry |[removeAll](#removeall) | `Promise` | Removes a list of resources from the registry  |
| Registry |[add](#add) | `Promise` | Adds a new resource to the registry  |
| Registry |[getAll](#getall) | `Promise` | Get all of the resources in the registry  |
| Registry |[get](#get) | `Promise` | Get a specific resource in the registry  |
| Registry |[exists](#exists) | `Promise` | Determines whether a specific resource exists in the registry  |
| Registry |[resolveAll](#resolveall) | `Promise` | Get all of the resources in the registry, and resolve all of their relationships to other assets, participants, and transactions  |
| Registry |[resolve](#resolve) | `Promise` | Get a specific resource in the registry, and resolve all of its relationships to other assets, participants, and transactions  |



# Method Details
 

##Inherited methods




## addAll
_Promise addAll(  resources )_


**Inherited from:**  Registry

Adds a list of new resources to the registry.





### Returns
{@link Promise} - A promise that will be resolved when the resource is added to the registry.




### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**resources**|  |*Yes*|The resources to be added to the registry.|











## add
_Promise add( Resource resource )_


**Inherited from:**  Registry

Adds a new resource to the registry.





### Returns
{@link Promise} - A promise that will be resolved when the resource is added to the registry.




### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**resource**| Resource |*Yes*|The resource to be added to the registry.|











## updateAll
_Promise updateAll(  resources )_


**Inherited from:**  Registry

Updates a list of resources in the registry.





### Returns
{@link Promise} - A promise that will be resolved when the resource is added to the registry.




### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**resources**|  |*Yes*|The resources to be updated in the asset registry.|











## update
_Promise update( Resource resource )_


**Inherited from:**  Registry

Updates a resource in the registry.





### Returns
{@link Promise} - A promise that will be resolved when the resource is updated in the registry.




### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**resource**| Resource |*Yes*|The resource to be updated in the registry.|











## removeAll
_Promise removeAll( ;  resources )_


**Inherited from:**  Registry

Removes a list of resources from the registry.





### Returns
{@link Promise} - A promise that will be resolved when the resource is added to the registry.




### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**resources**| ;  |*Yes*|The resources, or the unique identifiers of the resources.|











## remove
_Promise remove( Resource; string resource )_


**Inherited from:**  Registry

Remove an asset with a given type and id from the registry.





### Returns
{@link Promise} - A promise that will be resolved when the resource is removed from the registry.




### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**resource**| Resource; string |*Yes*|The resource, or the unique identifier of the resource.|











## getAll
_Promise getAll(  )_


**Inherited from:**  Registry

Get all of the resources in the registry.





### Returns
{@link Promise} - A promise that will be resolved with an array of JSON objects representing the resources.




### See also






### Parameters

No parameters










## get
_Promise get( string id )_


**Inherited from:**  Registry

Get a specific resource in the registry.





### Returns
{@link Promise} - A promise that will be resolved with a JSON object representing the resource.




### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**id**| string |*Yes*|The unique identifier of the resource.|











## exists
_Promise exists( string id )_


**Inherited from:**  Registry

Determines whether a specific resource exists in the registry.





### Returns
{@link Promise} - A promise that will be resolved with true/false depending on whether the resource exists.




### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**id**| string |*Yes*|The unique identifier of the resource.|











## resolveAll
_Promise resolveAll(  )_


**Inherited from:**  Registry

Get all of the resources in the registry, and resolve all of their relationships to other assets, participants, and transactions. The result is a JavaScript object, and should only be used for visualization purposes. You cannot use the {@link #add add} or {@link #update update} functions with a resolved resource.





### Returns
{@link Promise} - A promise that will be resolved with an array of JavaScript objects representing the resources and all of their resolved relationships.




### See also






### Parameters

No parameters










## resolve
_Promise resolve( string id )_


**Inherited from:**  Registry

Get a specific resource in the registry, and resolve all of its relationships to other assets, participants, and transactions. The result is a JavaScript object, and should only be used for visualization purposes. You cannot use the  {@link #add add} or {@link #update update} functions with a resolved resource.





### Returns
{@link Promise} - A promise that will be resolved with a JavaScript object representing the resource and all of its resolved relationships.




### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**id**| string |*Yes*|The unique identifier of the asset.|








 