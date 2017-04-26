# HelloWorld

This is a very simple applicaiton for testing out Pipeline tooling. 

Some useful basic Maven Commands are below.

   mvn -v

   mvn package

   mvn dependency:tree

   mvn spring-boot:run

For Pivotal Cloud Foundry, use:

   cf push springboot --random-route -m 256M -p target/myproject-0.0.1-SNAPSHOT.jar


