# dita-ot-plugins

An example of a modular development workflow for DITA-OT plugins.

## Requirements

For building and running the application you need:

- [OpenJDK 11](https://openjdk.org/projects/jdk/11/)
- [Maven](https://maven.apache.org)

## Getting Started

To get started, check out the installation instructions for ...

### Initialize and build modules

```shell
./mvnw clean install
```

### Run XSpec tests only for specific plugin

```shell
./mvnw test -pl plugins/org.shelden93.base
```

_Note: make sure that tools are initialized_

## Copyright

See [LICENSE](LICENSE)
