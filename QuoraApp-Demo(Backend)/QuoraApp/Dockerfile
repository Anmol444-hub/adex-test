FROM adoptopenjdk/openjdk11

WORKDIR /app/config

COPY ./target/test-classes/QuoraApp-0.0.1-SNAPSHOT.jar /app/QuoraApp-0.0.1-SNAPSHOT.jar

CMD ["java","-jar","/app/QuoraApp-0.0.1-SNAPSHOT.jar"]