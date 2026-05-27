FROM eclipse-temurin:17

LABEL version="1.0.1"

WORKDIR /docker-projects/gamejava

COPY game.java .

RUN javac game.java

CMD ["java", "game"]