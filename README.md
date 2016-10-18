##About
This repository contains some maven artifacts not found in other public maven repos

###To use it, include folowing lines in your pom.xml

```xml
<repository>
    <id>sunlaud-repo</id>
    <name>sunlaud maven repository</name>
    <url>https://raw.github.com/sunlaud/maven-repo/master</url>
</repository>
```


###Repository contents:

1. LuaJ - lua programming language implemented in java.
Found here: http://luaj.org/luaj/README.html.
Version: v3.0-alpha1

```xml
<dependency>
    <groupId>org.luaj</groupId>
    <artifactId>luaj-jse</artifactId>
    <version>3.0-alpha1</version>
</dependency>
```

2. enterprise-calc - enterprise calculator used as a target for test coverage
Version: v1.0-SNAPSHOT

```xml
<dependency>
    <groupId>com.epam.rd</groupId>
    <artifactId>enterprise-calc</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```
