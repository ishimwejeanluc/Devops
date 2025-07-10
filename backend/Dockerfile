FROM maven:3.9.6-eclipse-temurin-17

WORKDIR /app

COPY . .

RUN mvn clean install -pl backend -am -DskipTests

CMD ["java", "-jar", "backend/target/schedule.backend-0.0.1-SNAPSHOT.jar"]
