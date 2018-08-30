# Imagen de Golang Alpine + Make + GIT


Se crea imagen debido a que versión actual de Kubernetes utilizando [Kismatic] (https://github.com/apprenda/kismatic) no soporte para crear imagenes MultiStage.

Esta imagen contempla los siguientes paquetes adicionales a la imagen base:

- make
- git
- bash
- openssl
- swagger-go

Para compilar:
```
docker build -t "nombreimagen:tag" .

```