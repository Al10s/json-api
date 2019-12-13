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

```markdown
Servers **MUST** send all JSON:API data in response documents with the header
`Content-Type: application/vnd.api+json` without any media type parameters.
```

:heavy_multiplication_x: The response header `Content-Type` **SHOULD** be `application/vnd.api+json`.

:heavy_multiplication_x: The response header `Content-Type` **MAY** change according to the request `Accept` header.

:heavy_multiplication_x: We **MAY** allow the user to change it for more flexibility.

```markdown
Servers **MUST** respond with a `415 Unsupported Media Type` status code if
a request specifies the header `Content-Type: application/vnd.api+json`
with any media type parameters.
```

:heavy_multiplication_x: The server **SHOULD** respond a `415 Unsupported Media Type` status code, with an error, if the request specifies a `Content-Type` header other than `application/vnd.api+json`

:heavy_multiplication_x: We **MAY** allow the user to change it for more flexibility.

```markdown
Servers **MUST** respond with a `406 Not Acceptable` status code if a
request's `Accept` header contains the JSON:API media type and all instances
of that media type are modified with media type parameters.
```

:heavy_multiplication_x: The server **SHOULD** respond a `406 Not Acceptable` status code, with an error, if the request specifies an `Accept` header containing only parameterized instances of `application/vnd.api+json`.

:heavy_multiplication_x: The server **MAY** accept a query with another `Accept` header as long as this media type is supported (`application/json`).



<h2 id="document-structure"> :heavy_multiplication_x: Document Structure</h2>


<h3 id="document-top-level"> :heavy_multiplication_x: Top Level</h3>

```markdown
A document **MUST** contain at least one of the following top-level members:

* `data`: the document's "primary data"
* `errors`: an array of [error objects](#errors)
* `meta`: a [meta object][meta] that contains non-standard
  meta-information.
```

:heavy_multiplication_x: A document **MUST** contain at least one of the following top-level members:
* `data`
* `errors`
* `meta`

```markdown
The members `data` and `errors` **MUST NOT** coexist in the same document.
```

:heavy_multiplication_x: The members `data` and `errors` **MUST NOT** coexist in the same document.

```markdown
A document **MAY** contain any of these top-level members:

* `jsonapi`: an object describing the server's implementation
* `links`: a [links object][links] related to the primary data.
* `included`: an array of [resource objects] that are related to the primary
  data and/or each other ("included resources").
```

:heavy_multiplication_x: A document **MAY** contain any of these top-level members:
* `jsonapi`
* `links`
* `included`

```markdown
If a document does not contain a top-level `data` key, the `included` member
**MUST NOT** be present either.
```

:heavy_multiplication_x: A document **MUST NOT** contain a top-level `included` member if there is no `data` top-level member.

```markdown
The top-level [links object][links] **MAY** contain the following members:

* `self`: the [link][links] that generated the current response document.
* `related`: a [related resource link] when the primary data represents a
  resource relationship.
* [pagination] links for the primary data.
```

:heavy_multiplication_x: The top-level links object **MAY** contain the following members:
* `self`
* `related`
* `first`
* `last`
* `prev`
* `next`

```markdown
The document's "primary data" is a representation of the resource or collection
of resources targeted by a request.

Primary data **MUST** be either:

* a single [resource object][resource objects], a single [resource identifier object], or `null`,
  for requests that target single resources
* an array of [resource objects], an array of
  [resource identifier objects][resource identifier object], or
  an empty array (`[]`), for requests that target resource collections
```

:heavy_multiplication_x: For requests that target a single resource, the `data` member **MUST** contain one of the following:
* :heavy_multiplication_x: A single resource object
* :heavy_multiplication_x: A single resource identifier object
* :heavy_multiplication_x: `null`

:heavy_multiplication_x: For requests that target resource collections, the `data` member **MUST** contain one of the following:
* :heavy_multiplication_x: An array of resource objects
* :heavy_multiplication_x: An array of resource identifier objects
* :heavy_multiplication_x: `[]`


<h3 id="document-resource-objects"> :heavy_multiplication_x: Resource Objects</h3>

```markdown
A resource object **MUST** contain at least the following top-level members:

* `id`
* `type`

Exception: The `id` member is not required when the resource object originates at
the client and represents a new resource to be created on the server.
```

:heavy_multiplication_x: A resource object **MUST** contain a `type` member.

