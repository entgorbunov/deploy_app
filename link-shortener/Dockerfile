FROM amazoncorretto:17.0.7-alpine

COPY ./link-shortener*.jar ./link-shortener.jar
COPY ./application-release.yaml ./application-release.yaml

ENV TZ=Europe/Moscow

EXPOSE 8081

CMD ["java", "-jar", "./link-shortener.jar"]
