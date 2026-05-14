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

## Problema biológico
* El proyecto busca realizar la anotación estructural del genoma de *Escherichia coli* para identificar genes, regiones codificantes y elementos funcionales relevantes.

## Hipótesis
* Es posible identificar y anotar correctamente los genes funcionales del genoma de *E. coli* utilizando herramientas bioinformáticas como Galaxy y Prokka.

## Metodología

## Flujo de trabajo y organización

Como parte del equipo, se desarrolló y organizó el flujo de trabajo bioinformático del proyecto, asegurando una secuencia adecuada de análisis y la correcta organización de archivos dentro del repositorio GitHub.

### Flujo de trabajo bioinformático

El flujo de trabajo implementado fue el siguiente:

NCBI-SRA → FASTQ → FastQC → Trimmomatic → FastQC → SPAdes → Prokka → JBrowse → Resultados

### Descripción del proceso

- **NCBI-SRA:** obtención de lecturas genómicas de *Escherichia coli* desde la base de datos pública NCBI.
- **FASTQ:** archivos de secuencias utilizados como entrada para el análisis bioinformático.
- **FastQC:** evaluación de la calidad de las lecturas antes y después del filtrado.
- **Trimmomatic:** eliminación de regiones de baja calidad y aplicación de HEADCROP:20.
- **SPAdes:** ensamblaje del genoma bacteriano a partir de lecturas paired-end.
- **Prokka:** anotación estructural del genoma bacteriano.
- **JBrowse:** visualización e interpretación gráfica de las anotaciones genómicas.
- **Resultados:** generación de archivos anotados y análisis preliminar del genoma ensamblado.



Se incluyen evidencias visuales del proceso en la carpeta images/ del repositorio.
## RESULTADOS
## CONTRIBUCIÓN INDIVIDUAL
* Resumen breve  
## SCRIPTS  
