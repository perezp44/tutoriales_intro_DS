------------------------------------------------------------------------

[![Project Status: WIP ? Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip) [![Last-changedate](https://img.shields.io/badge/last%20change-2018--02--06-yellowgreen.svg)](/commits/master)


------------------------------------------------------------------------


tutoriales_intro_DS <img src="/figures/mola-mazo.png" align="right" />
===================================================================


Repo para alojar los materiales que se utilizarán en la asignatura "Programación y manejo de datos en la era del Big Data" de la UV.

- Aquí se alojarán, principalmente **tutoriales** y **transparencias de clase**. 

- La versión actualizada de los **ejemplos** y **casos** se encuentra en un RProject de RStudio Cloud, concretamente en: <https://rstudio.cloud/project/472823> . 

- Además, en este mismo repo, concretamente en el archivo `ejemplo_intro_DS.zip`, tienes una copia del Rproject con los ejemplos y casos.

- Durante el curso usaremos esta **etherpad**: <https://etherpad.wikimedia.org/p/curso_intro_DS_UV>

<br>

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
