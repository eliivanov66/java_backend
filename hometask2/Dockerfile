FROM openjdk:11
COPY ./logic/ /usr/src/myapp/logic
COPY ./resurces/ /usr/src/myapp/resurces
WORKDIR /usr/src/myapp/
RUN javac ./resurces/*.java
RUN javac ./logic/*.java
RUN export DISPLAY=:1
CMD ["java", "logic.Logic"]
