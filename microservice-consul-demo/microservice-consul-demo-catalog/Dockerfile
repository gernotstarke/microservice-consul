FROM ewolff/docker-java
ADD target/microservice-consul-demo-catalog-0.0.1-SNAPSHOT.jar .
CMD /usr/bin/java -Dlogging.path=/log/ -Xmx400m -Xms400m -jar microservice-consul-demo-catalog-0.0.1-SNAPSHOT.jar
EXPOSE 8080