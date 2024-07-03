# Temel görüntüyü belirleyin
FROM openjdk:17-jdk-slim

# Çalışma dizinini belirleyin
WORKDIR /app

# JAR dosyasını container'a kopyalayın
COPY target/demo-0.0.1-SNAPSHOT.jar app.jar

# Uygulamanın çalıştırılacağı komutu belirleyin
ENTRYPOINT ["java", "-jar", "app.jar"]

# Container'ın dinleyeceği portu belirleyin
EXPOSE 8080