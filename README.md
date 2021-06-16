# My Custom Extension

In order to install the connector go to the directory where pom.xml is placed.
Run the following command

```
mvn install
```


Add this dependency to your application pom.xml

```
<groupId>org.mulesoft.extension</groupId>
<artifactId>mule_custom_connector</artifactId>
<version>1.0.0</version>
<classifier>mule-plugin</classifier>
```
