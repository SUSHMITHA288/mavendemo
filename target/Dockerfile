FROM tomcat:9.0-alpine
LABEL maintainer="sushmitha.m.raj12@gmail.com"

COPY maven-webapp/Demo2/target/Demo2.war /usr/local/tomcat/webapps/

EXPOSE 8888
CMD ["catalina.sh", "run"]
