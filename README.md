Repository to go along with the *How To Test Code Coverage Using SonarQube and Jacoco* 
[YouTube video](https://youtu.be/6BTOd0X8UCs) and article at [tomgregory.com](https://tomgregory.com/how-to-measure-code-coverage-using-sonarqube-and-jacoco/).

[![CI](https://github.com/tkgregory/sonarqube-jacoco-code-coverage/actions/workflows/gradle.yml/badge.svg)](https://github.com/tkgregory/sonarqube-jacoco-code-coverage/actions/workflows/gradle.yml)

## Pre-requisites

* JDK 8+
* Docker

## Running

#### Running SonarQube

`./gradlew composeUp`

This will run SonarQube at [locahost:9000](http://localhost:9000).
The default login is *admin/admin*, then you will need to set a new password.

#### Running a SonarQube scan

Wait for SonarQube to start, then run:

`./gradlew sonarqube`

## Stopping

`./gradlew composeDown`

## SonarQube version

This example runs against the *lts* version of SonarQube (currently SonarQube 8.9).
