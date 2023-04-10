FROM openjdk
EXPOSE 8080
ARG JAR_FILE=./target/SpringCrud-0.0.1-SNAPSHOT.jar 
ADD ${JAR_FILE} SpringCrud-0.0.1-SNAPSHOT.jar 
ENTRYPOINT ["java","-jar","/SpringCrud-0.0.1-SNAPSHOT.jar"]
