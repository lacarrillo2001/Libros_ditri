FROM openjdk:17.0.2

WORKDIR /app

#Copia el archivo JAR de la aplicación al contenedor
COPY ./target/oauth-server-0.0.1-SNAPSHOT.jar ./oauth-server-0.0.1-SNAPSHOT.jar

#Expone el puerto 8001 para acceder a la aplicación
EXPOSE 9000

#Comando para ejecutar la aplicación
ENTRYPOINT ["java","-jar","oauth-server-0.0.1-SNAPSHOT.jar"]