:heavy_multiplication_x: A resource object **MUST** contain an `id` member, except for creation requests, where it **MAY** contain one.

```markdown
In addition, a resource object **MAY** contain any of these top-level members:

* `attributes`: an [attributes object][attributes] representing some of the resource's data.
* `relationships`: a [relationships object][relationships] describing relationships between
 the resource and other JSON:API resources.
* `links`: a [links object][links] containing links related to the resource.
* `meta`: a [meta object][meta] containing non-standard meta-information about a
  resource that can not be represented as an attribute or relationship.
```

:heavy_multiplication_x: A resource object **MAY** contain the following members:
* `attributes`
* `relationships`
* `links`
* `meta`

<h4 id="document-resource-object-identification"> :heavy_multiplication_x: Identification</h4>

```markdown
Every [resource object][resource objects] **MUST** contain an `id` member and a `type` member.
The values of the `id` and `type` members **MUST** be strings.
```

:heavy_multiplication_x: Every resource object **MUST** contain the following string members:
* `id`
* `type`

```markdown
The values of `type` members **MUST** adhere to the same constraints as
[member names].
```

:heavy_multiplication_x: The `type` members have the same constraints as [member names](#document-member-names).

<h4 id="document-resource-object-fields"> :heavy_multiplication_x: Fields</h4>

```markdown
Fields for a [resource object][resource objects] **MUST** share a common namespace with each
other and with `type` and `id`. In other words, a resource can not have an
attribute and relationship with the same name, nor can it have an attribute
or relationship named `type` or `id`.
```

:heavy_multiplication_x: An attribute or a relationship **MUST NOT** have the same name as another attribute or relationship.

:heavy_multiplication_x: An attribute or a relationship **MUST NOT** have the following names:
* `id`
* `type`

<h4 id="document-resource-object-attributes"> :heavy_multiplication_x: Attributes</h4>

```markdown
The value of the `attributes` key **MUST** be an object (an "attributes
object"). Members of the attributes object ("attributes") represent information
about the [resource object][resource objects] in which it's defined.
```

:heavy_multiplication_x: The value of the `attributes` key **MUST** be an object.

```markdown
Attributes may contain any valid JSON value.
```

:heavy_multiplication_x: The value of an attribute **MUST** be a valid JSON value.

```markdown
Complex data structures involving JSON objects and arrays are allowed as
attribute values. However, any object that constitutes or is contained in an
attribute **MUST NOT** contain a `relationships` or `links` member, as those
members are reserved by this specification for future use.
```

:heavy_multiplication_x: An attribute **MUST NOT** contain the following members:
* `relationships`
* `links`

```markdown
Although has-one foreign keys (e.g. `author_id`) are often stored internally
alongside other information to be represented in a resource object, these keys
**SHOULD NOT** appear as attributes.
```

:heavy_multiplication_x: An attribute **SHOULD NOT** be an internal relationship.

<h4 id="document-resource-object-relationships"> :heavy_multiplication_x: Relationships</h4>

```markdown
The value of the `relationships` key **MUST** be an object (a "relationships
object"). Members of the relationships object ("relationships") represent
references from the [resource object][resource objects] in which it's defined to other resource
objects.
```

:heavy_multiplication_x: The value of the `relationships` key **MUST** be an object.

```markdown
Relationships may be to-one or to-many.
```

:heavy_multiplication_x: The value of the `data` member of a relationship **MUST** be one of the following:
* :heavy_multiplication_x: `null` for empty to-one relationships.
* :heavy_multiplication_x: An empty array (`[]`) for empty to-many relationships.
* :heavy_multiplication_x: A single resource identifier object for non-empty to-one relationships.
* :heavy_multiplication_x: An array of resource identifier objects for non-empty to-many relationships.

```markdown
A "relationship object" **MUST** contain at least one of the following:

* `links`: a [links object][links] containing at least one of the following:
  * `self`: a link for the relationship itself (a "relationship link"). This
    link allows the client to directly manipulate the relationship. For example,
    removing an `author` through an `article`'s relationship URL would disconnect
    the person from the `article` without deleting the `people` resource itself.
    When fetched successfully, this link returns the [linkage][resource linkage]
    for the related resources as its primary data.
    (See [Fetching Relationships](#fetching-relationships).)
  * `related`: a [related resource link]
* `data`: [resource linkage]
* `meta`: a [meta object][meta] that contains non-standard meta-information about the
  relationship.
```

:heavy_multiplication_x: A relationship object **MUST** contain at least one of the following members:
*  :heavy_multiplication_x: `links`, that **MUST** contain at least one of the following members:
    * :heavy_multiplication_x: `self`
    * :heavy_multiplication_x: `related`
* :heavy_multiplication_x: `data`
* :heavy_multiplication_x: `meta`

```markdown
A relationship object that represents a to-many relationship **MAY** also contain
[pagination] links under the `links` member, as described below. Any
[pagination] links in a relationship object **MUST** paginate the relationship
data, not the related resources.
```

:heavy_multiplication_x: The `links` member of a relationship object **MAY** contain all of the following members:
* `first`
* `last`
* `prev`
* `next`

<h4 id="document-resource-object-related-resource-links"> :heavy_multiplication_x: Related Resource Links</h4>

```markdown
If present, a related resource link **MUST** reference a valid URL, even if the
relationship isn't currently associated with any target resources. Additionally,
a related resource link **MUST NOT** change because its relationship's content
changes.
```

:heavy_multiplication_x: If present, the `related` resource link **MUST** reference a valid URL.

<h4 id="document-resource-object-resource-linkage"> :heavy_multiplication_x: Resource Linkage</h4>

```markdown
Resource linkage **MUST** be represented as one of the following:

* `null` for empty to-one relationships.
* an empty array (`[]`) for empty to-many relationships.
* a single [resource identifier object] for non-empty to-one relationships.
* an array of [resource identifier objects][resource identifier object] for non-empty to-many relationships.
```

(Probable duplicate of `Relationships may be to-one or to-many.` in [Relationships](#document-resource-object-relationships))

<h4 id="document-resource-object-resource-links"> :heavy_multiplication_x: Resource Links</h4>

```markdown
The optional `links` member within each [resource object][resource objects] contains [links]
related to the resource.

If present, this links object **MAY** contain a `self` [link][links] that
identifies the resource represented by the resource object.

A server **MUST** respond to a `GET` request to the specified URL with a
response that includes the resource as the primary data.
```

:heavy_multiplication_x: If present, the `self` member of a `links` resource **MUST** refer to an URL returning the resource data.


<h3 id="document-resource-identifier-objects"> :heavy_multiplication_x: Resource Identifier Objects</h3>

```markdown
A "resource identifier object" **MUST** contain `type` and `id` members.
```

:heavy_multiplication_x: A resource identifier object **MUST** contain the following members:
* `type`
* `id`

```markdown
A "resource identifier object" **MAY** also include a `meta` member, whose value is a [meta] object that
contains non-standard meta-information.
```

:heavy_multiplication_x: A resource identifier object **MAY** contain a `meta` member.


<h3 id="document-compound-documents"> :heavy_multiplication_x: Compound Documents</h3>

```markdown
To reduce the number of HTTP requests, servers **MAY** allow responses that
include related resources along with the requested primary resources. Such
responses are called "compound documents".

In a compound document, all included resources **MUST** be represented as an
array of [resource objects] in a top-level `included` member.
```

:heavy_multiplication_x: The server **MAY** embed related resources in a top-level `included` member.

```markdown
Compound documents require "full linkage", meaning that every included
resource **MUST** be identified by at least one [resource identifier object]
in the same document. These resource identifier objects could either be
primary data or represent resource linkage contained within primary or
included resources.

The only exception to the full linkage requirement is when relationship fields
that would otherwise contain linkage data are excluded via [sparse fieldsets](#fetching-sparse-fieldsets).
```

:heavy_multiplication_x: Every resource of a compound document **MUST** be identified by at least one resource identifier object. The only exception being if the client requested [sparse fieldsets](#fetching-sparse-fieldsets).

```markdown
A [compound document] **MUST NOT** include more than one [resource object][resource objects] for
each `type` and `id` pair.
```

:heavy_multiplication_x: Every resource of a compound document **MUST** be included only once.


<h3 id="document-meta"> :heavy_multiplication_x: Meta Information</h3>

```markdown
Where specified, a `meta` member can be used to include non-standard
meta-information. The value of each `meta` member **MUST** be an object (a
"meta object").

```

:heavy_multiplication_x: The value of each `meta` member **MUST** be an object.

```markdown
Any members **MAY** be specified within `meta` objects.
```

:heavy_multiplication_x: The `meta` member object **MAY** contain any kind of fields.


<h3 id="document-links"> :heavy_multiplication_x: Links</h3>

```markdown
Where specified, a `links` member can be used to represent links. The value
of each `links` member **MUST** be an object (a "links object").
```

:heavy_multiplication_x: The value of each `links` member **MUST** be an object.

```markdown
Each member of a links object is a "link". A link **MUST** be represented as
either:

* a string containing the link's URL.
* <a id="document-links-link-object"></a>an object ("link object") which can
  contain the following members:
  * `href`: a string containing the link's URL.
  * `meta`: a meta object containing non-standard meta-information about the
    link.
```

:heavy_multiplication_x: Each member of the `links` object **MUST** contain one of the following:
* A string representing the URL to the link
* An object which:
    * **MUST** contain a `href` member (A string representing the URL to the link)
    * **MAY** contain a `meta` object


<h3 id="document-jsonapi-object"> :heavy_multiplication_x: JSON:API Object</h3>

```markdown
A JSON:API document **MAY** include information about its implementation
under a top level `jsonapi` member. If present, the value of the `jsonapi`
member **MUST** be an object (a "jsonapi object"). The jsonapi object **MAY**
contain a `version` member whose value is a string indicating the highest JSON
API version supported. This object **MAY** also contain a `meta` member, whose
value is a [meta] object that contains non-standard meta-information.
```

:heavy_multiplication_x: The top-level `jsonapi` member **MAY** be included.

:heavy_multiplication_x: If included, it **MUST** be an object.

:heavy_multiplication_x: This object **MAY** contain a `version` string member.

:heavy_multiplication_x: This object **MAY** contain a `meta` object.


<h3 id="document-member-names"> :heavy_multiplication_x: Member Names</h3>

```markdown
All member names used in a JSON:API document **MUST** be treated as case sensitive
by clients and servers, and they **MUST** meet all of the following conditions:

- Member names **MUST** contain at least one character.
- Member names **MUST** contain only the allowed characters listed below.
- Member names **MUST** start and end with a "globally allowed character",
  as defined below.

To enable an easy mapping of member names to URLs, it is **RECOMMENDED** that
member names use only non-reserved, URL safe characters specified in [RFC 3986](http://tools.ietf.org/html/rfc3986#page-13).
```

:heavy_multiplication_x: Member names **MUST** contain only allowed characters.


<h4 id="document-member-names-allowed-characters"> :heavy_multiplication_x: Allowed Characters</h4>

```markdown
The following "globally allowed characters" **MAY** be used anywhere in a member name:

- U+0061 to U+007A, "a-z"
- U+0041 to U+005A, "A-Z"
- U+0030 to U+0039, "0-9"
- U+0080 and above (non-ASCII Unicode characters; _not recommended, not URL safe_)

Additionally, the following characters are allowed in member names, except as the
first or last character:

- U+002D HYPHEN-MINUS, "-"
- U+005F LOW LINE, "_"
- U+0020 SPACE, " " _(not recommended, not URL safe)_
```

:heavy_multiplication_x: Member names **MUST** contain only allowed characters (Duplicate).

<h4 id="document-member-names-reserved-characters"> :heavy_multiplication_x: Reserved Characters</h4>

```markdown
The following characters **MUST NOT** be used in member names:

- U+002B PLUS SIGN, "+" _(used for ordering)_
- U+002C COMMA, "," _(used as a separator between relationship paths)_
- U+002E PERIOD, "." _(used as a separator within relationship paths)_
- U+005B LEFT SQUARE BRACKET, "[" _(used in sparse fieldsets)_
- U+005D RIGHT SQUARE BRACKET, "]" _(used in sparse fieldsets)_
- U+0021 EXCLAMATION MARK, "!"
- U+0022 QUOTATION MARK, '"'
- U+0023 NUMBER SIGN, "#"
- U+0024 DOLLAR SIGN, "$"
- U+0025 PERCENT SIGN, "%"
- U+0026 AMPERSAND, "&"
- U+0027 APOSTROPHE, "'"
- U+0028 LEFT PARENTHESIS, "("
- U+0029 RIGHT PARENTHESIS, ")"
- U+002A ASTERISK, "&#x2a;"
- U+002F SOLIDUS, "/"
- U+003A COLON, ":"
- U+003B SEMICOLON, ";"
- U+003C LESS-THAN SIGN, "<"
- U+003D EQUALS SIGN, "="
- U+003E GREATER-THAN SIGN, ">"
- U+003F QUESTION MARK, "?"
- U+0040 COMMERCIAL AT, "@"
- U+005C REVERSE SOLIDUS, "&#x5c;"
- U+005E CIRCUMFLEX ACCENT, "^"
- U+0060 GRAVE ACCENT, "&#x60;"
- U+007B LEFT CURLY BRACKET, "{"
- U+007C VERTICAL LINE, "&#x7c;"
- U+007D RIGHT CURLY BRACKET, "}"
- U+007E TILDE, "~"
- U+007F DELETE
- U+0000 to U+001F (C0 Controls)
```

:heavy_multiplication_x: Member names **MUST** contain only allowed characters (Duplicate).



<h2 id="fetching"> :heavy_multiplication_x: Fetching Data</h2>


<h3 id="fetching-resources"> :heavy_multiplication_x: Fetching Resources</h3>

```markdown
A server **MUST** support fetching resource data for every URL provided as:

* a `self` link as part of the top-level links object
* a `self` link as part of a resource-level links object
* a `related` link as part of a relationship-level links object
```

:heavy_multiplication_x: The server **MUST** respond to `GET` requests to the following URLs:
* :heavy_multiplication_x: Collection of resources endpoint
* :heavy_multiplication_x: Resources endpoints
* :heavy_multiplication_x: Resource relationship endpoints

<h4 id="fetching-resources-responses"> :heavy_multiplication_x: Responses</h4>

##### :heavy_multiplication_x: 200 OK

```markdown
A server **MUST** respond to a successful request to fetch an individual
resource or resource collection with a `200 OK` response.
```

:heavy_multiplication_x: The server **MUST** respond to a successful `GET` request on an individual resource or a resource collection with a `200 OK` status code.

```markdown
A server **MUST** respond to a successful request to fetch a resource
collection with an array of [resource objects] or an empty array (`[]`) as
the response document's primary data.
```

:heavy_multiplication_x: The server response to a successful `GET` request on a resource collection **MUST** contain an array `data` member filled with the matching resource collection.

```markdown
A server **MUST** respond to a successful request to fetch an individual
resource with a [resource object][resource objects] or `null` provided as
the response document's primary data.

`null` is only an appropriate response when the requested URL is one that
might correspond to a single resource, but doesn't currently.
```

:heavy_multiplication_x: The server response to a successful `GET` request on an individual resource **MUST** contain an object `data` member filled with the matching resource data.

:heavy_multiplication_x: The server response to a successful `GET` request on an individual resource **MAY** contain a `data` member containing a `null` value, if there is no matching resource.

##### :heavy_multiplication_x: 404 Not Found

```markdown
A server **MUST** respond with `404 Not Found` when processing a request to
fetch a single resource that does not exist, except when the request warrants a
`200 OK` response with `null` as the primary data (as described above).
```

:heavy_multiplication_x: The server response to a `GET` request on an individual resource that does not exist **MUST** have a `404 Not Found` status code.

##### :heavy_multiplication_x: Other responses

```markdown
A server **MAY** respond with other HTTP status codes.
```

:heavy_multiplication_x: The server **MAY** respond to a `GET` request on an individual resource or a resource collection with other HTTP status codes.

```markdown
A server **MAY** include [error details] with error responses.
```

:heavy_multiplication_x: The server **MAY** include error details in a response to an errored `GET` request on an individual resource or a resource collection.


<h3 id="fetching-relationships"> :heavy_multiplication_x: Fetching Relationships</h3>

```markdown
A server **MUST** support fetching relationship data for every relationship URL
provided as a `self` link as part of a relationship's `links` object.
```

:heavy_multiplication_x: The server **MUST** respond to `GET` requests to the following URLs:
* :heavy_multiplication_x: Resource relationships linkage endpoints

<h4 id="fetching-relationships-responses"> :heavy_multiplication_x: Responses</h4>

##### :heavy_multiplication_x: 200 OK

```markdown
A server **MUST** respond to a successful request to fetch a relationship
with a `200 OK` response.
```

:heavy_multiplication_x: The server **MUST** respond to a successful `GET` request on a resource relationships linkage with a `200 OK` status code.

```markdown
The primary data in the response document **MUST** match the appropriate
value for [resource linkage], as described above for
[relationship objects][relationships].
```

:heavy_multiplication_x: The server response to a successful `GET` request on a resource relationships linkage **MUST** contain an object `data` member filled with the matching resource linkage data.

```markdown
The top-level [links object][links] **MAY** contain `self` and `related` links,
as described above for [relationship objects][relationships].
```

:heavy_multiplication_x: The server response to a successful `GET` request on a resource relationships linkage **MAY** contain a `links` member.

:question: The [Relationships Objects spec](#document-resource-object-relationships) clearly states that:
```markdown
A "relationship object" **MUST** contain at least one of the following:

* `links`: a [links object][links] containing at least one of the following:
    * `self` [...]
    * `related` [...]
```
Therefore, it states that the `links` object **MUST** contain either `self` or `related`, in contradiction with this part of the spec that makes them optional.

:heavy_multiplication_x: This `links` member **MUST** contain any of the following members:
* `self`
* `related`

##### :heavy_multiplication_x: 404 Not Found

```markdown
A server **MUST** return `404 Not Found` when processing a request to fetch
a relationship link URL that does not exist.
```

:heavy_multiplication_x: The server response to a `GET` request on a relationship of a resource that does not exist (either the resource or the relationship) **MUST** have a `404 Not Found` status code.

##### :heavy_multiplication_x: Other responses

```markdown
A server **MAY** respond with other HTTP status codes.
```

:heavy_multiplication_x: The server **MAY** respond to a `GET` request on a relationship with other HTTP status codes.

```markdown
A server **MAY** include [error details] with error responses.
```

:heavy_multiplication_x: The server **MAY** include error details in a response to an errored `GET` request on a relationship.


<h3 id="fetching-includes"> :heavy_multiplication_x: Inclusion of Related Resources</h3>

```markdown
An endpoint **MAY** return resources related to the primary data by default.
```

:heavy_multiplication_x: The server **MAY** include related resources into an `included` field by default.

```markdown
An endpoint **MAY** also support an `include` request parameter to allow the
client to customize which related resources should be returned.
```

:heavy_multiplication_x: The server **MAY** process an `include` `GET` parameter to know which related resources should be included.

```markdown
If an endpoint does not support the `include` parameter, it **MUST** respond
with `400 Bad Request` to any requests that include it.
```

:heavy_multiplication_x: The server **MUST** return a `400 Bad Request` response if an `include` `GET` parameter is provided, but the endpoint doesn't support it.

```markdown
If an endpoint supports the `include` parameter and a client supplies it,
the server **MUST NOT** include unrequested [resource objects] in the `included`
section of the [compound document].
```

:heavy_multiplication_x: The server **MUST NOT** include unrequested resources if the `include` parameter is provided.

```markdown
The value of the `include` parameter **MUST** be a comma-separated (U+002C
COMMA, ",") list of relationship paths. A relationship path is a dot-separated
(U+002E FULL-STOP, ".") list of [relationship][relationships] names.

If a server is unable to identify a relationship path or does not support
inclusion of resources from a path, it **MUST** respond with 400 Bad Request.
```

:heavy_multiplication_x: The server **MUST** return a `400 Bad Request` response if an `include` `GET` parameter is provided, but isn't well-formated.

```markdown
A server may choose to expose a deeply nested relationship as a direct relationship with an alias.
```

:heavy_multiplication_x: The server **MAY** allow aliases to expose deeply nested relationships as a direct relationship.


<h3 id="fetching-sparse-fieldsets"> :heavy_multiplication_x: Sparse Fieldsets</h3>

```markdown
A client **MAY** request that an endpoint return only specific [fields] in the
response on a per-type basis by including a `fields[TYPE]` parameter.

The value of the `fields` parameter **MUST** be a comma-separated (U+002C
COMMA, ",") list that refers to the name(s) of the fields to be returned.
```

:heavy_multiplication_x: The server **MAY** filter the requested resources fields by using the `fields` parameter.

```markdown
If a client requests a restricted set of [fields] for a given resource type,
an endpoint **MUST NOT** include additional [fields] in resource objects of
that type in its response.
```

:heavy_multiplication_x: The server **MUST NOT** add fields other than the ones requested for this type of resource if a `fields` parameter is provided.


<h3 id="fetching-sorting"> :heavy_multiplication_x: Sorting</h3>

```markdown
A server **MAY** choose to support requests to sort resource collections
according to one or more criteria ("sort fields").
```

:heavy_multiplication_x: The server **MAY** sort requested resources.

```markdown
An endpoint **MAY** support requests to sort the primary data with a `sort`
query parameter. The value for `sort` **MUST** represent sort fields.
```

:heavy_multiplication_x: The server **MAY** support a `sort` parameter to sort requested resources. If provided, the `sort` parameter **MUST** represent the fields to sort.

```markdown
An endpoint **MAY** support multiple sort fields by allowing comma-separated
(U+002C COMMA, ",") sort fields. Sort fields **SHOULD** be applied in the
order specified.
```

:heavy_multiplication_x: The server **MAY** allow sorting on multiple criteria, by using a list of comma-separated fields. In this case, the sorting **SHOULD** be applied in the specified order.

```markdown
The sort order for each sort field **MUST** be ascending unless it is prefixed
with a minus (U+002D HYPHEN-MINUS, "-"), in which case it **MUST** be descending.
```

:heavy_multiplication_x: The sort order **MUST** be ascending by default for each field, and descending if the field name is prefixed with the `-` character.

```markdown
If the server does not support sorting as specified in the query parameter
`sort`, it **MUST** return `400 Bad Request`.
```

:heavy_multiplication_x: The server **MUST** return a `400 Bad Request` response if a `sort` `GET` parameter is provided, but the endpoint doesn't support it.

```markdown
If sorting is supported by the server and requested by the client via query
parameter `sort`, the server **MUST** return elements of the top-level
`data` array of the response ordered according to the criteria specified.
```

:heavy_multiplication_x: If the server supports sorting, the `data` **MUST** be sorted accordingly.

```markdown
The server **MAY** apply default sorting rules to top-level `data` if
request parameter `sort` is not specified.
```

:heavy_multiplication_x: The server **MAY** sort data with a default rule.


<h3 id="fetching-pagination"> :heavy_multiplication_x: Pagination</h3>

```markdown
A server **MAY** choose to limit the number of resources returned in a response
to a subset ("page") of the whole set available.
```

:heavy_multiplication_x: The server **MAY** have a pagination strategy.

```markdown
A server **MAY** provide links to traverse a paginated data set ("pagination
links").
```

:heavy_multiplication_x: If the server has a pagination strategy, it **MAY** provide links to traverse the data set.

```markdown
Pagination links **MUST** appear in the links object that corresponds to a
collection. To paginate the primary data, supply pagination links in the
top-level `links` object. To paginate an included collection returned in
a [compound document], supply pagination links in the corresponding links
object.
```

:heavy_multiplication_x: If provided, the pagination links **MUST** be inside the `links` field.

```markdown
The following keys **MUST** be used for pagination links:

* `first`: the first page of data
* `last`: the last page of data
* `prev`: the previous page of data
* `next`: the next page of data
```

:heavy_multiplication_x: The pagination links **MUST** be associated to the following keys :

* `first`: the first page of data
* `last`: the last page of data
* `prev`: the previous page of data
* `next`: the next page of data

```markdown
Keys **MUST** either be omitted or have a `null` value to indicate that a
particular link is unavailable.
```

:heavy_multiplication_x: If the link is unavailable, its value **SHOULD** be `null`

```markdown
Concepts of order, as expressed in the naming of pagination links, **MUST**
remain consistent with JSON:API's [sorting rules](#fetching-sorting).
```

:heavy_multiplication_x: Pagination links **MUST** follow the sorting rule, if any.

```markdown
The `page` query parameter is reserved for pagination. Servers and clients
**SHOULD** use this key for pagination operations.
```

:heavy_multiplication_x: The key used for pagination **SHOULD** be `page`.

```markdown
> Note: JSON:API is agnostic about the pagination strategy used by a server.
Effective pagination strategies include (but are not limited to):
page-based, offset-based, and cursor-based. The `page` query parameter can
be used as a basis for any of these strategies. For example, a page-based
strategy might use query parameters such as `page[number]` and `page[size]`,
an offset-based strategy might use `page[offset]` and `page[limit]`, while a
cursor-based strategy might use `page[cursor]`.
```

:heavy_multiplication_x: The server **MAY** support the following pagination strategies :

* page-based, using `page[number]` and `page[size]` parameters
* offset-based, using `page[offset]` and `page[limit]` parameters
* cursor-based, using `page[cursor]` parameter


<h3 id="fetching-filtering"> :heavy_multiplication_x: Filtering</h3>

```markdown
The `filter` query parameter is reserved for filtering data. Servers and clients
**SHOULD** use this key for filtering operations.
```

:heavy_multiplication_x: The server **SHOULD** use the `filter` parameter to filter the returned data.


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
