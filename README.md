# artifactory-lib-example

Simple hello world project for testing [Artifactory][artifactory] library deployment.

This project will publish a `jar file` to Artifactory using `Gradle`.

Use this project in conjunction with [artifactory-app-example][app-example] when testing.

Tested on Gradle version 2.10, using Wrapper.

To run this project use `./gradlew build jar artifactoryPublish`

[artifactory]: https://www.jfrog.com/open-source/
[app-example]: https://github.com/RobGThai/artifactory-app-example
