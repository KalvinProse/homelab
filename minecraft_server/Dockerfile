# Beta minecraft Docker image
FROM eclipse-temurin:8-jre

WORKDIR /app
COPY b1.7.3.jar /app/b1.7.3.jar

EXPOSE 5560
USER 1000
CMD ["java","-jar","b1.7.3.jar"]
