FROM tomcat
EXPOSE 8080
ADD /target/ROOT.war /usr/local/tomcat/webapps/ROOT.war 
# ENTRYPOINT [ "java","-jar","Insight68-0.0.1-SNAPSHOT.war" ] 
RUN chmod -R 777 /usr/local/tomcat/webapps
CMD ["catalina.sh", "run"]