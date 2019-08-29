# 1_3_configuracion_de_Java
Proyecto HelloWorld

DESCRIPCIÓN
El objetivo del proyecto es comprobar la correcta configuración de Java para NetBeans y JDK 8, de igual forma la configuración para compilar y correr programas Java en prompt de Windows.
El programa imprime Hello World en la consola de NetBeans y en prompt de Windows.

CONFIGURACIÓN DE WINDOWS 10

Para compilar y correr programas escritos en Java con Windows prompt, primero debe asegurarse que se ha instalado Java Development Kit (en cualquier versión) previamente, una vez instalado JDK, en el explorador de archivos se ubica el ícono "Este equipo", haciendo clic derecho se busca y selecciona la opción "Propiedades".

![Configuración Java para Windows 1](https://user-images.githubusercontent.com/54320247/63960930-38791100-ca55-11e9-8a89-56806ab3af65.jpg)

En la ventana "Sistema" se busca la opción "Configuración avanzada del Sistema" y se ingresa.

![Configuración Java para Windows 2](https://user-images.githubusercontent.com/54320247/63960938-40d14c00-ca55-11e9-8314-9bcca92a4b14.jpg)

Se abrirá una ventana de nombre "Propiedades del sistema", en la pestaña "Opciones avanzadas" se da clic sobre "Variables de entorno...".

![Configuración Java para Windows 3](https://user-images.githubusercontent.com/54320247/63960939-4169e280-ca55-11e9-9954-6662cc68dec4.jpg)

En la ventana "Variables de entorno" se busca y selecciona en el cuadro "Variables del sistema" la variable "Path", posteriormente se da clic sobre la opción "Editar...".

![Configuración Java para Windows 4](https://user-images.githubusercontent.com/54320247/63960940-4169e280-ca55-11e9-95a9-3f5dab2fa84d.jpg)

En el cuadro "Editar variable de entorno" se selecciona la opción "Nuevo" y en la casilla se coloca la dirección C:\Program Files\Java\jdk1.8.0_221\bin y se da clic en Aceptar.

![Configuración Java para Windows 5](https://user-images.githubusercontent.com/54320247/63960941-4169e280-ca55-11e9-80d3-b456ef5f3445.jpg)

Una vez hecho eso, se da clic en "Nueva..." y se crea la variable "CLASSPATH" con el valor de variable ";" (punto y coma) y se da clic en Aceptar.

![Configuración Java para Windows 6](https://user-images.githubusercontent.com/54320247/63960942-4169e280-ca55-11e9-883d-53b75e4fa45f.jpg)
