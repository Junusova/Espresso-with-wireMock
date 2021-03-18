FROM openjdk:8-jre

ADD wiremock-standalone-2.27.2.jar wiremock-standalone-2.27.2.jar
ADD mappings mappings
ADD __files __files

EXPOSE 8181

ENTRYPOINT ["java","-jar","/wiremock-standalone-2.27.2.jar"]