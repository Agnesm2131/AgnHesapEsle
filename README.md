How to Build a Minecraft Plugin with Maven

Install Requirements

Java JDK (e.g., 17)

Apache Maven (mvn -v should work)

Project Setup

Place Java code in src/main/java

Place plugin.yml in src/main/resources

Configure pom.xml with Spigot/Paper dependency

Build Command
Run in your project root:

mvn clean package


Output
The compiled plugin will be in the target/ folder as a .jar file.

Deploy
Copy the .jar into your server’s plugins/ folder and restart the server.
