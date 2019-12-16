------------------------------------------------------------------------

[![Project Status: WIP ? Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip)

------------------------------------------------------------------------

# Curso Programación y manejo de datos 

<img src="/figs/mola-mazo.png" align="right" width="200" height="240"/>

Repo para alojar los materiales que se utilizarán en la asignatura [Programación y manejo de datos en la era del Big Data](https://webges.uv.es/uvGuiaDocenteWeb/guia?APP=uvGuiaDocenteWeb&ACTION=MOSTRARGUIA.M&MODULO=36494&CURSOACAD=2020&IDIOMA=C) del Grado en Economía de la UV.

- Aquí se alojarán, principalmente **tutoriales** y **transparencias de clase**. 

- La versión actualizada de los **ejemplos** y **casos** se encuentra en un RProject de RStudio Cloud, concretamente en: <https://rstudio.cloud/project/472823> . 

- Además, en este mismo repo, concretamente en el archivo `ejemplo_intro_DS.zip`, tienes una copia del Rproject con los ejemplos y casos.

- Durante el curso usaremos esta **etherpad**: <https://etherpad.wikimedia.org/p/curso_intro_DS_UV>

<br>

----------------------

# Trabajos de los estudiantes

Durante el curso 2019-20 los estudiantes hicieron un proyecto que aporta 1,25 puntos a la nota final del curso (el profe es un poco rácano⁉️). La verdad es que los estudiantes lo hicieron muy bien!!! 👏👏👏
Aquí puedes ver el listado de trabajos por orden de exposición:

1)  

2) [Project AGA](https://github.com/andreu2398/Project-AGA)


<br>

---------------------

# Descarga de los materiales utilizados durante el curso

Puedes descargarte **TODOS** los archivos de este repo pinchando en el icono verde donde pone "Clone or download" o, alternativamente, ejecutando las siguientes instrucciones en R/RStudio:

```r
#install.packages("usethis") 
usethis::use_course("perezp44/tutoriales_intro_DS", destdir = "./")
```

También puedes descargarte **todos** los archivos del repo usando solo R-base:

```r
url <- "https://github.com/perezp44/tutoriales_intro_DS/archive/master.zip"
download.file(url, destfile = "./tutoriales_intro_DS.zip")
unzip(zipfile = "./tutoriales_intro_DS.zip")
```

<br>


Si quieres descargarte **solo un archivo** puedes hacerlo con:

```r
file_to_download <- "tt_01_introduccion_v3.html" #- elige el archivo que quieres bajarte
url <- paste0("https://github.com/perezp44/tutoriales_intro_DS/raw/master/", file_to_download)
download.file(url, destfile = file_to_download)
```

<br>

Si quieres descargarte (y descomprimir) el Rproject con los ejemplos:

```r
file_to_download <- "ejemplos_intro_DS.zip" 
url <- paste0("https://github.com/perezp44/tutoriales_intro_DS/raw/master/", file_to_download)
download.file(url, destfile = file_to_download)
unzip(zipfile = file_to_download)
file.remove(file_to_download)        #- borra el archivo .zip
```
