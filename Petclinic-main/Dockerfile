FROM openjdk:8
EXPOSE 8082
ADD Petclinic-main/target/petclinic.war petclinic.war
ENTRYPOINT ["java","-jar","/petclinic.war"]
