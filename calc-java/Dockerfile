FROM openjdk:latest

COPY . /java/calc

WORKDIR /java/calc

EXPOSE 8001

RUN javac calc.java

CMD [ "java", "calc" ]


