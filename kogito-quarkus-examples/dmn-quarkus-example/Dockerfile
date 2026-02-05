FROM eclipse-temurin:17-jdk

WORKDIR /app

# Copy the entire fast-jar output so we don't miss subfolders (lib/, app/, quarkus/, quarkus-run.jar)
COPY target/quarkus-app/ /app/

ENTRYPOINT ["java", "-jar", "quarkus-run.jar"]
