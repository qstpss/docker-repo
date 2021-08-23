FROM adoptopenjdk/openjdk11:latest
COPY dbservice.jar app.jar
CMD ["echo", "!!!!!!!! Wait for mysql is ready !!!!!!!!"]
CMD sleep 15 && java -jar /app.jar
