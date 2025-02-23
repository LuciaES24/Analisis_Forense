# A.4.4 - La suerte del principiante

Buscar el sistema operativo.

![SO](/img/suerte1.png)

En base a la información que se da en el supuesto, los procesos más importantes son cmd, paint y winrar.

Buscar los comandos ejecutados en el cmd.

![cmd](/img/suerte2.png)

![cmd](/img/suerte3.png)

*Test*  
![paint1](/img/suerte5.png)

A partir del PID del proceso del Paint, volcar los ficheros de dicho proceso.

![paint1](/img/suerte4.png)

Cambiar la extensión a *.data* y abrirlo con la herramienta GIMP. Ajustar el alto y el ancho de la foto hasta poder identificar lo que está escrito.

*Test*  
![rar](/img/suerte6.png)

Buscar un archivo *.rar* sospechoso.

![rar](/img/suerte8.png)

Sacar los ficheros del archivo *.rar*.

![dumpfiles](/img/suerte9.png)

Cambiar la extensión del archivo a *.rar*. Para extraer el fichero hace falta una contraseña, por lo que hay que extraer las del sistema.

![dumpfiles](/img/suerte7.png)

Poniendo el hash en mayúscula extraer los ficheros de la carpeta comprimida. En la foto se encuentra la flag 3.

*Test*  
![rar](/img/suerte10.png)