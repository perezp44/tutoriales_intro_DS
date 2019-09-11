# tutoriales_intro_DS

Este repo sirve para alojar materiales que se utilizarán en la asignatura "Programación y manejo de datos en la era del Big Data" de la UV.

Aquí se alojarán, principalmente tutoriales y transparencias de clase. Los ejemplos y casos se encuentran en: <https://rstudio.cloud/project/472823>.

Puedes descargarte **TODOS** los archivos de este repo pinchando en el icono verde donde pone "Clone or download" o ejecutando las siguientes instrucciones en R/RStudio:

```
#install.packages("usethis") 
usethis::use_course("perezp44/tutoriales_intro_DS", destdir = "./")
```

Alternativamente, también puedes descargarte **todos** los archivos del repo usando solo R-base:

```
url <- "https://github.com/perezp44/tutoriales_intro_DS/archive/master.zip"
download.file(url, destfile = "./tutoriales_intro_DS.zip")
unzip(zipfile = "./tutoriales_intro_DS.zip")
```

Si quieres descargarte **solo un archivo** puedes hacerlo con:

```
file_to_download <- "tt_01_introduccion_v3.html" #- elige el archivo que quieres bajarte
url <- paste0("https://github.com/perezp44/archivos_download/raw/master/", file_to_download)
download.file(url, destfile = file_to_download)
```
