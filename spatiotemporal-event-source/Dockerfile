# maintainer: Adam Mollenkopf (@amollenkopf)
FROM centos
RUN yum install -y java-1.8.0-openjdk.x86_64
ADD ./data/taxi/taxi-simulation-01-25.csv /data/taxi/taxi-simulation-01-25.csv
ADD ./target/scala-2.11/spatiotemporal-event-source-assembly-1.0.jar /jars/spatiotemporal-event-source-assembly-1.0.jar
