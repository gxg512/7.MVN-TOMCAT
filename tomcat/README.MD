https://www.cprime.com/resources/blog/deploying-your-first-web-app-to-tomcat-on-docker/


docker build -t mywebapp .
docker run -d -p 8081:8080 mywebapp


http://192.168.1.6:8081/sample/
