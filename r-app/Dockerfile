# Usar la imagen oficial de R
FROM r-base

# Crear el directorio de trabajo
WORKDIR /usr/src/app

# Copiar el archivo app.R al contenedor
COPY app.R /usr/src/app/

# Comando para ejecutar el script de R
CMD ["Rscript", "app.R"]
