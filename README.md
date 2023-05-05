jetbrick-parent
==================

This is a parent pom for jetbrick projects.

```xml
<parent>
    <groupId>com.github.subchen</groupId>
    <artifactId>jetbrick-parent</artifactId>
    <version>2.5</version>
</parent>
```

Supports following features

* Add license header / code format

    ```
    mvn process-sources -P format
    ```

* Code coverage (jacoco)

    ```
    mvn test -P jacoco
    ```

* Maven deploy and release

    ```
    mvn deploy -P oss -autoReleaseAfterClose=true
    ```

