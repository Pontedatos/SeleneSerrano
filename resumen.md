# ¿Qué hemos aprendido a lo largo del curso?

A lo largo del curso hemos trabajado con diversas emulaciones de terminales. En mi caso, las utlizadas han sido GitBash y Cygwin. En ellas, hemos aprendido cómo usar comandos y para qué sirven, además de la conexión de estas con la web de GitHub, donde nos creamos un perfil y creamos repositorios propios. 
## Terminal Cygwin
Primero utilizamos una terminal llamada GitBash pero después cambiamos a Cygwin para trabajar con más facilidad y con más comandos. Para descargarla fuimos a la web de Cygwin y pulsamos en instalar. 

Instalación de Cygwin
Tras el proceso de instalación a través de internet, ejecutamos la descarga recién hecha (en su versión:(setup-x86_64.exe)). Ahí decidimos modificar algunas de las cosas que íbamos a instalar para que se añadiesen todas las herramientas que íbamos a usar (para ello cambiamos la opción de _view_ a _full_ para que nos saliesen todas las opciones) como por ejemplo libcur14, wget, ca-certificates-letsencrypt, lynx, nano y openssl. En ellas instalamos la última versión para poder usarlas. Así pudimos tener y trabajar con la emulación de la terminal en nuestro ordenador. 

Previamente, con el uso de GitBash habíamos instalado las opciones de .git para poder trabajar con ello. Además, trabajamos con nano para poder usar un editor de texto dentro de la terminal y lo configuramos y aprendimos a usarlo. Saber, por ejemplo, que este símbolo: ^ hace referencia al botón de control en nuestro ordenador.  

### Preparación del emulador para trabajar con él. 
Al acabar con las instalaciones, procedimos, en clase juntos, a configurar la nueva terminal: Cygwin. Lo que hicimos de nuevo fue configurar el git y crear el alias de nuevo. El alias que creamos fue el de 'micasa'. En mi caso, este comando lleva a: /c/Users/selen/OneDrive/Escritorio/PERIODISMO-DE-DATOS/. 


## Versión del lenguaje de SHELL utilizado:
Al idioma de la terminal se le denomina Shell. Según la página web de programador clic [(link aquí)](https://programmerclick.com/article/20661147775/), Shell es, además de un intérprete de comandos, un lenguaje de programación muy poderoso, fácil de escribir, fácil de depurar y flexible. Shell es un lenguaje de programación para interpretación y ejecución .Los comandos del sistema Linux se pueden llamar directamente en Shell.

Para poder ver cuál era la versión del lenguaje de Shell con la que hemos estado trabajando, comprobé a través de Cyngwin. Para hacerlo, usé el comando echo $0 que sirve para ver precisamente, si se usa dentro de shell, para ver cuál es la versión de shell que se está usando. La respuesta fue que lo que se está usando es Bash. Bash es el lenguaje de Shell más popular, pese a que existen otros como JScript o AppleScript. 


## ¿Cuál es el valor de la variable de entorno PATH?
Path son las rutas que el odenador tiene que seguir. Es decir, el proceso paso a paso por el que tiene que pasar el ordenador para llegar a los archivos que le demandamos. Las rutas que se siguen en mi ordenador para llegar a los programas instalados son todas estas:/usr/local/bin:/usr/bin:/cygdrive/c/Program Files (x86)/Intel/iCLS Client:/cygdrive/c/Program Files/Intel/iCLS Client:/cygdrive/c/WINDOWS/system32:/cygdrive/c/WINDOWS:/cygdrive/c/WINDOWS/System32/Wbem:/cygdrive/c/WINDOWS/System32/WindowsPowerShell/v1.0:/cygdrive/c/Program Files (x86)/Intel/Intel(R) Management Engine Components/DAL:/cygdrive/c/Program Files/Intel/Intel(R) Management Engine Components/DAL:/cygdrive/c/Program Files (x86)/Intel/Intel(R) Management Engine Components/IPT:/cygdrive/c/Program Files/Intel/Intel(R) Management Engine Components/IPT:/cygdrive/c/WINDOWS/System32/OpenSSH:/cygdrive/c/Program Files/Git/cmd:/cygdrive/c/Users/selen/AppData/Local/Microsoft/WindowsApps:/cygdrive/c/Users/selen/bin
Sin embargo, las rutas no tienen porqué ser dentro de un ordenador, también pueden ser dentro de internet. 

Path es una variable de entorno. 
### Comandos utilizados y ejemplos
Los comandos que hemos usado son numerosos pero los que más hemos utilizado son:
- ls: para ver los archivos que hay dentro de la carpeta en la que estamos. 
- pwd: para ver dónde nos encontramos. 
- cd: para cambiar de directorio. 
- cp: para copiar datos. 
- micasa: una vez establecido el alias para la ruta que más hemos usado.
- mkdir: para la creación de nuevas carpetas. 
Además de esos, hemos usado en repetidas ocasiones todas las que hacen referencia a git, explicadas en [este](https://github.com/Pontedatos/SeleneSerrano/blob/main/metodologia.md) archivo. 
