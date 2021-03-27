Se ha creado un Dockerfile para esta herramienta, motarlo con:

Docker build -t <nombre> .

Eligiendo el nombre que se desee.

Arrancar la imagen desde Docker Desktop

Dentro del CLI creado por Docker Desktop, dentro de la carpeta test ejecutar:
python -m ramose -s mi_db_test.hf -c '/api/v2/metadata'

Este archivo de configuración tiene otro metodo que se accede sustituyendo "metadata" por "test"
