FROM tomcat:8-jre11
RUN rm -rf usr/local/tomcat/webapps/*
LABEL "author"="admin"
LABEL "project"="dockertest"
COPY target/artifact.war /usr/local/tomcat/webapps/origin.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
WORKDIR /usr/local/tomcat
VOLUME /usr/local/tomcat/webapps