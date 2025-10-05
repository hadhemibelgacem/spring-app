# Étape 1 : utiliser l'image Java
FROM openjdk:17-jdk-slim

# Étape 2 : définir le répertoire de travail dans le conteneur
WORKDIR /app

# Étape 3 : copier le JAR compilé dans le conteneur
COPY target/*.jar app.jar

# Étape 4 : exposer le port utilisé par Spring Boot (par défaut 8080)
EXPOSE 8089

# Étape 5 : lancer l'application
ENTRYPOINT ["java","-jar","app.jar"]
