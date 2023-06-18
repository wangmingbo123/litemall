FROM openjdk:8-jre
COPY application.yml application.yml
COPY ./litemall-all/target/litemall-all-*-exec.jar litemall.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","litemall.jar"]