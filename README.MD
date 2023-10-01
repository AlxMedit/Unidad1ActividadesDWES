# PRÁCTICAS DWES
## Alejandro Vaquero Abad

---

### ÍNDICE
- [Actividad 1](#actividad-1)
- [Actividad 2](#actividad-2)
- [Actividad 3](#actividad-3)
- [Actividad 4](#actividad-4)

---

### Actividad 1
**Objetivo: Instalar y configurar un paquete software que integre Apache, PHP y MSQL.**

Como se aprecia en las capturas el XAMPP está activo y funcional en el equipo, phpmyadmin es accesible y la web de pruebas también

![Imagen1](Practica1Img/1.png)

![Imagen2](Practica1Img/2.png)

### Actividad 2
**Objetivo: Instalación y configuración de un entorno web utilizando una máquina virtual.**

Primero updateamos todos los paquetes del servidor para obtener las versiones correctas de los programas a usar.

![Imagen1](Practica2Img/1.png)

Posteriormente instalamos los paquetes necesarios

![Imagen2](Practica2Img/2.png)
![Imagen2.1](Practica2Img/2.1.png)

![Imagen3](Practica2Img/3.png)
![Imagen3.1](Practica2Img/3.1.png)

![Imagen4](Practica2Img/4.png)
![Imagen4.1](Practica2Img/4.1.png)

![Imagen5](Practica2Img/5.png)

Una vez tenemos todos los paquetes instalados, accederemos mediante un plugin de ssh de visual studio a la máquina, y habilitamos permisos de uso a la carpeta donde trabajaremos

![Imagen6](Practica2Img/6.png)
![Imagen7](Practica2Img/7.png)
![Imagen8](Practica2Img/8.png)

Posteriormente vemos la ip del servidor y accedemos a ella desde nuestro equipo

![Imagen9](Practica2Img/9.png)
![Imagen9.1](Practica2Img/9.1.png)

Comprobamos que todos los servicios están instalados y activos

![Imagen10](Practica2Img/10.png)
![Imagen10.1](Practica2Img/10.1.png)
![Imagen10.2](Practica2Img/10.2.png)
![Imagen10.3](Practica2Img/10.3.png)

### Actividad 3
**Objetivo: Instalación y configuración de un entorno web utilizando una máquina virtual.**

Instalamos Vagrant

![Imagen0](Practica3Img/0.png)

Usamos el comando vagran box add laravel/homestead y elegimos la opción 3 (virtualbox)

![Imagen1](Practica3Img/1.png)
![Imagen2](Practica3Img/2.png)

Iniciamos el docker

![Imagen3](Practica3Img/3.png)

Le habilitamos el servicio ssh

![Imagen4](Practica3Img/4.png)

Modificamos el fichero "homestead.yml" situado en la carpeta donde lo instalamos

![Imagen5](Practica3Img/5.png)

Levantamos el vagrant

![Imagen6](Practica3Img/6.png)

Modificamos el fichero hosts

![Imagen7](Practica3Img/7.png)

Nos conectamos por ssh

![Imagen8](Practica3Img/8.png)

Accedemos a la carpeta home/vagrant/code/public que es donde debemos almacenar los fichero que queremos acceder y generamos un codigo .html

![Imagen9](Practica3Img/9.png)

![Imagen10](Practica3Img/10.png)

Accedemos a la dirección "homestead.test" (que configuramos en el fichero hosts del sistema) y podemos ver que la web ya es accesible

![Imagen11](Practica3Img/11.png)

### Actividad 4
**Objetivo: Crear un entorno virtual para desarrollo en el lado del servidor.**

Accedemos al Eclipse, seleccionaremos preferencias, y añadir un entorno de runtime

![Imagen1](Practica4Img/1.png)

![Imagen2](Practica4Img/2.png)

Seleccionamos el servidor apache tomcat y elegiremos la opción "Create a new local server"

![Imagen3](Practica4Img/3.png)

Ahora creamos un proyecto de web dinamico y dentro de este crearemos un "JSP file", posteriormente crearemos un servlet

![Imagen4](Practica4Img/4.png)

![Imagen5](Practica4Img/5.png)

![Imagen6](Practica4Img/6.png)

![Imagen7](Practica4Img/7.png)

![Imagen8](Practica4Img/8.png)

![Imagen9](Practica4Img/9.png)

Le daremos run as >> run on server, seleccionaremos el servidor tomcat de apache que anteriormente habíamos configurado y podremos acceder

![Imagen10](Practica4Img/10.png)

![Imagen11](Practica4Img/11.png)

Accedemos al proyecto en la red, pondremos el número 3 para probar, le daremos a enviar y vemos como nos enseña el doble de ese número

![Imagen11](Practica4Img/12.png)

![Imagen11](Practica4Img/13.png)
