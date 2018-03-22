# mvn-repo

Repository of Maven artifacts not yet published to Maven Central.


### Usage 

```xml
<repositories>
    <repository>
        <id>opentosca-mvn-repo</id>
        <url>https://raw.github.com/OpenTOSCA/mvn-repo/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```
