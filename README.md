Repository to go along with the *How To Test Code Coverage Using SonarQube and Jacoco* 
[YouTube video](https://youtu.be/6BTOd0X8UCs) and article at [tomgregory.com](https://tomgregory.com/how-to-measure-code-coverage-using-sonarqube-and-jacoco/).

## Pre-requisites

* JDK 8+
* Docker

## Running

#### Running SonarQube

`./gradlew composeUp`

This will run SonarQube at [locahost:9000](http://localhost:9000).

#### Running a SonarQube scan

Wait for SonarQube to start, then run:

`./gradlew sonarqube`

## Stopping

`./gradlew composeDown`

## SonarQube 7 vs. 8

This example runs against the *lts* version of SonarQube (currently SonarQube 7).
An example using SonarQube 8 can be found on the [sonarqube-8](https://github.com/tkgregory/sonarqube-jacoco-code-coverage/tree/sonarqube-8) branch.