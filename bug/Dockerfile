FROM mcr.microsoft.com/java/tomcat:8-zulu-alpine-tomcat-9
RUN rm -fr /usr/local/tomcat/webapps/ROOT
RUN npm
COPY <artifact> /usr/local/tomcat/webapps/ROOT.war
