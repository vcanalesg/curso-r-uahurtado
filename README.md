# Curso de Introducción a R - Universidad Alberto Hurtado

## ¡Hola!

Este repositorio contendrá los link a las clases y el código que revisaremos en estas. También encontrarás las instrucciones para instalar R y RStudio en tu computador personal.

## Instalación de R y RStudio

Para instalar R y RStudio debes seguir los siguientes pasos:

1. **Instala R** desde <https://cran.r-project.org>

   + Dependiendo de tu sistema operativo, haz click en alguno de los siguientes links:
   
   ![](https://github.com/vcanalesg/curso-r-uahurtado/raw/main/images/r_cran.png)

   + Haz click en el link que dice **base**.

   + Ahora, haz click en el link de descarga que aparece justo arriba de la página. En el caso que hayas elegido Windows deberías ver algo así:
   
   ![](https://github.com/vcanalesg/curso-r-uahurtado/raw/main/images/r_403_windows.png)

   + Después de descargado el archivo, instálalo como cualquier otro programa.
   


2. **Vayamos ahora por RStudio**. Debes ir a <http://www.rstudio.com/download>

   + Haz click en la versión gratuita de RStudio Desktop.

   + Luego, haz click en el botón de descarga que aparece en la parte superior de la página (te sugerirá la versión a instalar de acuerdo a tu sistema operativo).

   + Luego, abre el archivo descargado y sigue las instrucciones para su instalación.

Si todo resulta bien, cuando abras RStudio deberías ver algo así:

![](https://github.com/vcanalesg/curso-r-uahurtado/raw/main/images/rstudio.png)

### Un poco más sobre R y RStudio

R es un lenguaje y un entorno para la computación estadística y la visualización de datos. Es un proyecto de software libre, que deriva de otro lenguaje llamado S y que fue creado por Robert Gentleman y Ross Ihaka.

¡R ya tiene más de 25 años! Desde entonces se han desarrollado muchas extensiones a su código siendo utilizado para desarrollar una diversidad de tareas y análisis.

RStudio es un entorno de desarrollo integrado. Permite que el trabajo con R sea más sencillo y fluido.

### Instalando paquetes

Un paquete (*package*) es la unidad básica para distribuir código en R. En la actualidad existen aproximadamente 14.000 paquetes.

La primera vez que instalamos R este viene con 14 paquetes base + 29 recomendados.

Para instalar un paquete usamos la función `install.package`. Abre R Studio y copia y pega la siguiente lista de paquetes que utilizaremos durante las sesiones del taller:

```r
install.packages("tidyverse")
install.packages("haven")
install.packages("writexl")
install.packages("guaguas")
```

Cuando se instala un paquete este se agrega a una carpeta en nuestro computador, por lo que no es necesario instalarlo cada vez que iniciamos sesión en R.

```r
# carpeta por defecto donde se guardan paquetes
.Library
```

Lo que sí es necesario es "llamar" las librerías cada sesión para utilizarlas. Para esto se utiliza la función `library`.

```r
# nótese que ahora no es necesario usar las comillas ("") como en la función de instalación
library(tidyverse)
```

Otros paquetes útiles en el manejo de datos (particularmente de encuestas) son:

```r
install.packages("survey")
```

## Programa clases

**Sesión 1: Conociendo R (5 de enero)**

- [Código clases](https://www.dropbox.com/s/aadn8bxg52k7o3t/codigo_en_vivo1.R?dl=0)
- [Presentación](https://docs.google.com/presentation/d/1DjiBGWrG97MHoUhYIrrLye1mkZ7ywTv4hxJHSs78Dts/edit?usp=sharing)

**Sesión 2: Explorar y transformar datos (7 de enero)**

- Código clases
- Presentación