FROM python:3.10

RUN pip install pandas

# indicamos el destino donde vamos a copiar el archivo
WORKDIR /app 
# copiamos el archivo indicado, el segundo atributo indica el nombre en el destino (no tienen que ser iguales)
COPY pipeline.py pipeline.py

ENTRYPOINT [ "python" , "pipeline.py"]