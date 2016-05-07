# OpenSSH-Installer-Script PRE-ALPHA

The Script for n00bs and lazy people 

* Caracteristicas
  * -Soporte Multidiestro (De momento, Gentoo, Ubuntu y Debian)
  * -Sistema de Integridad de los Ficheros
  * -Soporte con su,sudo y gksu
  * -Modo de Configuracion Automatizada (WIP!)
  * -Modo Recuperacion en caso de corrupcion de los Ficheros.(WIP!)

* Ficheros:
 * Tools/generate-hash -- Heramienta que genera Hashes de forma automatizada y remplaza el array de hashes del fichero check
 * files/* -- Librerias con Funciones
 * OpenSSH-Installer-Script -- Programa Principal.

* TO-DO:
  * Crear un Branch adicional para el Trabajo y dejar Master para seguir Trabajando. 
  * MAS ESTILO!!!!!!!!!!! MAS COLORES!!!!!!!!!!!!!!!!!
  * Mejorar Estructura de los Ficheros.
  * Modo Unsupported/LFS: Compilacion.
  * Modo Actualizacion.
  * Modo Automatizado (Lee un fichero con opciones prestablecidas).
  * Checkception: AKA Control de Ficheros en modo lunatico.
  * Integrar Soporte con wget/curl
  * Integrar pv.
  * Introducir Soporte Multi-Idioma (Basado en los Locales de las Variables del Sistema)
  * Activar/Desactivar Servicio u Activar arrancar con el Sistema o Desactivar.
  * Comentar el Codigo
  * Añadir Sistemas Operativos Mainstream (Red Hat Family, Suse Familiy, Arch Linux Family)

* Requisitos Minimos de Caracteristicas (Esto es una Tarea xd):
 * La opción 1 comprobará primero que el paquete no está instalado. Actualizará los repositorios e instalará el paquete. - OK
 * La opción 2 solicitará al usuario el nombre de dos ficheros, uno que contendrá nombres de usuario (separados por espacios en blanco o en líneas diferentes) a los que se permitirá hacer ssh. El segundo fichero contendrá las direcciones ip a las que se permite hacer ssh (separadas por espacios en blanco o en líneas diferentes). - WIP!
 * La opción 3 incorporará las direcciones ip permitidas al fichero allow. El dený deberá configurarse para que sea lo más seguro posible. - .
 * La opción 4 desinstalará el servicio y eliminará la referencia a ssh en el fichero allow (Esto último opcional). - .
* Deberás emplear/realizar:
  * -Una función que reciba parámetros - OK - (De momento, generate-hash y su funcion algoritm, y del Programa la funcion su-metodo)
  * -2 o más ficheros script - OK - TODO ESTA DIVIDIDO, MUAJJAJAJJAJJAJJAJAJAJJAJA
  * Control de ficheros - OK - Powered by LFC (Lunatic File Control)
