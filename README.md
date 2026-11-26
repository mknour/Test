# Hello World (Java)

A minimal Java hello world project built with Maven.

## Requirements

- Java 17+
- Maven 3.6+

## Build and run

```bash
mvn package
java -jar target/hello-world-1.0.0.jar
```

Or without Maven:

```bash
javac -d out src/main/java/com/example/HelloWorld.java
java -cp out com.example.HelloWorld
```
