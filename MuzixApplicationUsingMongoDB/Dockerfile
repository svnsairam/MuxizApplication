FROM openjdk:11
ADD ./target/MuzixApplicationUsingMongoDB-0.0.1-SNAPSHOT.jar /usr/src/MuzixApplicationUsingMongoDB-0.0.1-SNAPSHOT.jar
EXPOSE 8080
WORKDIR usr/src
ENTRYPOINT ["java","-jar","MuzixApplicationUsingMongoDB-0.0.1-SNAPSHOT.jar"]