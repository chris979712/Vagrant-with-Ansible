# Vagrant-with-Ansible
Actividad de la E.E Desarrollo de aplicaciones, en la cual se desarrollo la configuración de una máquina virtual a través de vagrant y de la ayuda de Ansible, para poder levantar un servidor; usando Ubuntu server 22.0.4

Requerimientos:
Para poder ejecutar el proyecto, es necesario tener instalado Vagrant y Virtual Box (o cualquier otro virtualizador)

Procedimiento de ejecución:
1.- Clonar el repositorio
2.- Abrir la línea de comandos en la ruta donde se encuentra el vagrantfile
3.- Ejecutar el comando "vagrant up"
4.- Ejecutar el comando "vagrant ssh" para poder abrir nuestra máquina virtual
5.- Verificar si se realizó correctamente el aprovisionamiento, a través del chequeo de estado de nuestro servidor apache con el comando "systemctl status apache2"
6.- Cerrar el chequeo del estado de servidor con "ctrl+c"
7.- Obtener la ip públic de nuestro servidor ejecutando el comando "ip a"
8.- En un navegador web escribir lo siguiente http://DireccionIPDelServidor:80
9.- Disfruta :D
