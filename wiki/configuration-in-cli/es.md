
## Guardando la configuración

**Esta función está disponible a partir de la versión: `3.3`**

Si prefiere la interfaz de línea de comandos (CLI) a la interfaz gráfica de usuario (GUI), SaveDesktop, además de guardar la configuración en la GUI, le permite guardar la configuración en la CLI.

### Entonces, ¿cómo proceder?
**1. Abrir un terminal**

Puede abrirlo desde el menú de aplicaciones, o usando el atajo de teclado Ctrl+Alt+T.

**2. Introduce el comando**

Introduce el siguiente comando en el terminal:
- si tienes SaveDesktop instalado como un paquete de Flatpak, utiliza lo siguiente:
     ```
     flatpak run io.github.vikdevelop.SaveDesktop --save-now
     ```
- si tienes SaveDesktop instalado como un paquete Snap o nativo, utiliza: 
     ```
     savedesktop --save-now
     ```


Al utilizar este método, utiliza parámetros de la GUI, concretamente parámetros del modo de guardado periódico, como el formato del nombre de archivo y la carpeta seleccionada para los archivos de guardado periódico. Puede guardar la configuración con este método siempre que lo desee, independientemente del intervalo de guardado periódico seleccionado.

## Importar la configuración

**Esta función está disponible a partir de la versión: `3.2.2`**

Además de importar la configuración en la GUI, SaveDesktop también le permite importar la configuración en la interfaz de línea de comandos (CLI), que puede utilizar en caso de que su entorno de escritorio se rompa.

### Entonces, ¿cómo proceder?
**1. Abrir un terminal**

Puede abrirlo desde el menú de aplicaciones, o usando el atajo de teclado Ctrl+Alt+T.

**2. Introduce el comando**

Introduce el siguiente comando en el terminal:
- si tienes SaveDesktop instalado como un paquete de Flatpak, utiliza lo siguiente:
     ```
     flatpak run io.github.vikdevelop.SaveDesktop --import-config /path/to/filename.sd.tar.gz
     ```
- si tienes SaveDesktop instalado como un paquete Snap o nativo, utiliza: 
     ```
     savedesktop --import-config /path/to/filename.sd.tar.gz
     ```

**Nota**:
- en lugar de `/path/to/filename.sd.tar.gz`, introduzca la ruta al archivo de configuración que desea importar, por ejemplo: `/home/user/Downloads/myconfig.sd.tar.gz`



{% include footer.html %}
