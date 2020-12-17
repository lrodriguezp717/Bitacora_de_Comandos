# Bitacora_de_Comandos
## Lista de Comandos Vistos durante el curso
## Comando Ping
### El comando Ping se utiliza para para poder verificar si existe una respuesta de un host específico
### Se escribe de la siguiente forma ping y el nombre del host por ejemplo google.com
### ejemplo: ping google.com
## Comando Clear
### Este comando se utiliza para limpiar la pantalla de la terminal unicamente se debe escribir "clear"
### ejemplo: clear
## Comando pstree
### Este comando al utilizarlo, retorna todos los procesos en ejecución, mostrados en una estructura de árbol
### ejemplo:pstree
## Comando ps -aux
### Este comando se utiliza para mostrar información acerca de los procesos en ejecución, si se utiliza de esta forma por lo general muestra el usuario, el ID de proceso
### el porcentaje de CPU y memoria que utiliza, tiempo, comando entre otros datos importante relacionados con cada proceso
### ejemplo: ps -aux
## Comando man
### Este comando funciona como un manual para cada comando dentro del sistema operativo, muestra una descripción sobre para que sirve además de información sobre la sintaxis y en que casos utilizarlo, también muestra ejemplos que pueden guiar al usuario a la hora de utilizar el comando
### ejemplo: man pstree
## Comando History
### Este comando se utiliza para poder visualizar el historial de comandos escritos y ejecutados en la terminal por el usuario
### ejemplo: history
## Comando Whoami
### El comonado whoami se utiliza para poder imprimir el nombre del usuario que está haciendo uso del sistema en ese preciso momento 
### ejemplo: whoami
## Comando --version
### El comando --version se utiliza para poder imprimir toda información relacionada con la versión actual de una aplicación o comando instalado en el sistema entre esa 
### información se encuentra el número de versión, características de esa versión, desarrolladores, entre otros
### ejemplo: firefox --version
## Comando Top
### El comando top se utiliza con el fin de visualizar el estado del sistema y todos los procesos dentro de el, se pueden observar datos similares a los que retorna el 
### comando ps -aux, pero a diferencia de este, muestra datos en tiempos real, lo cual es bastante util ya que ayuda a conocer el estado actual de nuestro servidor
### ejemplo: top
## Comando Htop
### El comando htop, es bastante parecido al comando top debido a que también se utiliza para observar procesos dentro del sistema, pero a diferencia de este, es mucho más
### visual, el usuario puede moverse vertical y horizontalmente para ver los procesos. También cuenta con opciones interactivas como filtrar procesos, ver los procesos en
### formato de árbol, configurar y matar procesos. Es muy similar al task manager de Windows 10, ya que muestra gráficos sobre el rendimiento del sistema, como por ejemplo el
### el porcentaje de uso de componentes como CPU y memoria, entre otros.
### ejemplo: htop
## Comando Sudo
### El comando sudo se utiliza para poder ejecutar comandos o progromas con todos los privilegios de seguridad que posee el supeusuario o usuario administrador 
### en resumen un usuario común puede utilizar sudo para así ejecutar comandos que están restringidos y que unicamente puede ejecutar el usuario administrador
### ejemplo: para poder actualizar el sistema operativo se utiliza sudo apt upgrade
## Comando Cat
### Este comando se utiliza para poder visualizar el contenido de un archivo específico, por ejemplo de un archivo de texto
### ejemplo: cat HolaMundo.txt (devuelve todo lo escrito en este archivo)
## Comando Tail
### Es similar a cat con la diferencia que se utiliza para unicamente visualizar las últimas diez lineas del archivo
### ejemplo: tail documento.txt (devuelve las últimas diez lineas de documento.txt)
## Comando Head
### Es identico al comando tail, pero a diferencia de este, en vez de retornar las últimas diez lineas del archivo devuelve las primeras diez lineas
### ejemplo: head documento.txt (retorna las primeras diez líneas de documento.txt)
## Comando cd
### El comando cd se utiliza para poder ingresar a un directorio específico, se coloca cd y la ruta a donde se quiere acceder
### ejemplo: cd /home/lrodriguezp717/Descargas
## Comando ls 
### Se utiliza para poder observar todo el contenido que se encuentra dento de un directorio específico
### ejemplo: ls /home/lrodriguezp717/Descargas
## Comando pwd
### El comando pwd retorna el nombre del directorio donde el usuario se encuentra trabajando actualmente
### ejemplo: pwd 
## Comando cp
### El comando cp se utiliza en casos donde el usuario quiera copiar un archivo o un directorio, se escribe cp nombre de archivo y el destino a donde se quiere copiar
### ejemplo: cp Calculadora.txt /home/lrodriguezp717/Descargas (se copia este archivo a este directorio)
## Comando mv
### El comando mv se utiliza para renombrar o mover archivos a un directorio, si se escribe mv y un nuevo nombre se renombra, si se escrive mv y una ruta se mueve el
### archivo a ese directorio
### ejemplo: mv Calculadora.txt Calculadora2.txt (se renombra el archivo)
## Comando rm
### El comando rm se utiliza para eliminar un archivo o directorio específico
### ejemplo: rm Documento.txt (se elimina el archivo)
## Comando chmod 777
### El comando chmod 777 se utiliza para concederle todos los permisos a un archivo se escribe el comando y el nombre del archivo
### ejemplo: chmod 777 Documento.txt
## Comando passwd
### Este comando se utiliza para cambiar la contraseña de un usuario, si es un usuario normal solo puede cambiar la suya, mientras que con un usuario administrador se 
### pueden cambiar las contraseñas de otros usuarios
### ejemplo: passwd o también sudo passwd nombreUsuario para cambiar la contraseña de un usuario con permisos de superusuario
## Comando chmod +x
### Este comando se utiliza para poder agregar permisos de ejecución a un archivo específico, por ejemplo a un script que se quiera ejecutar por medio de un shell 
### como por ejemplo bash
### ejemplo: chmod +x calculador.sh
## Comando reboot
### El comando reboot se utiliza para reiniciar el equipo inmediatamente, sin preguntar nada
### ejemplo: reboot
## Comandos shutdown y shutdown now
### El primero de estos apaga el equipo sin preguntar nada al usuario, el segundo lo apaga inmediatamente
### ejemplo: shutdown       shutdown now
## Comando Tar
### El comando tar es utilizado para poder comprimir archivos, tiene variaciones por ejemplo:
### tar -cvf archivo.tar se utiliza para crear un nuevo archivo tar
### tar -xvf archivo.tar se utiliza para descomprimir un archivo tar
## Comando hostname
### se utiliza para poder conocer el nombre de nuestro equipo
### ejemplo: hostname
## Comando wget
### Este comando es utilizado para poder descargar, archivos, paquetes, aplicaciones o cualquier contenido que el sistema operativo requiera, desde servidores web, antes
### de utilizarlo se debe instalar dentro del sistema por medio del comando apt-get install wget
### ejemplo: wget https://wordpress.org/latest.zip
## Comando zenity --info --text
### Este comando se utiliza para poder desplegar un mensaje en pantalla, por ejemplo una alerta en caso de que un proceso haya salido mal
### ejemplo: zenity --info --text="Hola Mundo"
## Comando zenity --entry --text
### Este comando se utiliza para desplegar una ventana donde el usuario puede ingresar información, después esta información puede ser asignada a variables, este comando
### se utiliza mucho en scripts
### ejemplo: nombre=$(zenit --entry --text="Digite su nombre") (muestra la ventana, el usuario ingresa su nombre y lo almacena en esta variable)
## Comando echo
### Se utiliza para poder imprimir un texto o una variable en la terminal
### ejemplo: echo $nombre (imprime la información almacenada en la variable nombre)
## Comando zenity --password
### Se utiliza para desplegar una ventana donde el usuario puede ingresar una contraseña
### ejemplo: zenity --password
## Comando zenity --question
### Se utiliza para desplegar una ventana con una pregunta, donde el usuario puede escoger si o no
### ejemplo: zenity --question
## Comando sudo add apt repository
### Se utiliza para agregar un repositorio nuevo dentro del sistema operativo
## Comando sudo apt update
### Se utiliza para actualizar toda la lista de paquetes dentro del sistema operativo
## Comando sudo apt uprade
### Se utiliza para poder actualizar el sistema operativo y no solo eso sino también se ejecutan todas las posibles actualizaciones, ya sea de aplicaciones o de otro tipo
## Comando sudo rm-R
### Borra todos los archivos del usuario root, nunca es recomendable ejecutarlo
## Comando file
### Se utiliza con el fin de conocer el tipo de archivo con el cual se relaciona un archivo específico
### ejemplo: file HolaMundo.txt (este comando retorna que el archivo es de tipo UTF-8 unicode text)
## Comando sudo chown root 
### Este comando se utiliza para poder cambiar el propietario de cierto archivo específico al usuario root
### ejemplo: sudo chown root Documento.txt
## Comando kill -9
### Se utiliza para poder matar un proceso específico, se coloca el comando seguido del id del proceso que se desea matar
### ejemplo: kill -9 10
## Comando du -h
### Se utiliza para poder obtener información sobre cuanto espacio en memoria está utilizando un archivo
### Ejemplo: du -h Documento.txt
## Comando stat 
### Este comando retorna diferente datos relacionados con un archivo, por ejemplo, tamaño, acceso, fecha de cambios, entre otros
### Ejemplo: stat Documento.txt
## Comando df -h
### se utiliza para poder saber el sistema de archivos montados
## Comando bash
### Este comando se utiliza para poder ejecutar scripts por medio del interprete de comandos (shell) bash, el que viene por defecto en Linux, solo se debe colocar bash y
### el nombre del script a ejecutar, el script debe ser de tipo sh
### ejemplo: bash Calculadora.sh
## Comando curl -X GET -L
### Se utiliza para poder agregar información a una hoja de cálculo en Google
### Ejemplo: curl -X GET -L script.google.com/macros/s/AKfycbztjXtmKGK6nSZ2jyqwKvvFWrsT0qEmyxKvr15SjFCVQzy83TQ/exec?data=$nombre
## Comando sudo apt install
### Se utiliza para poder instalar una aplicación o paquete que el sistema operativo requiera
### ejemplo: sudo apt install python3
## Comando sudo apt search
### Se utiliza para poder buscar paquetes desde la terminal
### ejemplo: sudo apt search nodejs (retorna una lista de todos los paquetes nodejs)
## Comando more
### Permite visualizar el contenido de un archivo linea por linea
### ejemplo: more Documento.txt
## Comando ip addr
### Retorna la dirección ip de nuestro equipo
## Comando docker pull
### Se utiliza para obtener imágenes de sistemas operativos o para descargar repositorios subidos a docker hub
### ejemplo: docker pull ubuntu
## Comando docker images
### muestra todas las imágenes de sistemas operativos instaladas 
### ejemplo: docker images, después de esto despliega la información
## Comando sudo docker run -it
### Se utiliza paara poder ejecutar una de las imagenes descargadas 
### ejemplo sudo docker run -it ubuntu (crea una nueva máquina virtual ubuntu e ingresa a la terminal de esta)
## Comando cat /etc/os-release
### En docker se utiliza para saber información sobre la máquina virtual que se esté utilizando en ese momento
## Comando uname -a
### Se utiliza para poder saber el kernel que utiliza una máquina virtual que se esté usando en docker
## Comando exit
### Se sale del contenedor que se esté utilizando en docker
## Comando docker ps -a
### Despliega todos los contenedores que se están corriendo en docker
## Comando docker start
### Se utiliza para poder inicializar un contenedor específico, solo se coloca docker start y el id del contenedor que se desea inicializar
### ejemplo: docker start 2254f8f6c0e7 
## Comando docker attach
### Se utiliza para poder utilizar o ingresar a la terminal de un contenedor en ejecución, solo se coloca docker attach y el id del contenedor
### ejemplo: docker attach 2254f8f6c0e7
## Comando docker login -u
### Se utiliza para poder realizar un login en docker, solo se coloca docker login -u y el nombre de usuario de una cuenta en docker hub
### ejemplo: docker login -u  lrodriguezp717
## Comando docker push
### Se utiliza para poder subir un repositorio a docker hub, se debe además agregar el nombre del repositorio
### ejemplo: docker push Leo/Sistemas_Operativos
## Comando docker commit -m
### Se utiliza para poder guardar un repositorio que posteriormente puede ser subido a docker hub, se coloca el comando y el nombre del repositorio que se quiere guardar
### docker commit -m 







