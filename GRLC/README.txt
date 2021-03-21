Sólo es necesario realizar este comando:
docker run -it --rm -p 8088:80 -e GRLC_SERVER_NAME=grlc.io -e GRLC_GITHUB_ACCESS_TOKEN=xxx clariah/grlc

"xxx" = es el token de acceso a GitHub, un token de acceso se encuentra en la memoria del trabajo.

Las pruebas se encuentra en el siguiente enlace: http://localhost:8088/api/david-menendez/grlc-queries

La herramienta original se encuentra en : https://github.com/CLARIAH/grlc
