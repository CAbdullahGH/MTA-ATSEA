FROM tomcat

COPY mta-java.war /usr/local/tomcat/webapps/ROOT.war
RUN rm -rf /usr/local/tomcat/webapps/ROOT
RUN /usr/local/tomcat/bin/catalina.sh start
