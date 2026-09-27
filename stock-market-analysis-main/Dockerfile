FROM maven:3.9.9-eclipse-temurin-17

WORKDIR /app

COPY . .

WORKDIR /app/stock-market-analysis-main/backend/demo

RUN mvn package -DskipTests

EXPOSE 8080

CMD ["sh", "-c", "java -jar target/*.jar"]