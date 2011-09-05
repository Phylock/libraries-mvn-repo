#Howto
To add this maven2 repository to your project add one of the following sections to your pom.xml.

##Release
```xml
<repositories>
    <repository>
        <id>phylock-libraries</id>
        <url>https://github.com/phylock/libraries-mvn-repo/raw/master/release</url>
    </repository>
</repositories>
```

##Snapshot
```xml
<repositories>
    <repository>
        <id>phylock-libraries-snapshots</id>
        <url>https://github.com/phylock/libraries-mvn-repo/raw/master/snapshots</url>
    </repository>
</repositories>
```
