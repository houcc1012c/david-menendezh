Para obtener la herramienta:
docker pull apache/marmotta

Para ejecutar la herramienta: 
docker run -p 8080:8080 apache/marmotta

Cuando está en ejecución añadir los archivos ttl que se quieran probar:

curl -i -X POST -d @test-30.ttl -H "Content-Type: text/turtle" -H "Slug: test" http://localhost:8080/marmotta/ldp
curl -i -H "Accept: text/turtle" http://localhost:8080/marmotta/ldp/test

Los archivos probados para esta herramienta provienen de: https://www.w3.org/TeamSubmission/turtle/
La herramienta original se encuentra en : http://marmotta.apache.org/platform/ldp-module.html
