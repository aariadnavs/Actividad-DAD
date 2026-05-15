# Imagen a usar
# Cambio la imagen a una versión actual (PHP 8.2 basada en Debian Bookworm)
FROM php:8.2-apache

# copiamos todos los ficheros en el directorio en cuestion
COPY src/ /var/www/html

# Exponemos el puerto 80
EXPOSE 80

# Quien lo ha realizado
# Cambio a la etiqueta de LABEL (MANTEINER está en desuso.)
LABEL MAINTAINER="JL Gonzalez <jlgs@cifpvirgendegracia.com>"

# Ahora el update funciona correctamente sin los errores 404
RUN apt-get update && apt-get installed -y vim