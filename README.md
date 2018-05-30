# java-testing-project

* mvn clean install
* java -jar /target/demo-0.0.1-SNAPSHOT.jar 

# In order to check the status of the app you have two different options.

1. curl -X GET localhost:8080/actuator/health

2. ps aux | grep java

For ELB health check you can use ${IP}:8080/actuator/health, you will get 200 code.
