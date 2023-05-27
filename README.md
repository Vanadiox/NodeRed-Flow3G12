# NodeRed-Flow3G12

En este ejercicio vamos a agregar un nuevo nodos: _Text_. Este nodo viene incluido la extensión _Node red dashboard_ instalada desde el primer _flow_

## Requisitos: 

1. Tener instalado y corriendo NodeRED. Sírvase de este [enlace](https://github.com/Vanadiox/NodeRed-Flow1G12) si aún no tiene instalado dichos programas. Se explica la instalación de dicho software 

2. Exportar e importar el _flow_ anterior. Aquí un [enlace](https://github.com/Vanadiox/NodeRed-Flow2G12) para ver cómo hacer eso

3. Tener ya instalado _Node-red-dashboard_. [Aquí](https://github.com/Vanadiox/NodeRed-Flow1G12) la forma de instalarlo

## Instrucciones: 

Una vez importado el proyecto anterior y tener instalado _Node-red-dashboard_, es hora de agregar el nuevo nodo. 

Vaya a la barra de búsqueda en la parte izquierda y escriba "Text". Deberá aparecer algo como esto:

![Imagen 1]()

Arrastre al lienzo y quedaría parecido a esto:

![Imagen 2]()

Ahora, es turno de crear pestañas y grupos. Para ello, diríjase a la barra en la parte derecha de la página. Hasta ahora hemos trabajado en las pestañas de _Info_ y _Debug_. Si mira un poco más a la derecha, verá una flecha hacia abajo, indicando que hay aún más opciones. De clic y abra _Dashboard_.

![Imagen 3]()

Aparecerá un menú, donde se podrá agregar pestañas y dentro de estas, grupos. Para ello, de clic en el botón **+ tab**.

![Imagen 4]()

Aparecerá un objeto llamado _Tab n_ donde _n_ es el número de pestaña. 
Si usted deja flotando el cursor en la pestaña aparecerán algunos botones para agregar grupos, editar la pestaña, editar la presentación. 

![Imagen 5]()

~~~
Nota: Como ya se había creado con anterioridad esta pestaña, aparece con un nombre, distinto a lo que se mencionó con anterioridad. 
~~~

De clic en _edit_ para cambiar nombre. Aparecerá una nueva ventana. Agregue el nombre en el campo _Name_, en este caso "Flow 3: Fecha" y presione _Update_.

![Imagen 6]()

Ahora, hay que crear un grupo. Volvemos a colocar el cursor sobre la pestaña "Flow 3: Fecha" y damos clic en el botón **+ group**.

![Imagen 7]()

Aparecerá un elemento llamado _Group n_, de la misma manera que en las pestañas, la _n_ se refiere al número que aparece al momento de crear este elemento. Del mismo modo, para cambiar el nombre seleccione _edit_ y en el campo _Name_ ponga _Fecha_. Una vez conformes con el nombre, de clic en _Update_.

![Imagen 8]()

Ahora, acomode los nodos. El siguiente es un ejemplo:

![Imagen 9]()

~~~
Nota: Por el momento no se preocupe por el nombre en la imagen. Ya lo configuraremos.
~~~

Para configurar el nuevo nodo, hay que dar doble click en este.

![Imagen 10]()

Si da clic en el apartado _Group_ aparecerán los grupos a los que se puede asociar este nodo. En este caso, seleccione el que acabamos de crear. 

![Imagen 11]()

En _label_, coloque un texto que vaya a hacer alusión a nuestra actividad, ya que se va a mostrar en el resultado final. Una vez nombrado, pulse en _Done_

Ahora, para ver el resultado, vaya al ícono de "abrir nueva pestaña", que tiene forma de un cuadro con una flecha saliendo del centro (nótese que en la siguiente imágen el cursor está señalando el ícono).

![Imagen 12]()

O también puede ir a tecleando **localhost:1880/ui/** o **127.0.0.1:1880/ui/** (las dos direcciones se dirigen al mismo destino)

# Y ¡LISTO!

Se tendría que ver algo como esto: 

![Imagen 13]()

Para detener el proceso, recuerde ir a la pestaña de información y, dependiendo el _flow_, será donde detenga el proceso al presionar el botón de _disable_

## Referencias

[Ejercicio del flow 1](https://github.com/Vanadiox/NodeRed-Flow1G12)

[Ejercicio del flow 2](https://github.com/Vanadiox/NodeRed-Flow2G12)

## Créditos

[Manual realizado por Vanadiox (Kevin H)](https://github.com/Vanadiox)