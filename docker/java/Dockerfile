FROM openjdk:21-slim

RUN apt-get update

WORKDIR /GameServer

COPY src/GameServer /GameServer

CMD ["java", "--class-path", "./src/:./lib/*", "net.kanolab.aiwolf.server.automatic.AutoGameStarter"]
