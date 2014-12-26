spring-gradle-sample
====================

Small project build wiht gradle that gets built into a war deployable on tomcat 8

Steps to run:

1. Install Java 8 and set JAVA_HOME environment variable

2. Install Gradle 2.x.x and set GRADLE_HOME environment variable (I use a standalone Gradle local instance to build all my projects, I do not like the Gradle wrapper very much.

3. Install Tomcat 8

4. Download and install an IDE (I recommend Intellij Idea)

5. Run "gradle war"

6. In build/libs you will find your war: spring-gradle-sample.war. Deploy this war on your Tomcat installation (by copying it under  CATALINA_HOME/webapps 
or use your editor to deploy it by creating a Tomcat Launcher.

7. Start adding your own stuff.

Enjoy!