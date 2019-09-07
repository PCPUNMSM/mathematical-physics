# Taller de Física Matemática
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PCPUNMSM/fisica-matematica/master)

**Club de Python Para Físicos**

Materiales para las distintas sesiones de física matemática usando Python llevadas a cabo en la Universidad Nacional Mayor de San Marcos

# Instalación

Para poder usar los notebooks de manera local deberá clonar este repo dandole al botón descargar o usando `git` de la siguiente forma

`git clone https://github.com/PCPUNMSM/fisica-matematica.git`

## Para Linux
El comando `git` viene instalado por defecto en la mayoría de distros


## Para Windows

Instalar git para Windows desde la [página oficial](https://git-scm.com/downloads).

Una vez instalado, abrir Git Bash y clonar el repositorio.


# Entorno de trabajo

Se usará Anaconda para manejar las librerias y entornos de trabajo. Descargar e instalar desde la dirección [oficial](https://www.anaconda.com/distribution/#download-section)

Una vez terminada la instalación y dentro del directorio clonado, instalar el entorno de trabajo de la siguiente manera

`conda env create -f environment.yml`

Este comando se encargara de instalar las librerias necesarias para correr este repositorio. En caso se agreguen nuevas librerias siguiendo el avance de las sesiones, el entorno de trabajo se actualiza de la siguiente forma

`conda env update -f environment.yml`

# Notebooks

Para hacer uso de los notebooks, abrir Anaconda Prompt y escribir 

`conda activate pcpunmsm`

 para activar el entorno de trabajo y luego ejecutar el comando `jupyter-lab` para iniciar el servidor de Jupyter. Los notebooks serán accesibles de manera local en la siguiente url http://localhost:8888