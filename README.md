# maven-demo

A maven plugin to check errors in the maven clean plugin.

```bash
mvn clean package
```

A reproduction of the conditions is found in the code below in `pom.xml`.
The plugin version is `maven-clean-plugin:3.3.1`

```xml
<plugin>
    <artifactId>maven-clean-plugin</artifactId>
    <configuration>
        <directory>${tempDir}</directory>
    </configuration>
</plugin>
```

Details of a sample `mvn clean` run is provided in [sample-run.txt](./sample-run.txt)

Cheers!
