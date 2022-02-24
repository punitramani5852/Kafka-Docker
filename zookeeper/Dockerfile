FROM openjdk:8-jre-slim

WORKDIR /kafka-dir

ADD kafka/ /kafka-dir/

EXPOSE 2181

CMD ./bin/zookeeper-server-start.sh config/zookeeper.properties
