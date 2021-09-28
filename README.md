## 	:triangular_flag_on_post: SAP Cloud Integration libraries

Import libraries into local MAVEN repo with the following cmd


```sh
mvn install:install-file -Dfile=<path>/com.sap.it.public.generic.api-2.25.0.jar -DgroupId=com.sap.it.public -DartifactId=generic.api -Dpackaging=jar -Dversion=2.25.0
```

```sh
mvn install:install-file -Dfile=<path>/cloud.integration.script.apis-2.7.1.jar -DgroupId=com.sap.it.script -DartifactId=cloud.integration.script.apis -Dpackaging=jar -Dversion=2.7.1
```

Add dependencies to the pom.xml

```xml
<dependency>
    <groupId>com.sap.it.public</groupId>
    <artifactId>generic.api</artifactId>
    <version>2.25.0</version>
</dependency>

<dependency>
    <groupId>com.sap.it.script</groupId>
    <artifactId>cloud.integration.script.apis</artifactId>
    <version>2.7.1</version>
</dependency>
```
