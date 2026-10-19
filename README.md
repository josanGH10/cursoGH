# Curso de Microsoft Fabric

Este repositorio contiene ejemplos y ejercicios para aprender Microsoft Fabric y GitHub.

## Objetivo

Practicar el uso de repositorios GitHub para guardar y compartir archivos relacionados con análisis e ingeniería de datos.

## Contenido

- **OneLake:** lago de datos unificado de Microsoft Fabric.
- **Lakehouse:** almacenamiento y análisis de datos con tablas Delta.
- **Notebooks:** ejecución de código PySpark.
- **Pipelines:** automatización de tareas de datos.
- **Dataflow Gen2:** transformación de datos con Power Query.
- **Warehouse:** análisis de datos relacionales mediante T-SQL.

## Ejemplo de PySpark

```python
from pyspark.sql import SparkSession

spark = SparkSession.builder.getOrCreate()
datos = [(1, "Laptop", 15000), (2, "Monitor", 4000), (3, "Teclado", 600)]
df = spark.createDataFrame(datos, ["ProductoID", "Producto", "Precio"])
df.show()
```

## Cómo usar este repositorio

1. Consulta los archivos desde la rama `main`.
2. Descarga o clona el repositorio para practicar.
3. Crea otra rama si deseas hacer cambios sin modificar directamente `main`.

## Nota

No subas contraseñas, claves de acceso ni datos confidenciales a un repositorio público.
