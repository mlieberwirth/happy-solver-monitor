# Happy-Solver-Monitor

Is a [Spring-Admin-Server](https://github.com/codecentric/spring-boot-admin) for monitoring of the Happy-Solver-Server.

## Preconditions
You need Java 8 and gradle.

## Run Monitoring

### Run in IDE

You only need to compile the sources as gradle-project in for instance eclipse and run ServerLauncher.java as application. Relevant application.yml is under 'src/main/resources'

### Run with gradle

    ./gradlew bootRun

### Create and run jar 
For build a jar use gradle

    ./gradlew bootJar
    
after that a executable jar is under /build/libs/. Run it with
    
    java -jar ./build/libs/happy-solver-monitor.jar

### With bash

Execute ``./build-copy.sh && ./run.sh`` in folder run-local. Relevant application.yml is in same folder.

## Open UI
If the server is running for example on localhost with port 8283 you can see all registered client-server on

    http://localhost:8283/#/applications

    
