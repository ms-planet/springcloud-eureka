FROM hub.c.163.com/library/java:8-apline

ADD target/*.jar app.jar

EXPOSE 8761

ENTRYPOINT ["java","-jar","/app.jar"]