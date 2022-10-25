FROM adoptopenjdk/openjdk11:x86_64-ubuntu-jdk-11.0.11_9-slim
EXPOSE 8080
ADD /target/ticket-booking-service-0.0.1-SNAPSHOT.jar ticket-booking-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","ticket-booking-service-0.0.1-SNAPSHOT.jar"]
ENV SOME=SOME1
ENV DT_RELEASE_VERSION=0.76
ENV DT_RELEASE_STAGE=Prod
ENV DT_RELEASE_PRODUCT=Zoo-back
