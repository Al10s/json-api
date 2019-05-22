# Implementation

===============

## Progress (0%)

[Source of JSON:API spec 1.0](https://jsonapi.org/format/1.0/)

* :heavy_multiplication_x: [Content Negociation](#content-negotiation) ([Spec](https://jsonapi.org/format/1.0/#content-negotiation))
* :heavy_multiplication_x: [Document Structure](#document-structure) ([Spec](https://jsonapi.org/format/1.0/#document-structure))
    * :heavy_multiplication_x: [Top Level](#document-top-level) ([Spec](https://jsonapi.org/format/1.0/#document-top-level))
    * :heavy_multiplication_x: [Resource Objects](#document-resource-objects) ([Spec](https://jsonapi.org/format/1.0/#document-resource-objects))
        * :heavy_multiplication_x: [Identification](#document-resource-object-identification) ([Spec](https://jsonapi.org/format/1.0/#document-resource-object-identification))
        * :heavy_multiplication_x: [Fields](#document-resource-object-fields) ([Spec](https://jsonapi.org/format/1.0/#document-resource-object-fields))
        * :heavy_multiplication_x: [Attributes](#document-resource-object-attributes) ([Spec](https://jsonapi.org/format/1.0/#document-resource-object-attributes))
        * :heavy_multiplication_x: [Relationships](#document-resource-object-relationships) ([Spec](https://jsonapi.org/format/1.0/#document-resource-object-relationships))
        * :heavy_multiplication_x: [Related Resource Links](#document-resource-object-related-resource-links) ([Spec](https://jsonapi.org/format/1.0/#document-resource-object-related-resource-links))
        * :heavy_multiplication_x: [Resource Linkage](#document-resource-object-resource-linkage) ([Spec](https://jsonapi.org/format/1.0/#document-resource-object-resource-linkage))
        * :heavy_multiplication_x: [Resource Links](#document-resource-object-resource-links) ([Spec](https://jsonapi.org/format/1.0/#document-resource-object-resource-links))
    * :heavy_multiplication_x: [Resource Identifier Objects](#document-resource-identifier-objects) ([Spec](https://jsonapi.org/format/1.0/#document-resource-identifier-objects))
    * :heavy_multiplication_x: [Compound Documents](#document-compound-documents) ([Spec](https://jsonapi.org/format/1.0/#document-compound-documents))
    * :heavy_multiplication_x: [Meta Information](#document-meta) ([Spec](https://jsonapi.org/format/1.0/#document-meta))
    * :heavy_multiplication_x: [Links](#document-links) ([Spec](https://jsonapi.org/format/1.0/#document-links))
    * :heavy_multiplication_x: [JSON:API Object](#document-jsonapi-object) ([Spec](https://jsonapi.org/format/1.0/#document-jsonapi-object))
    * :heavy_multiplication_x: [Member Names](#document-member-names) ([Spec](https://jsonapi.org/format/1.0/#document-member-names))
        * :heavy_multiplication_x: [Allowed Characters](#document-member-names-allowed-characters) ([Spec](https://jsonapi.org/format/1.0/#document-member-names-allowed-characters))
        * :heavy_multiplication_x: [Reserved Characters](#document-member-names-reserved-characters) ([Spec](https://jsonapi.org/format/1.0/#document-member-names-reserved-characters))
* :heavy_multiplication_x: [Fetching Data](#fetching) ([Spec](https://jsonapi.org/format/1.0/#fetching))
    * :heavy_multiplication_x: [Fetching Resources](#fetching-resources) ([Spec](https://jsonapi.org/format/1.0/#fetching-resources))
        * :heavy_multiplication_x: [Responses](#fetching-resources-responses) ([Spec](https://jsonapi.org/format/1.0/#fetching-resources-responses))
    * :heavy_multiplication_x: [Fetching Relationships](#fetching-relationships) ([Spec](https://jsonapi.org/format/1.0/#fetching-relationships))
        * :heavy_multiplication_x: [Responses](#fetching-relationships-responses) ([Spec](https://jsonapi.org/format/1.0/#fetching-relationships-responses))
    * :heavy_multiplication_x: [Inclusion of Related Resources](#fetching-includes) ([Spec](https://jsonapi.org/format/1.0/#fetching-includes))
    * :heavy_multiplication_x: [Sparse Fieldsets](#fetching-sparse-fieldsets) ([Spec](https://jsonapi.org/format/1.0/#fetching-sparse-fieldsets))
    * :heavy_multiplication_x: [Sorting](#fetching-sorting) ([Spec](https://jsonapi.org/format/1.0/#fetching-sorting))
    * :heavy_multiplication_x: [Pagination](#fetching-pagination) ([Spec](https://jsonapi.org/format/1.0/#fetching-pagination))
    * :heavy_multiplication_x: [Filtering](#fetching-filtering) ([Spec](https://jsonapi.org/format/1.0/#fetching-filtering))
* :heavy_multiplication_x: [Creating, Updating and Deleting Resources](#crud) ([Spec](https://jsonapi.org/format/1.0/#crud))
    * :heavy_multiplication_x: [Creating Resources](#crud-creating) ([Spec](https://jsonapi.org/format/1.0/#crud-creating))
        * :heavy_multiplication_x: [Client-Generated IDs](#crud-creating-client-ids) ([Spec](https://jsonapi.org/format/1.0/#crud-creating-client-ids))
        * :heavy_multiplication_x: [Responses](#crud-creating-responses) ([Spec](https://jsonapi.org/format/1.0/#crud-creating-responses))
    * :heavy_multiplication_x: [Updating Resources](#crud-updating) ([Spec](https://jsonapi.org/format/1.0/#crud-updating))
        * :heavy_multiplication_x: [Updating a Resource's Attributes](#crud-updating-resource-attributes) ([Spec](https://jsonapi.org/format/1.0/#crud-updating-resource-attributes))
        * :heavy_multiplication_x: [Updating a Resource's Relationships](#crud-updating-resource-relationships) ([Spec](https://jsonapi.org/format/1.0/#crud-updating-resource-relationships))
        * :heavy_multiplication_x: [Responses](#crud-updating-responses) ([Spec](https://jsonapi.org/format/1.0/#crud-updating-responses))
    * :heavy_multiplication_x: [Updating Relationships](#crud-updating-relationships) ([Spec](https://jsonapi.org/format/1.0/#crud-updating-relationships))
        * :heavy_multiplication_x: [Updating To-One Relationships](#crud-updating-to-one-relationships) ([Spec](https://jsonapi.org/format/1.0/#crud-updating-to-one-relationships))
        * :heavy_multiplication_x: [Updating To-Many Relationships](#crud-updating-to-many-relationships) ([Spec](https://jsonapi.org/format/1.0/#crud-updating-to-many-relationships))
        * :heavy_multiplication_x: [Responses](#crud-updating-relationships-responses) ([Spec](https://jsonapi.org/format/1.0/#crud-updating-relationships-responses))
    * :heavy_multiplication_x: [Deleting Resources](#crud-deleting) ([Spec](https://jsonapi.org/format/1.0/#crud-deleting))
        * :heavy_multiplication_x: [Responses](#crud-deleting-responses) ([Spec](https://jsonapi.org/format/1.0/#crud-deleting-responses))
* :heavy_multiplication_x: [Query Parameters](#query-parameters) ([Spec](https://jsonapi.org/format/1.0/#query-parameters))
* :heavy_multiplication_x: [Errors](#errors) ([Spec](https://jsonapi.org/format/1.0/#errors))
    * :heavy_multiplication_x: [Processing Errors](#errors-processing) ([Spec](https://jsonapi.org/format/1.0/#errors-processing))
    * :heavy_multiplication_x: [Error Objects](#error-objects) ([Spec](https://jsonapi.org/format/1.0/#error-objects))



<h2 id="content-negotiation"> :heavy_multiplication_x: Content Negociation</h2>

* `Servers MUST send all JSON:API data in response documents with the header Content-Type: application/vnd.api+json without any media type parameters.`

 :heavy_multiplication_x: The response header `Content-Type` SHOULD be `application/vnd.api+json`.

 :heavy_multiplication_x: The response header `Content-Type` MAY change according to the request `Accept` header.

 :heavy_multiplication_x: We MAY allow the user to change it for more flexibility.

* `Servers MUST respond with a 415 Unsupported Media Type status code if a request specifies the header Content-Type: application/vnd.api+json with any media type parameters.`

 :heavy_multiplication_x: The server SHOULD return a 415 error if the request specifies a `Content-Type` header other than `application/vnd.api+json`

 :heavy_multiplication_x: We MAY allow the user to change it for more flexibility.

* `Servers MUST respond with a 406 Not Acceptable status code if a request’s Accept header contains the JSON:API media type and all instances of that media type are modified with media type parameters.`

 :heavy_multiplication_x: The server SHOULD return a 406 error if the request specifies an `Accept` header containing only parameterized instances of `application/vnd.api+json`.

 :heavy_multiplication_x: The server MAY accept a query with another `Accept` header as long as this media type is supported (`application/json`).



<h2 id="document-structure"> :heavy_multiplication_x: Document Structure</h2>


<h3 id="document-top-level"> :heavy_multiplication_x: Top Level</h3>

* `A document MUST contain at least one of the following top-level members : data, errors, meta`

 :heavy_multiplication_x: A document MUST contain at least one of the following top-level members: `data`, `errors`, `meta`

* `The members data and errors MUST NOT coexist in the same document.`

 :heavy_multiplication_x: The members `data` and `errors` MUST NOT coexist in the same document.

* `A document MAY contain any of these top-level members: jsonapi, links, included.`

 :heavy_multiplication_x: A document MAY contain any of these top-level members: `jsonapi`, `links`, `included`.

* `If a document does not contain a top-level data key, the included member MUST NOT be present either.`

 :heavy_multiplication_x: A document MUST NOT contain a top-level `included` member if there is no `data` top-level member.

* `The top-level links object MAY contain the following members: self, related, first, last, prev, next`

 :heavy_multiplication_x: The top-level links object MAY contain the following members: `self`, `related`, `first`, `last`, `prev`, `next`

* `The document’s "primary data" is a representation of the resource or collection of resources targeted by a request.`

 :heavy_multiplication_x: For requests that target a single resource, the `data` member MUST contain one of the following:
    * :heavy_multiplication_x: A single resource object
    * :heavy_multiplication_x: A single resource identifier object
    * :heavy_multiplication_x: `null`

 :heavy_multiplication_x: For requests that target resource collections, the `data` member MUST contain one of the following:
    * :heavy_multiplication_x: An array of resource objects
    * :heavy_multiplication_x: An array of resource identifier objects
    * :heavy_multiplication_x: `[]`


<h3 id="document-resource-objects"> :heavy_multiplication_x: Resource Objects</h3>

* `A resource object MUST contain at least the following top-level members: id, type. Exception: The id member is not required when the resource object originates at the client and represents a new resource to be created on the server.`

 :heavy_multiplication_x: A resource object MUST contain a `type` member.

 :heavy_multiplication_x: A resource object MUST contain an `id` member, except for creation requests, where it MAY contain one.

* `In addition, a resource object MAY contain any of these top-level members: attributes, relationships, links, meta`

 :heavy_multiplication_x: A resource object MAY contain the following members: `attributes`, `relationships`, `links`, `meta`

<h4 id="document-resource-object-identification"> :heavy_multiplication_x: Identification</h4>

* `Every resource object MUST contain an id member and a type member. The values of the id and type members MUST be strings.`

 :heavy_multiplication_x: Every resource object MUST contain the following string members : `id`, `type`.

* `The values of type members MUST adhere to the same constraints as member names.`

 :heavy_multiplication_x: The `type` members have the same constraints as [member names](#document-member-names).

<h4 id="document-resource-object-fields"> :heavy_multiplication_x: Fields</h4>

* `Fields for a resource object MUST share a common namespace with each other and with type and id. In other words, a resource can not have an attribute and relationship with the same name, nor can it have an attribute or relationship named type or id.`

 :heavy_multiplication_x: An attribute or a relationship MUST NOT have the same name as another attribute or relationship.

 :heavy_multiplication_x: An attribute or a relationship MUST NOT have the following names: `id`, `type`.

<h4 id="document-resource-object-attributes"> :heavy_multiplication_x: Attributes</h4>

* `The value of the attributes key MUST be an object (an "attributes object").`

 :heavy_multiplication_x: The value of the `attributes` key MUST be an object.

* `Attributes may contain any valid JSON value.`

 :heavy_multiplication_x: The value of an attribute MUST be a valid JSON value.

* `Complex data structures involving JSON objects and arrays are allowed as attribute values. However, any object that constitutes or is contained in an attribute MUST NOT contain a relationships or links member, as those members are reserved by this specification for future use.`

 :heavy_multiplication_x: An attribute MUST NOT contain the following members: `relationships`, `links`.

* `Although has-one foreign keys (e.g. author_id) are often stored internally alongside other information to be represented in a resource object, these keys SHOULD NOT appear as attributes.`

 :heavy_multiplication_x: An attribute MUST NOT be an internal relationship.

<h4 id="document-resource-object-relationships"> :heavy_multiplication_x: Relationships</h4>

* `The value of the relationships key MUST be an object (a "relationships object").`

 :heavy_multiplication_x: The value of the `relationships` key MUST be an object.

* `Relationships may be to-one or to-many.`

 :heavy_multiplication_x: The value of the `data` member of a relationship MUST be one of the following:
    * :heavy_multiplication_x: A single resource identifier object
    * :heavy_multiplication_x: An array of resource identifier objects

*  `A "relationship object" MUST contain at least one of the following:`
    * `links: a links object containing at least one of the following:`
        * `self: a link for the relationship itself (a "relationship link"). This link allows the client to directly manipulate the relationship. For example, removing an author through an article’s relationship URL would disconnect the person from the article without deleting the people resource itself. When fetched successfully, this link returns the linkage for the related resources as its primary data. (See Fetching Relationships.)`
        * `related: a related resource link`
    * `data: resource linkage`
    * `meta: a meta object that contains non-standard meta-information about the relationship.`

 :heavy_multiplication_x: A relationship object MUST contain at least one of the following members:
    *  :heavy_multiplication_x: `links`, that MUST contain at least one of the following members:
        * `self`
        * `related`
    * :heavy_multiplication_x: `data`
    * :heavy_multiplication_x: `meta`

* `A relationship object that represents a to-many relationship MAY also contain pagination links under the links member, as described below. Any pagination links in a relationship object MUST paginate the relationship data, not the related resources.`

<h4 id="document-resource-object-related-resource-links">Related Resource Links</h4>

<h4 id="document-resource-object-resource-linkage">Resource Linkage</h4>

<h4 id="document-resource-object-resource-links">Resource Links</h4>


<h3 id="document-resource-identifier-objects">Resource Identifier Objects</h3>


<h3 id="document-compound-documents">Compound Documents</h3>


<h3 id="document-meta">Meta Information</h3>


<h3 id="document-links">Links</h3>


<h3 id="document-jsonapi-object">JSON:API Object</h3>


<h3 id="document-member-names">Member Names</h3>

<h4 id="document-member-names-allowed-characters">Allowed Characters</h4>

<h4 id="document-member-names-reserved-characters">Reserved Characters</h4>



<h2 id="fetching">Fetching Data</h2>


<h3 id="fetching-resources">Fetching Resources</h3>

<h4 id="fetching-resources-responses">Responses</h4>


<h3 id="fetching-relationships">Fetching Relationships</h3>

<h4 id="fetching-relationships-responses">Responses</h4>


<h3 id="fetching-includes">Inclusion of Related Resources</h3>


<h3 id="fetching-sparse-fieldsets">Sparse Fieldsets</h3>


<h3 id="fetching-sorting">Sorting</h3>


<h3 id="fetching-pagination">Pagination</h3>


<h3 id="fetching-filtering">Filtering</h3>



<h2 id="crud">Creating, Updating and Deleting Resources</h2>


<h3 id="crud-creating">Creating Resources</h3>

<h4 id="crud-creating-client-ids">Client-Generated IDs</h4>

<h4 id="crud-creating-responses">Responses</h4>


<h3 id="crud-updating">Updating Resources</h3>

<h4 id="crud-updating-resource-attributes">Updating a Resource's Attributes</h4>

<h4 id="crud-updating-resource-relationships">Updating a Resource's Relationships</h4>

<h4 id="crud-updating-responses">Responses</h4>


<h3 id="crud-updating-relationships">Updating Relationships</h3>

<h4 id="crud-updating-to-one-relationships">Updating To-One Relationships</h4>

<h4 id="crud-updating-to-many-relationships">Updating To-Many Relationships</h4>

<h4 id="crud-updating-relationships-responses">Responses</h4>


<h3 id="crud-deleting">Deleting Resources</h3>

<h4 id="crud-deleting-responses">Responses</h4>



<h2 id="query-parameters">Query Parameters</h2>



<h2 id="errors">Errors</h2>


<h3 id="errors-processing">Processing Errors</h3>


<h3 id="error-objects">Error Objects</h3>
