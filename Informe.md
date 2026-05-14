PROYECTO : ** Anotación estructural básica del genoma de *Escherichia coli* utilizando Galaxy y Prokka para su posterior visualización en JBrowse **  
Integrantes:  
* Maximo Pinduisaca  
* Jhandry Sarango  
* Vanessa Castro  
* Diego Guerra  
* Jonathan Rios
  
**Objetivo**   
Realizar el ensamblaje y la anotación estructural del genoma de *Escherichia coli* utilizando datos provenientes de NCBI-SRA, mediante herramientas bioinformáticas como FastQC, Trimmomatic, SPAdes, Prokka y JBrowse, para obtener un genoma anotado e interpretable biológicamente. 

## Problema biológico
* El proyecto busca realizar la anotación estructural del genoma de *Escherichia coli* para identificar genes, regiones codificantes y elementos funcionales relevantes.

**1. Introducción**  

La anotación de genomas bacterianos constituye una herramienta esencial en bioinformática, ya que permite identificar y organizar los elementos estructurales básicos de la secuencia genética, como genes codificantes, regiones reguladoras y ARN funcionales. *Escherichia coli*, una bacteria modelo ampliamente utilizada en estudios de microbiología y genética molecular, representa un organismo ideal para aplicar metodologías de ensamblaje y anotación genómica debido a la gran cantidad de información disponible en bases de datos públicas.

En este proyecto se propone realizar el ensamblaje y la anotación estructural del genoma de *E. coli* utilizando datos obtenidos desde NCBI-SRA, mediante el entorno bioinformático Galaxy, el cual facilita la ejecución de flujos de trabajo reproducibles para análisis genómicos. Asimismo, se emplea SPAdes para el ensamblaje del genoma y Prokka para la anotación automática de genes bacterianos.

Posteriormente, las anotaciones obtenidas serán visualizadas en JBrowse, un navegador genómico interactivo que permite explorar de manera dinámica la organización del genoma y sus elementos funcionales. Este flujo de trabajo busca establecer un pipeline bioinformático reproducible, útil tanto en el ámbito académico como en investigaciones aplicadas, fortaleciendo la formación en análisis genómico y la interpretación de datos biológicos.

**2. Metodologia (Workflow)**  

## Flujo de trabajo bioinformático implementado

El flujo de trabajo utilizado en el proyecto sigue un proceso estándar de análisis genómico, desde la obtención de datos crudos hasta la anotación e interpretación biológica final.

* NCBI-SRA → FASTQ → FastQC → Trimmomatic → FastQC → SPAdes → Prokka → JBrowse → Resultados

## Descripción detallada del proceso

### NCBI-SRA
* Se realizó la obtención de datos genómicos de *Escherichia coli* desde la base de datos pública NCBI Sequence Read Archive (SRA).  
Este repositorio proporciona lecturas de secuenciación de alta calidad generadas por tecnologías de secuenciación masiva.

### FASTQ
Los datos descargados se encuentran en formato FASTQ, el cual contiene:
* Secuencias de nucleótidos
* Calidad de cada base 
Estos archivos constituyen la entrada principal para el análisis bioinformático.

### FastQC (control de calidad inicial)
Se aplicó FastQC para evaluar la calidad de las lecturas crudas antes del procesamiento.
Este análisis permitió identificar:
* Calidad promedio de las bases
* Presencia de adaptadores o regiones de baja calidad
* Distribución de calidad por lectura

### Trimmomatic (filtrado de calidad)
Se utilizó Trimmomatic para mejorar la calidad de los datos eliminando:
* Bases de baja calidad en los extremos
* Secuencias no confiables
Se aplicó el parámetro **HEADCROP:20**, eliminando los primeros 20 nucleótidos de cada lectura para reducir posibles errores sistemáticos.

### FastQC (control posterior)
Después del filtrado, se realizó nuevamente FastQC para verificar la mejora en la calidad de las lecturas.
Se observó:
* Incremento en la calidad promedio
* Reducción de ruido en las secuencias
* Datos más adecuados para ensamblaje

### SPAdes (ensamblaje del genoma)
Con las lecturas filtradas se realizó el ensamblaje del genoma utilizando SPAdes.
Este proceso permitió:
* Reconstruir fragmentos largos (contigs)
* Aproximar la estructura del genoma bacteriano
* Organizar las lecturas en secuencias continuas

### Prokka (anotación estructural)
Se utilizó Prokka para identificar elementos funcionales dentro del genoma ensamblado.
Este paso permitió:
* Identificación de genes codificantes
* Predicción de regiones funcionales
* Generación de archivos de anotación como .gff y .fna

### JBrowse (visualización genómica)
Los resultados fueron cargados en JBrowse para su visualización interactiva.
Esto permitió:
* Observar la organización del genoma
* Visualizar genes anotados
* Analizar regiones funcionales de forma gráfica

### Resultados finales
Como resultado del flujo de trabajo se obtuvo:
* Un genoma ensamblado de *Escherichia coli*
* Anotaciones funcionales de genes
* Archivos interpretables (.gff, .fna)
* Visualización genómica en JBrowse

Estos resultados permiten un análisis preliminar de la estructura genética del organismo.

Todas las evidencias del proceso (capturas de pantalla, resultados intermedios y visualizaciones) se encuentran organizadas en la carpeta `images/` del repositorio del proyecto.
   
**3. Resultados**  
**4. Discusion**  
**5. Conclusiones**  
**6. Referencias bibliograficas**  
