README

Prerequisite:

Download MySQL database Use the givit_db.sql to generate database schema

Open application.properties file, updated your corresponding mysql informaiton.

Work on Spring Boot Code:

STEP 1. Pull the project source code

STEP 2. Open the project from IDE (I use Eclipse)

If you use IDE terminal, you could do this:

First, set JAVA JDK PATH and Maven path. For example, for windows:

set PATH=%PATH%;C:\jdk1.8....\bin;C:\apache-maven....\bin (point to your jdk and maven path)

from terminal you could run maven command:

mvn compile
To sart/run the Spring Boot app:

mvn spring-boot:run
