Environment setup - Backend
=========

Here we expose the specific tools and technologies **needed** for developing the [backend](https://github.com/AdrianDeLasSierras/Backend).

Setup for development
-------------

1. Download and install [MySQL](http://www.mysql.com/downloads/) version 5.6.26.0.

2. Download and install the [latest JDK 7](http://www.oracle.com/technetwork/es/java/javase/downloads/jdk7-downloads-1880260.html).

3. Download and install the [Spring Tool Suite (STS)](https://spring.io/tools/sts).

4. Establish the recently installed JDK's JRE as the Java runtime for STS. For help [check this](http://stackoverflow.com/questions/25584564/change-enviornment-to-jdk-in-eclipse-luna).

5. If needed set the preferred IPV4 global setting for Java. [check this](http://stackoverflow.com/questions/11850655/how-can-i-disable-ipv6-stack-use-for-ipv4-ips-on-jre/11850724#11850724).

6. Install the [Gradle extension for STS](http://docs.spring.io/sts/docs/2.9.0.old/reference/html/gradle/installation.html).

7. Clone the [backend](https://github.com/AdrianDeLasSierras/Backend) repo.

8. Import the project into STS.

9. Create the *application.properties* file in the *[ProjectRoot]/ADS-SpringBE/src/main/resources* folder. It should be based on the *application.properties.sample* file located in the same folder but with your database user and password.

10. Import the development database located in *[ProjectRoot]/DevelopmentResources/adriandelassierras.sql* into MySQL server.

11. Run *gradle build* either from the command line or from the STS.

Setup for deploy
-------------

1. Download and install [MySQL](http://www.mysql.com/downloads/) version 5.6.26.0.

2. Import the production or QA database into MySQL server.

3. Download and install the [latest JDK 7](http://www.oracle.com/technetwork/es/java/javase/downloads/jdk7-downloads-1880260.html).

4. If needed set the preferred IPV4 global setting for Java. [check this](http://stackoverflow.com/questions/11850655/how-can-i-disable-ipv6-stack-use-for-ipv4-ips-on-jre/11850724#11850724).

5. Get the last backend jar build.

6. Establish the proper database user name and password in the *resources/*application.properties* file.

7. Run *gradlew run* on a command line located in the folder where the jar is.

License
-------------

Copyright (c) 2015 - 2015 Augusto Altman Quaranta <augusto.altman@gmail.com>, Julia Lima <julia.lima.dg@gmail.com>, Ricardo Fretes <rgfretes@gmail.com> et al Licensed under the MIT license.
