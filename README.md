# nifi-gradle-nar-example

A test project to set up a full Groovy/Gradle based project for an example NAR for Apache NiFi

## Requirements

1. Java 1.8
    * I recommend instalation with brew and using jenv:
        * `brew install openjdk@1.8 jenv`
        * `jenv add /home/linuxbrew/.linuxbrew/Cellar/openjdk@8/1.8.0-442/` Of course, actual version on your machine
        * `jenv global 1.8`

## How to build

`./gradlew build`

You can also list tasks with `./gradlew tasks`
