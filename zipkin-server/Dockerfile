FROM openjdk:11-jre-slim
COPY zipkin-server-2.23.2-exec.jar /usr/local/lib/zipkin-server.jar
#COPY zipkin-server /usr/local/lib/zipkin-server
EXPOSE 9411
ENTRYPOINT ["java","-jar","/usr/local/lib/zipkin-server.jar"]

#FROM openjdk:11
#VOLUME /tmp
#EXPOSE 9411
#ADD ./zipkin-server-2.23.2-exec.jar zipkin-server.jar
#ENTRYPOINT ["java","-jar","/zipkin-server.jar"]