
Links
- <http://maven.apache.org/guides/introduction/introduction-to-dependency-mechanism>

When module has a `provided` dependency, it is not transitive.
Dependency's dependencies will not be added.
Next module, depending on the 1st module, will not see the `provided` dependency.