# spring-cloud-config-server
This is Dynamic Config Server Application that fetches property files from ConfigServerProp.
This is the most suitable way of externalizing your application properties environment wise, your application does not need to be stopped and re-deploy in case of any change in properties, all you need to do is hit refresh endpoint of your application to see changes.

Right now there are 3 property files in ConfigServerProp
you can make changes in any of them and committ that then test it locally by.

http://localhost:8888/spring-boot-config/dev
http://localhost:8888/spring-boot-config/uat
http://localhost:8888/spring-boot-config/prod

http://localhost:8888/{application-name}/{profile}.

Spring-boot-config is the application that uses this config server for its properties.
