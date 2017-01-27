FROM tomcat:8
MAINTAINER psof.io "info@psof.io"
RUN ["rm", "-fr", "/usr/local/tomcat/webapps/ROOT"]
COPY app/target/*.war /usr/local/tomcat/webapps/ROOT.war
