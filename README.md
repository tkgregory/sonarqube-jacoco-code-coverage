Repository to go along with the *How To Test Code Coverage Using SonarQube and Jacoco* article
at [tomgregory.com](https://www.tomgregory.com).

## Pre-requisites

* Docker

## Running

#### Running SonarQube

`./gradlew dockerComposeUp`

This will run SonarQube at [locahost:9000](http://localhost:9000).

#### Running a SonarQube scan

`./gradlew sonarqube`

## Stopping

`docker-compose down`

(unfortunately the Palantir Gradle plugin doesn't provide a *dockerComposeDown* task
so we have to run the *docker-compose* command directly)