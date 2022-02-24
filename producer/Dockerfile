FROM openjdk:8-jre-slim

WORKDIR /kafka-dir

ADD kafka/ /kafka-dir/

CMD ./bin/kafka-console-producer.sh --bootstrap-server server:9092 --topic test
