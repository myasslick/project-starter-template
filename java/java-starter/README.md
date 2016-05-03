(Based on
[Maven in Five Minutes](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html))

## Starter kit

To create this project, run

```
mvn archetype:generate -DgroupId=com.yeukhon.app \
-DartifactId=java-starter -DarchetypeArtifactId=maven-archetype-quickstart \
-DinteractiveMode=false
```

Then run ``mvn package`` to compile. Next, run the main class:

```
java -cp target/java-starter-1.0-SNAPSHOT.jar com.yeukhon.app.App
```

To skip the default phases, we can be lazy and run:

```
mvn -N compile
```
