# java-core-lab

A personal sandbox for practising **basic and advanced Java concepts**. Each topic lives in its own package with small, focused examples and exercises so ideas can be explored in isolation.

## Tech Stack

- **Java:** 11
- **Build tool:** Maven
- **Group / Artifact:** `com.learning` / `java-practise`

## Topics Covered

Practice areas planned for this lab:

### Basics
- Language syntax, data types, and operators
- Control flow and arrays
- Strings and `StringBuilder`
- Object-Oriented Programming (classes, inheritance, polymorphism, encapsulation, abstraction)
- Exception handling
- Packages and access modifiers

### Advanced
- Collections framework (`List`, `Set`, `Map`, `Queue`)
- Generics and wildcards
- Functional interfaces, lambdas, and method references
- Streams API and `Optional`
- Multithreading and `java.util.concurrent`
- I/O and NIO
- JVM internals (memory model, garbage collection, class loading)
- Modern Java features (records, sealed classes, pattern matching, `var`, text blocks)

## Project Structure

```
java-core-lab/
├── pom.xml
├── src/
│   ├── main/
│   │   ├── java/com/learning/     # topic packages live here
│   │   └── resources/
│   └── test/
│       └── java/
└── README.md
```

New topics should be added as sub-packages under `com.learning` (e.g. `com.learning.collections`, `com.learning.streams`).

## Getting Started

Clone the repo and build with Maven:

```bash
git clone <repo-url>
cd java-core-lab
mvn clean install
```

Run a specific class from the command line:

```bash
mvn exec:java -Dexec.mainClass="com.learning.Main"
```

Or open the project in IntelliJ IDEA / Eclipse / VS Code and run the desired `main` method directly.

## Requirements

- JDK 11+
- Maven 3.6+
