# mvn-repo

Repository of Maven artifacts not yet published to Maven Central.


### Usage

```xml
<repositories>
    <repository>
        <id>opentosca-mvn-repo</id>
        <url>https://opentosca.github.io/mvn-repo/</url>
        <!-- <url>https://raw.github.com/OpenTOSCA/mvn-repo/<branch></url> -->
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```
