Se ha creado un Dockerfile para esta herramienta.

Montar la imagen con :
docker build -t <nombre> .

Y arrancar la imagen con: 
docker run -it --rm -p 3000:3000 --name miwalder my_walder

(NOTA: en este caso se ha montado la imagen con nombre “my_walder” y creado el contenedor “miwalder”)

Dentro del CLI del contenedor, ejecutar: 
walder -c example/myconfig.yaml

Con esta configuración se puede acceder a :
http://localhost:3000/Jackson
http://localhost:3000/Gaga

La herramienta original se encuentra en: https://github.com/KNowledgeOnWebScale/walder

La herramienta a sido comprimida por la cantidad de archivos diferentes que contiene.

