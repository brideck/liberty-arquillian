# Arquillian Liberty Server Containers [![Maven Central Latest](https://maven-badges.herokuapp.com/maven-central/io.openliberty.arquillian/arquillian-parent-liberty/badge.svg)](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22io.openliberty.arquillian%22%20AND%20a%3A%22arquillian-parent-liberty%22) [![Build Status 1.x](https://github.com/OpenLiberty/liberty-arquillian/actions/workflows/maven.yml/badge.svg?branch=1.x-maintenance)](https://github.com/OpenLiberty/liberty-arquillian/actions?branch=1.x-maintenance)

For Arquillian Liberty Managed container documentation, click [here](https://github.com/OpenLiberty/liberty-arquillian/tree/main/liberty-managed/README.md).

For Arquillian Liberty Remote container documentation, click [here](https://github.com/OpenLiberty/liberty-arquillian/tree/main/liberty-remote/README.md).

### Testing

To run tests, you will need to specify the following parameters:

| Parameter        | Description |
| ---------------- | ----------- |
| runtime          | The runtime to use. Specify `ol` for Open Liberty and `wlp` for WebSphere Liberty. |
| runtimeVersion   | Version of the specified runtime to use. |

For example, to run tests on version 21.0.0.3 of the Open Liberty runtime, use the following command:

```
mvn verify -Druntime=ol -DruntimeVersion=21.0.0.3
```