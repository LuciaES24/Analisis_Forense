# A.4.5 - Un Nuevo Mundo

Buscar el sistema operativo de la imagen.

![SO](/img/nuevoMundo1.png)

Ver las variables de entorno hasta encontrar una cifrada.

![envars](/img/nuevoMundo2.png)

![variable](/img/nuevoMundo3.png)

Descifrar la variable.

![descifrada](/img/nuevoMundo4.png)

*Test*  
![test1](/img/nuevoMundo5.png)

Buscar archivos *.kbd* o *.kdbx* que se puedan abrir con la aplicación ***KeePass***.

![filescan](/img/nuevoMundo6.png)

Extraer el archivo encontrado.

![kdb](/img/nuevoMundo7.png)

Al cambiar la extensión del archivo y abrirlo con ***KeePass*** pide una contraseña por lo que se va buscar la imagen que la contiene.

![png](/img/nuevoMundo8.png)

Al abrirla se obtiene la contraseña necesaria.

![contraseña](/img/nuevoMundo9.png)

Abrir ***KeePass*** y copiar la flag.

![keepass](/img/nuevoMundo10.png)

*Test*  
![test2](/img/nuevoMundo11.png)

Buscar el historial del navegador.

![historial](/img/nuevoMundo12.png)

Extraer el historial.

![historial2](/img/nuevoMundo13.png)

Cambiar la extensión del archivo y abrirlo con ***DBBrowser for SQLite*** y encontrar un enlace sospechoso.

![enlace](/img/nuevoMundo14.png)

Al acceder al enlace se debe descargar el archivo *.zip*.

![zip](/img/nuevoMundo15.png)

Para abrir el *.zip* se necesita una contraseña que es el **SHA1** de la flag del test **A.4.4**.

![sha1](/img/nuevoMundo16.png)

*Test*  
![test3](/img/nuevoMundo17.png)