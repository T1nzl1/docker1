FROM eclipse-temurin:17

LABEL version="1.0.1"

WORKDIR /docker-projects/javacal

COPY calc.java .

RUN javac calc.java

CMD ["java", "calculator"]