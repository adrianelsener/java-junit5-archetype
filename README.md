Java 17 + JUnit 5 Quickstart Maven Archetype
======================================


Summary
-------
The project is a Maven archetype for Java 8 and JUnit 5


Prerequisites
-------------

- JDK 17
- Maven 3


Install archetype locally
-------------------------

To install the archetype in your local repository execute the following commands:

```bash
    git clone https://github.com/adrianelsener/java-junit5-archetype.git
    cd java-junit5-archetype
    mvn clean install
```


Last step: creating a project
----------------

```bash
 mvn archetype:generate \
 -DarchetypeGroupId=com.tbp \
 -DarchetypeArtifactId=java-junit5-archetype \
 -DarchetypeVersion=1.0.0-SNAPSHOT  \
 -DgroupId=com.example       \
 -DartifactId=my-project      \
 -DinteractiveMode=false
```
