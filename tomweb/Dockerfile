FROM tomcat:8-jre11
LABEl "admin"="vicky"
LABEL "projectname"="test"
RUN rm -rf /usr/local/tomcat/webapps/*
COPY target/artifact.war /usr/local/tomcat/webapps/articopy.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
WORKDIR /usr/local/tomcat
VOLUME /usr/local/tomcat/webapps