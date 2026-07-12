FROM openjdk:24-ea

WORKDIR /app

COPY main.java .

EXPOSE 8001

RUN javac main.java

CMD ["java", "Main"]