#maven-tomcat-demo

#run

```shell
mvn tomcat7:run
```

[http://localhost:8080/maven-tomcat-demo](http://localhost:8080/maven-tomcat-demo)

---------

###pom.xml
```xml
    <build>
        <plugins>
            <plugin>
                <groupId>org.apache.tomcat.maven</groupId>
                <artifactId>tomcat7-maven-plugin</artifactId>
                <version>2.2</version>
            </plugin>
        </plugins>
    </build>
```