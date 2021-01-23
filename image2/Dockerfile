#build step
FROM openjdk:8 AS Stage1
WORKDIR /src
COPY Test.java .
# build the application and compile it!
RUN javac Test.java


#execution step
FROM alpine
RUN apk add openjdk8-jre
WORKDIR /src
COPY --from=Stage1 /src/Test.class .
CMD java Test