# Docker: PHP 

Instala rápidamente un ambiente de desarrollo local con Apache y PHP utilizando [Docker](https://www.docker.com). 

El proyecto instala `PHP 7.2` con las extensiones `mysql`, `pdo`, `pdo_mysql` y Apache con el módulo `rewrite` habilitado.

### Requerimientos

* [Docker Desktop](https://www.docker.com/products/docker-desktop)


### Instalar el ambiente de desarrollo

```zsh
docker-compose up -d
```

### Comandos disponibles

Una vez instalado, se pueden utilizar los siguiente comandos:

```zsh
docker-compose start    # Iniciar el ambiente de desarrollo
docker-compose stop     # Detener el ambiente de desarrollo
docker-compose down     # Detener y eliminar el ambiente de desarrollo.
```


### Estructura de Archivos

* `Dockerfile` contiene la configuración para crear la imagen Docker.
* `docker-compose.yml` contiene la configuración para crear el contenedor.
* `/www/` carpeta para los archivos PHP del proyecto.


### Accesos

http://localhost/

