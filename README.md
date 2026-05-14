# MBM-3
Omicas 2026
Proyecto:  Anotación estructural basica del genoma de E. coli usando Galaxy y Prokka para su posterior visualizacion y edicion en JBrowse  
Integrantes  
* Castro Vanessa
* Guerra Diego
* Pinduisaca Máximo
* Rios Jonathan  
* Sarango Jhandry
  
## OBJETIVO
* Realizar la anotación estructural básica del genoma de Escherichia coli mediante Galaxy y Prokka, y posteriormente visualizar y editar las anotaciones en JBrowse, con el fin de establecer un flujo bioinformático reproducible para proyectos académicos y de investigación aplicada.

## Metodología

* Descarga de la secuencia genómica desde NCBI.
*	Almacenamiento del archivo FASTA.
*	Análisis mediante comandos Linux.
*	Conteo de nucleótidos.
*	Búsqueda de patrones biológicos.
*	Automatización mediante scripts bash.
*	Documentación en GitHub.
  
## Dataset utilizado

* Fuente: NCBI
* Accession: MT781409.1
* Enlace: https://www.ncbi.nlm.nih.gov/nuccore/MT781409.1
* Formato: FASTA

## FLUJO DE TRABAJO
  * Descarga del genoma completo de E. coli desde NCBI GenBank o ENA.
  * Anotacion estructural con Prokka
  * Coversión y verificación de formatos
  * Instalar y configurar JBrowse
  * Visualiazión y edición del genoma en JBrowse
  * Conclusiones sobre la utilidad y aplicabilidad como flujo bioinformatico reproducible

## GALAXY VS LINEA DE COMANDOS

| Característica        | Galaxy    | Línea de comandos |
| --------------------- | --------- | ----------------- |
| Facilidad de uso      | Alta      | Media             |
| Requiere programación | No        | Sí                |
| Automatización        | Limitada  | Alta              |
| Flexibilidad          | Media     | Muy alta          |
| Reproducibilidad      | Alta      | Muy alta          |
| Uso en bioinformática | Académico | Profesional       |

  ### Workflow y organización

Como parte del equipo, se desarrolló y organizó el flujo de trabajo bioinformático del proyecto, asegurando la correcta secuencia de análisis.

  ### Workflow bioinformático

![Workflow parte 1](images/workflow1.png)

![Workflow parte 2](images/workflow2.png)

El workflow detallado es:

* NCBI → FASTA → Galaxy → Prokka → Resultados → Interpretación

Descripción del proceso:

  * NCBI: obtención de la secuencia genómica de Escherichia coli.
  * FASTA: formato de archivo utilizado como entrada del análisis.
  * Galaxy: plataforma bioinformática para el procesamiento de datos.
  * Prokka: herramienta de anotación estructural del genoma bacteriano.
  * Resultados: generación de archivos con genes y anotaciones.
  * Interpretación: análisis biológico de los resultados obtenidos.

Se incluyen evidencias visuales del proceso en la carpeta images/ del repositorio.
## RESULTADOS
## CONTRIBUCIÓN INDIVIDUAL
* Resumen breve  
## SCRIPTS  
