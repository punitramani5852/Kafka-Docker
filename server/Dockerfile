FROM openjdk:8-jre-slim

WORKDIR /kafka-dir

ADD kafka/ /kafka-dir/

EXPOSE 9092

CMD [ "./bin/kafka-server-start.sh","config/server.properties" ]
