# Start with a base image containing Tomcat
FROM tomcat
FROM java:8

# Add Maintainer Info
LABEL maintainer="loginapp@miracle.com"

# Copy war file
COPY ./loginapp/target/login.war /usr/local/tomcat/webapps/

#Run the application
CMD ["java", "-war", "./loginapp/target/login.war"]
