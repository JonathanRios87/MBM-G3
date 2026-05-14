# MBM-3
Omicas 2026  
## Proyecto:  Anotación estructural y ensamblaje del genoma de E. coli usando Galaxy y Prokka para su posterior visualizacion y edicion en JBrowse  
## Integrantes  
* Castro Vanessa
* Guerra Diego
* Pinduisaca Máximo
* Rios Jonathan  
* Sarango Jhandry

## Planteamiento del problema
* El ensamblaje y la anotación estructural de genomas bacterianos constituyen procesos fundamentales en la genómica funcional y bioinformática, debido a su importancia en la identificación de genes, regiones codificantes y elementos regulatorios. Sin embargo, la integración de herramientas como Galaxy, Prokka y JBrowse presenta limitaciones relacionadas con la reproducibilidad, compatibilidad de formatos y correcta interpretación de datos genómicos. En el caso de Escherichia coli, una anotación deficiente puede afectar la identificación precisa de genes y la visualización estructural del genoma. Por ello, se plantea implementar un flujo de trabajo bioinformático para el ensamblaje, anotación estructural y posterior visualización genómica, optimizando la organización, análisis y edición de la información genética bacteriana.

## Objetivo
* Realizar la anotación estructural básica del genoma de E. coli mediante Prokka, y posteriormente visualizar y editar las anotaciones en JBrowse, con el fin de establecer un flujo bioinformático reproducible para proyectos académicos y de investigación aplicada.  
## Dataset
* Escherichia Coli es un organismo modelo por excelencia en la biologia molecular, su rapido crecimiento y genoma bien definida permitieron descubrir como funciona el codigo genetico y la replicacion del ADN. En ingenieria genetica se utiliza para la produccion de medicamentos, compuestos quimicos y biocombustibles, mediante la modificacio de sus vias metabolicas, actua como celula huesped para la sintesis de proteinas complejas mediante la insercion de plasmidos. Se genoma flexible permite la incorporcion de transposones, fagos y plasmidos facilitando su clonacion y secuenciacion  

* # IDENTIFICACION DE SECUENCIA FATSQ E. Coli  
* La secuencia se obtuvo de la base de datos NCBI  
* https://trace.ncbi.nlm.nih.gov/Traces/?run=SRR2584863  
* La elección e importancia del estudio de E. coli radica en su rol como organismo modelo, su gran versatilidad y capacidad de analisis permite validar herramientas bioinformáticas de ensamblaje y además estudiar los mecanismos de adaptación y resistencia.
 
<img width="1366" height="768" alt="imagen" src="https://github.com/user-attachments/assets/c46625bc-9acf-4c04-9575-01f37664a183" />
<img width="1366" height="768" alt="imagen" src="https://github.com/user-attachments/assets/1db1370c-8fdf-44e9-8953-1e30be0747d8" />
<img width="1366" height="768" alt="imagen" src="https://github.com/user-attachments/assets/dfa634a8-8904-4fd2-a6ff-aca7243dfd66" />

## Flujo de trabajo

<p align="center">
  <img src="images/workflow_escherichia_coli.png" width="800">
</p>

  * Descarga del genoma E. coli desde NCBI GenBank SRR2584863 
  * Control Calidad Datos
  * Trimming
  * Ensamblaje
  * Anotacion estructural con Prokka
  * Instalar y configurar JBrowse
  * Visualiazión y edición del genoma en JBrowse
  * Conclusiones sobre la utilidad y aplicabilidad como flujo bioinformatico reproducible  
## Resultados
<img width="1365" height="629" alt="Captura de pantalla 2026-05-14 100856" src="https://github.com/user-attachments/assets/4540a942-f7d4-48c9-91b7-8fac78dc533c" />
<img width="1060" height="582" alt="Captura de pantalla 2026-05-14 102002" src="https://github.com/user-attachments/assets/dc29a882-ecc1-4bc4-b08c-0ea2dbc84fa3" />
<img width="1261" height="628" alt="Captura de pantalla 2026-05-14 102013" src="https://github.com/user-attachments/assets/911b5ba4-465a-4c50-ba97-d6347491692d" />

## Contribucion individual
 * Este proyecto se enfocó en el ensamblaje y la anotación estructural del genoma de *Escherichia coli* mediante el uso de herramientas bioinformáticas especializadas como Galaxy, Prokka y JBrowse. Inicialmente, se obtuvieron secuencias genómicas desde bases de datos públicas y se realizó un control de calidad para garantizar la integridad de las lecturas. Posteriormente, se ejecutó el ensamblaje del genoma en Galaxy, permitiendo reconstruir la secuencia genómica bacteriana a partir de fragmentos de ADN.

 * Una vez ensamblado el genoma, se aplicó Prokka para identificar genes, regiones codificantes, ARN ribosomal y otros elementos genéticos presentes en el organismo. Los archivos generados en formatos FASTA y GFF fueron posteriormente integrados en JBrowse para la visualización y edición de la estructura genómica de *E. coli*. Este flujo de trabajo permitió desarrollar un análisis reproducible y organizado, fortaleciendo competencias en genómica, anotación estructural y manejo de herramientas bioinformáticas aplicadas al análisis molecular bacteriano.
## SCRIPTS  
<img width="1266" height="591" alt="image" src="https://github.com/user-attachments/assets/a4b026bf-e349-41b0-9382-a34236d3078c" />
