# insert base image
# download the tomcat 8.0 release 
FROM tomcat:8.0
# add .war file inside the tomcat dir
RUN cp -a **/*.war /usr/local/tomcat/webapps/
# run tomcat on port 8080 (container port)
EXPOSE 8080
# run tomcat image
CMD ["catalina.sh", "run"]