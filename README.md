# Proyecto-1-Sistemas-Operativos- 
**Integrantes**
Mariana Montoya
Isabel Parra
Sofia Rojo

**Descripción**
Editor de texto desarrollado en C para Linux, basado en el editor `editorEAFIT` proporcionado por el profesor.
El proyecto permite abrir, consultar y modificar archivos de texto directamente desde la terminal, utilizando llamadas al sistema POSIX para el manejo de archivos.
También se integró el editor con el Shell del curso mediante el comando `ed_open`.

**Funcionalidades**
* Apertura y creación de archivos
* Lectura y visualización de líneas
* Agregar y eliminar líneas
* Insertar texto en una posición determinada
* Búsqueda de palabras
* Copia y pegado de líneas
* Consulta de información del archivo
* Manejo de errores
* Integración con el Shell
* Pruebas automatizadas

**Comandos**
El editor cuenta con los comandos correspondientes a los niveles Base, 2 y 3:
* `o [archivo]` — Abrir archivo
* `p [n]` — Mostrar líneas
* `a [texto]` — Agregar texto
* `d [n]` — Eliminar línea
* `q` — Salir
* `i [n] [texto]` — Insertar línea
* `s [palabra]` — Buscar palabra
* `m` — Mostrar información
* `y [n]` — Copiar línea
* `x [n]` — Pegar línea

**Tecnologías utilizadas**
* Lenguaje C
* Linux
* Llamadas al sistema POSIX
* Manejo de archivos
* Procesos y ejecución de programas
* `fork()`, `execvp()` y `waitpid()`
* Memoria dinámica
* Terminal y entrada/salida

 **Pruebas**
El proyecto incluye pruebas automatizadas para verificar el funcionamiento de los comandos, el manejo de errores, la modificación de archivos y la integración con el Shell.
Las pruebas se ejecutan mediante el script `PRUEBAS.sh` y utilizan `pty_driver.c` para simular la interacción con el editor.

**Compilación**
Para compilar el proyecto se utiliza:
make
También se puede utilizar:
make editor
para compilar el editor, y:
make shell
para compilar el Shell.
Para eliminar los archivos generados durante la compilación:
make clean

**Ejecución**
El editor puede ejecutarse directamente desde su carpeta utilizando:
./text_editor archivo.txt
También puede ejecutarse desde el Shell mediante:
ed_open archivo.txt
Una vez abierto el editor, se puede presionar : para ingresar al modo de órdenes y utilizar los comandos disponibles.

**Uso de Inteligencia Artificial**
Este proyecto utilizó herramientas de Inteligencia Artificial como apoyo durante el proceso de desarrollo.
Se emplearon principalmente para:
* Aclarar conceptos relacionados con Sistemas Operativos
* Resolver dudas puntuales de programación
* Apoyar la comprensión de llamadas al sistema y manejo de archivos
* Revisar posibles errores durante el desarrollo

**Consideraciones:**
* La implementación y desarrollo del proyecto fueron realizados por los integrantes.
* Se buscó comprender el funcionamiento del código utilizado.
* La IA se utilizó como herramienta de apoyo y no como reemplazo del trabajo realizado por el equipo.
