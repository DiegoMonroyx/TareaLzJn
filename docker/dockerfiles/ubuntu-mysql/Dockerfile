# Usar Ubuntu como imagen base
FROM ubuntu:latest

# Establecer variables de entorno para evitar preguntas interactivas durante la instalación
ENV DEBIAN_FRONTEND=noninteractive

# Actualizar el sistema e instalar MySQL
RUN apt-get update && \
    apt-get install -y mysql-server && \
    apt-get clean

# Copiar el archivo de configuración para MySQL (opcional)
# Si tienes un archivo de configuración personalizado, descomenta esta línea y reemplaza "my.cnf" con tu archivo.
# COPY my.cnf /etc/mysql/my.cnf

# Exponer el puerto por defecto de MySQL
EXPOSE 3306

# Establecer el comando de inicio
CMD ["mysqld"]