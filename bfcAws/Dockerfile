FROM openjdk:17-alpine
WORKDIR /opt
ENV PORT 8282
EXPOSE 8282
COPY target/bfcDoc.exe.war /opt/bfcDoc.exe.war
ENTRYPOINT exec java $JAVA_OPTS -jar bfcDoc.exe.war
