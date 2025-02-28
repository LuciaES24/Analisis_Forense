# A.4.6 - La guarida del mal

Buscar el sistema operativo de la imagen.

![SO](/img/guardiaDelMal1.png)

Buscar el script malicioso.

![script](/img/guardiaDelMal2.png)

Extraer el fichero para ver su contenido.

![dump](/img/guardiaDelMal3.png)

Modificar la extensión del archivo a *.py* y ver su contenido.

![script2](/img/guardiaDelMal4.png)

Buscar el archivo *vip.txt* que se menciona en el script y extraerlo.

![vip.txt](/img/guardiaDelMal5.png)

Cambiar la extensión del archivo a *.txt* y ver su contenido.

![txt](/img/guardiaDelMal6.png)

Copiar el contenido y decodearlo con ***Cyberchef*** en base al cifrado XOR y base64 encontrados en el script. De esta forma tendremos la primera mitad de la flag.

![cyberchef](/img/guardiaDelMal7.png)

Buscar la imagen que se debe analizar y extraerla.

![jpeg](/img/guardiaDelMal8.png)

Cambiar la extensión del archivo a *.jpeg* y abrirla con la aplicación ***steghide***. La contraseña es la primera mitad de la flag encontrada anteriormente.

![steghide](/img/guardiaDelMal9.png)

*Test*  
![test](/img/guardiaDelMal10.png)
