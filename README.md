## SonarCloud deployment configured with the repository

SonarCloud project:

![SonarQube/SonarCloud deployment show to be configured with the repo](https://i.imgur.com/2Y3tGB9.png)

Sonar token:

![SonarQube/SonarCloud deployment show to be configured with the repo](https://i.imgur.com/RgniYvR.png)

Sonar quality gate configuration:

![SonarQube/SonarCloud quality gate configuration](https://i.imgur.com/ESeLdEM.png)

gradle.yml sonarcloud implementation with qualitygate.wait=true:

![image](https://user-images.githubusercontent.com/38559573/167475248-9d517007-5062-4157-92d6-f2190cc24267.png)

![Artifactory deployment configuration](https://i.imgur.com/Dc0eJjz.png)
![Artifactory deployment configuration](https://i.imgur.com/ujdpQZQ.png)
![Artifactory deployment configuration](https://i.imgur.com/J3yl72b.png)
![Artifactory deployment configuration](https://i.imgur.com/5m97GvY.png)
![image](https://user-images.githubusercontent.com/38559573/167476599-366e1c9d-6d35-4ddf-871d-10a42ddead54.png)

# Running Unit Tests With Maven and Gradle

This example application demonstrates how you can run unit tests which use JUnit 5 by using
either Maven or Gradle

## Running Unit Tests With Maven

You can run your unit tests by running the following command at the command prompt:

    mvn clean test   

## Running Unit Tests With Gradle

    gradle clean test 
