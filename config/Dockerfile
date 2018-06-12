FROM java:8-jre
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>
RUN apt-get update
RUN apt-get install -y curl
ADD ./target/config.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/config.jar"]
EXPOSE 8888



