# Pre-entrega: Extracción y Almacenamiento Seguro de Datos vía API

## Descripción
Script en Python que consume datos desde una API pública mediante peticiones HTTP GET, aplicando buenas prácticas de seguridad mediante variables de entorno (`.env`) y manejo de excepciones para fallos de red o códigos HTTP. Los datos extraídos son limpiados y almacenados en formato estructurado CSV.

## Estructura del Proyecto
- `extraccion_api.ipynb`: Código principal de extracción, transformación y carga.
- `data_extracted.csv`: Archivo de salida con los datos limpios y estructurados.
- `requirements.txt`: Dependencias necesarias para ejecutar el proyecto.
- `.gitignore`: Archivo de configuración para evitar subir credenciales o archivos `.env` al repositorio.

## Configuración y Ejecución
1. Clonar el repositorio e instalar las dependencias:
   ```bash
   pip install -r requirements.txt