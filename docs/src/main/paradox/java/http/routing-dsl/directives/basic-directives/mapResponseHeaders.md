<a id="mapresponseheaders-java"></a>
# mapResponseHeaders

## Description

Changes the list of response headers that was generated by the inner route.

The `mapResponseHeaders` directive is used as a building block for @ref[Custom Directives-java](../custom-directives.md#custom-directives-java) to transform the list of
response headers that was generated by the inner route.

See @ref[Response Transforming Directives-java](index.md#response-transforming-directives-java) for similar directives.

## Example

@@snip [BasicDirectivesExamplesTest.java](../../../../../../../test/java/docs/http/javadsl/server/directives/BasicDirectivesExamplesTest.java) { #mapResponseHeaders }