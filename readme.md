# Manipulando Archivos.

- ls -lS .- S es de size, ordena por tamaño los archivos.

* ls -lr .- r es de reverse, los lista en forma reversa.

* mkdir "Mi directorio" .- Las comillas sirven para crear los archivos con espacio.

* touch archivo1 archivo2 archivo3 .- Esta forma crea de manera rapida varios archivos, sirve de igual forma con mkdir.

* cp archivo1 archivo1_copia .- Copia el archivo.

* mv archivo1_copy .. .- Mueve el archivo un directorio antes.

* mv archivo1_copy archivo1renombrado .- Renombra el archivo

* rm archivo1renombrado .- Remueve o borra el archivo o directorio.

* rm -i archivo1renombrado.- Pregunta de forma interactiva si realmente quieres borrar el archivo.

* rm -r directorio .- Remueve un directorio y todo su contenido.

# Explorando contenido de archivos

- head archivo.txt .- muestra las primeras 10 lineas del archivo.

- head -n 20 archivo.txt .- muestra las primeras 20 lineas del archivo.

- tail archivo.txt .- muestra las ultimas 10 lineas del archivo.

- tail -n 20 archivo.txt .- muestra ñas ultimas 20 lineas del archivo.

- less archivo.txt .- interfaz amigable para explorar el archivo.

# Definición de un Comando

- Puede ser un programa ejecutable.
- Un comando de utilidad de la shell.
- Una función de shell.
- Un alias.

* type cd .- Nos muestra el tipo de comando de las 4 opciones anteriores.

* alias l="ls -alt" .- Crea un comando, sin embargo son temporales.

* help cd .- Muestra la ayuda para los comandos.

* man cd .- Muestra el manual del comando necesitado.

* info cd .- Muy similar al de "man".

* whatis cd .- Muestra una breve descripcion de lo que hace el comando.
