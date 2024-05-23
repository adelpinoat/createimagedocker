# Utilizar una imagen base de OpenJDK
FROM openjdk:17-jdk-slim

# Establecer el directorio de trabajo en /app
WORKDIR /app

# Copiar el archivo JAR de tu aplicación al contenedor
COPY target/*.jar app.jar

# Exponer el puerto que la aplicación va a usar
EXPOSE 8080

# Ejecutar la aplicación Java
ENTRYPOINT ["java", "-jar", "app.jar"]