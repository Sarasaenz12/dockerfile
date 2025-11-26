# Usar imagen oficial de OpenJDK
FROM eclipse-temurin:17

# Copiar el archivo Java al contenedor
COPY ExponenteRecursivoSaraSanchez.java .

# Compilar el archivo
RUN javac ExponenteRecursivoSaraSanchez.java

# Ejecutar el programa
CMD ["java", "ExponenteRecursivoSaraSanchez"]
