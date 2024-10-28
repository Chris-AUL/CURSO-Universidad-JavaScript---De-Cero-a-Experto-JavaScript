# Instalación de NodeJS

A continuación se describirá como descargar e instalar *NodeJS* en *Windows 10 Home Edition*

## Descargar NodeJS

Como primer paso, desde nuestro navegador web favorito, buscar node js

![](img/IMG_35.png)

Entre las diversas opciones que nos brinda el buscador, seleccionamos la página oficial de *NodeJS*:

[https://nodejs.org](https://nodejs.org)

![](img/IMG_36.png)

Dentro de la página oficial de *NodeJS*, presionamos en el botón que dice:
**Download Node js(LTS)**, **LTS** significa que es una versión con soporte a largo plazo (*Long Term Support*).

![](img/IMG_37.png)

Esto provocará que se descargue la última versión de *NodeJS* en nuestro equipo

![](img/IMG_38.png)

Habiéndose descargado en nuestro equipo el instalador, ir a *Administrador de archivos* > *Descargar*

![](img/IMG_39.png)

![](img/IMG_40.png)

## Instalación de NodeJS

Desde aquí en descargas, dar doble clic sobre el instalador, esto provocará que el instalador se inicie en nuestro equipo

Nos indicará que *NodeJS* se instalará en nuestro equipo, dar clic en **Next.**

![](img/IMG_41.png)

En principio, nos mostrará el acuerdo de licencia del usuario final (EULA) para el uso de *NodeJS*, el cual opcionalmente podemos leer y obligatoriamente debemos aceptar. Damos clic en el marcador que dice:

**I accept the terms in the license Agreement**

y luego dar clic en **Next**

![](img/IMG_42.png)

![](img/IMG_43.png)

Luego preguntará la carpeta donde se desea guardar los ficheros de instalación y uso de *NodeJS*. Por defecto ofrece una ruta indicada en la partición que contiene el Sistema Operativo, pero si tu experiencia lo permite y así lo deseas, puedes seleccionar otra ruta para estos ficheros.

Seleccionada la ruta, dar clic en **Next**

![](img/IMG_44.png)

Nos mostrará las acciones de preparación en la instalación de *NodeJS* que el instalador tiene definidas por defecto. Si así lo deseas, puedes modificar esto.

Luego de aceptar cada acción, dar clic en **Next**.

![](img/IMG_45.png)

Por terminar, pregunta si desea instalar *Chocolatey*. Esto dependerá de los usos que se le darán a *NodeJS*, así que depende del usuario final.

Si el motivo es para aprender *JavaScript* y *NodeJS*, dejar desmarcado, de lo contrario, analizar si tu profesión lo necesita para añadir esta instalación en el proceso.

Dar clic en **Next**.

![](img/IMG_46.png)

Preguntará si estamos preparados para realizar la instalación. Si es correcto, presionar **Install**. Para cancelar dar en **Cancel**

![](img/IMG_47.png)

Si escojemos iniciar la instalación, mostrará una barra de *Status*

![](img/IMG_48.png)

Al terminar el proceso, mostrará la última ventana, la cual indica que la instalación ha sido completada. dar clic en **Finish**

![](img/IMG_49.png)

Para comprobar la instalación, ejecutar una consola de *PowerShell* y ejecutar el comando:

``` PowerShell
node --version
```

Esto nos mostrará la versión de *NodeJS* que fue instalada:

![](img/IMG_50.png)