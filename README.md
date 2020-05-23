Repository to go along with the *How To Test Code Coverage Using SonarQube and Jacoco* 
[YouTube video](https://youtu.be/6BTOd0X8UCs) and article at [tomgregory.com](https://tomgregory.com/how-to-measure-code-coverage-using-sonarqube-and-jacoco/).

## Pre-requisites

* JDK 8+
* Docker

## Running

#### Running SonarQube

`./gradlew dockerComposeUp`

This will run SonarQube at [locahost:9000](http://localhost:9000).

#### Running a SonarQube scan

Wait for SonarQube to start, then run:

`./gradlew sonarqube`

## Stopping

`./gradlew dockerComposeDown`