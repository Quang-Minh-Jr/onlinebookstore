FROM tomcat

# War file will be passed once docker build
ARG warfile

# Add the package .war file to tomcat webapp source
ADD ${warfile} /usr/local/tomcat/webapps

# Run the default Tomcat server
CMD ["catalina.sh", "run"]