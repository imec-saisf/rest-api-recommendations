# HTTP API Design Guide

* [Foundations](foundations/README.md)
  * [REST](foundations/rest.md)
  * [Separate Concerns](foundations/separate-concerns.md)
  * [Require Secure Connections](foundations/require-secure-connections.md)
  * [Allow Versioning in the URL](foundations/allow-versioning-in-url.md)
  * [Support ETags for Caching](foundations/support-etags-for-caching.md)
  * [Provide Request-Ids for Introspection](foundations/provide-request-ids-for-introspection.md)
* [Requests](requests/README.md)
  * [Accept serialized JSON in request bodies](requests/accept-serialized-json-in-request-bodies.md)
  * [Resource names](requests/resource-names.md)
  * [Actions](requests/actions.md)
  * [Hierarchical data](requests/hierarchical-data.md)
  * [Use consistent path formats](requests/use-consistent-path-formats.md)
    * [Paths and attributes case](requests/paths-and-attributes-case.md)
    * [Support non-id dereferencing for convenience](requests/support-non-id-dereferencing-for-convenience.md)
    * [Minimize path nesting](requests/minimize-path-nesting.md)
  * [Collection requests](requests/collection-requests.md)
    * [Sorting](requests/sorting.md)
    * [Filtering](requests/filtering.md)
    * [Pagination](requests/pagination.md)
  * Sparse fieldsets
* [Responses](responses/README.md)
  * [Resource objects](responses/resource-objects.md)
    * [Provide resource (UU)IDs](responses/provide-resource-uuids.md)
    * [Type field](responses/type-field.md)
    * [Provide full resources where available](responses/provide-full-resources-where-available.md)
  * [Enveloping](responses/enveloping.md)
  * [Relationship population](responses/relationship-population.md)
  * Link objects
  * [Return appropriate status codes](responses/return-appropriate-status-codes.md)
  * [Generate structured errors](responses/generate-structured-errors.md)
  * [Keep JSON minified in all responses](responses/keep-json-minified-in-all-responses.md)
  * [Provide standard timestamps](responses/provide-standard-timestamps.md)
  * [Use UTC times formatted in ISO8601](responses/use-utc-times-formatted-in-iso8601.md)
  * [Show rate limit status](responses/show-rate-limit-status.md)
* [Artifacts](artifacts/README.md)
  *  [Provide machine-readable JSON schema](artifacts/provide-machine-readable-json-schema.md)
  *  [Provide human-readable docs](artifacts/provide-human-readable-docs.md)
  *  [Provide executable examples](artifacts/provide-executable-examples.md)
