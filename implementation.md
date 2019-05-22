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

<h2 id="content-negotiation">Content Negociation</h2>
<h2 id="document-structure">Document Structure</h2>
    <h3 id="document-top-level">Top Level</h3>
    <h3 id="document-resource-objects">Resource Objects</h3>
        <h4 id="document-resource-object-identification">Identification</h4>
        <h4 id="document-resource-object-fields">Fields</h4>
        <h4 id="document-resource-object-attributes">Attributes</h4>
        <h4 id="document-resource-object-relationships">Relationships</h4>
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
