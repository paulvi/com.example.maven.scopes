
Links
- <http://maven.apache.org/guides/introduction/introduction-to-dependency-mechanism>

When module has a `provided` dependency, it is not transitive.
Dependency's dependencies will not be added.
Next module, depending on the 1st module, will not see the `provided` dependency.


From Maven developers point of view,
Shouldn't transitive dependencies be imported as runtime?
So that it is clearer what APIs are used.