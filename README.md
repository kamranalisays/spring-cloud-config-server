# spring-cloud-config-server

URL = http://localhost:8888/spring-cloud-server-configuration/default

Annotation @EnableConfigServer

Use can use it for spring cloud microservices

Ue can test it as standalone server


Note:

1)This project use a url https://github.com/kamranalisays/spring-cloud-server-configuration-properties-file in application.properties file to get the configuration.

2) Kindly check the url https://github.com/kamranalisays/spring-cloud-server-configuration-properties-file   is exist or not.

3) If the url exist then project will run successfuly otherwise you have to change the url in application.properties file or remove at the following location in application.properties file
spring.cloud.config.server.git.uri=https://github.com/kamranalisays/spring-cloud-server-configuration-properties-file.git
