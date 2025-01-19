# Descripción del ejercicio


En este ejercicio aprendo a desplegar una instancia de MediaWiki.

Utilizaré la imagen oficial que se encuentra disponible en Docker Hub: 
[Link a la imagen:](https://hub.docker.com/_/mediawiki)

Crear el contenedor:

```shell
docker run -d -p 8080-80 --name mimediawiki mediawiki
```

