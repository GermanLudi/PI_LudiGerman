#de que imagen partimos
FROM amazoncorretto:11-alpine-jdk 
#quien es el dueño
MAINTAINER GDL
#va a copiar el empaqueado a git-hub
COPY target/gdl-0.0.1-SNAPSHOT.jar  gdl-app.jar
#es la instruccion que se va a ejecutar primero
ENTRYPOINT ["java","-jar","/gdl-app.jar"]
