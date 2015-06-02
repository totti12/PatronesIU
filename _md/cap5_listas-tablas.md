# Listas y tablas

**Recopilado por**:  José Alvarado Monge

## Selector de dos paneles

Este patrón consiste en mantener dos paneles en la ventana principal con el fin de mantener una lista de elementos en uno de ellos y al seleccionar de estos elementos el segundo panel mostrará sus contenidos.

Es muy útil cada vez que se tiene una lista de ítems que mostrar y cada uno de ellos tiene contenido o información relevante asociado. Permite que el usuario mantenga esa lista en plena vista todo el tiempo y pueda navegar por sus elementos fácil y rápidamente.

Al tener un área dedicada a cambiar, el usuario tiene mayor facilidad concentrándose en esa área, en oposición a cambiar toda la ventana lo que demandaría una mayor atención por parte del usuario. 

La desventaja aquí es q se necesita suficiente espacio en pantalla, en dispositivos que no llegan a ese requerimiento pueden usarse alternativas como es la Exploración en una sola ventana.

Ejemplos comunes son las aplicaciones de correo electrónico, ventanas de exploradores de archivos e interfaces de gestores de imágenes.

## Exploración en una sola ventana

Una alternativa al patrón de Selector de dos paneles descrito arriba. Aquí la forma de mostrar los contenidos toma todo el espacio disponible, tanto la lista como la vista asociada a cada elemento.

La idea es que en muchas ocasiones no se cuenta con mucho espacio, como sucede con muchos dispositivos móviles pequeños o “widgets”. De igual manera puede suceder que el contenido de ambas vistas es muy grande aun teniendo mucho espacio disponible, puede beneficiarse de usar todo ese espacio para mostrar la información como es el caso de foros en línea.

La desventaja es que el usuario tiene que estar devolviéndose a la pantalla de la lista para pasar de un elemento a otro, para ayudar con eso se pueden agregar funcionalidades para navegar al siguiente y al anterior.

Los ejemplos más comunes son las aplicaciones para dispositivos móviles pequeños que disponen de un área relativamente pequeña. Asimismo los foros que se pueden encontrar en línea utilizan mucho este diseño ya que las desventajas de este patrón no lo afectan tanto.

## Lista de incrustaciones

Esta es una lista normal como la que aparecería en la Exploración en una sola ventana, sin embargo en el momento que el usuario selecciona uno de los elementos, este se despliega en la misma ventana, sin pasar a otra y sin la necesidad de un panel adicional.

Al mantener el resto de los elementos en la misma vista, ayuda a crear un mapeo visual para el usuario y entender mejor como se relacionan, también es un patrón que permite abrir más de un elemento a la vez y así poder comparar sus detalles, lo cual no se puede hacer con el Selector de dos paneles ni Exploración en una sola ventana.

## Rejilla de Miniaturas

La rejilla de miniaturas (*Thumnail Grid o simplemente Thumbnail*) consiste en presentar varias vistas previas de elementos de manera que se obtenga una percepción más detallada de cada elemento. Este patrón resulta particularmente útil cuando se trata de mostrar información en conjunto de imágenes o vistas previas de los elementos. Actualmente es ampliamente utilizado en sistemas web de salas de cine, tiendas electrónicas, sitios de visualización de películas y series entre otros muchos, además de ser usado por los exploradores de archivos para dar una percepción más rápida del contenido de los documentos que se encuentran almacenados en un computador  

### Ventajas

* Crea un entorno en el cual el usuario se le permite distinguir rápidamente el contenido de un archivo o producto por su imagen de vista previa  
* Con el tamaño adecuado de imágenes y la correcta programación, un sitio que manipule este tipo de patrón genera una muy buena y amigable vista para dispositivos móviles.  
* Los sitios web y sistemas adquieren un tono más llamativo para el usuario, en comparación a si se presentara una lista de texto.
  
### Desventajas

* La carga de imágenes genera un mayor consumo de datos a la hora de cargar un sitio web  
* Si no se seleccionan las imágenes de un tamaño apropiado y uniforme puede generar visualizaciones asimétricas y disparejas, lo cual es mal visto  
* Tener vistas previas de documentos de texto u otros tipos de archivos no siempre es útil o relevante lo cual puede generar una experiencia negativa a la hora de navegar en la interfaz.  
* El implementar muchos elementos en la rejilla genera una sobrecarga visual y ocasiona que se extienda mucho perdiendo su practicidad  

(Tidwell, 2011) (Welie, 2015) (Hassan, 2012)

![](_figures/ejemplo_rejilla_miniaturas.png)

## Carrusel

Este patrón pretende mostrar una moderada o pequeña cantidad de elementos mediante una interfaz circular que se extiende primordialmente de manera horizontal, desde la cual el usuario puede visualizar varias imágenes o contenido los cuales pueden rotar en intervalos o moverse según gusto del usuario. Este patrón es usado muy comúnmente en tiendas virtuales y la mayor parte de sitios web por su atractivo visual. Es indispensable recalcar que cada elemento que se vaya a mostrar en un carrusel debe poseer imágenes demostrativas significativas, las cuales se puedan utilizar para mostrar al usuario la información principal del elemento. 

Finalmente, se debe contar con herramientas para desplazar los elementos del carrusel, por lo que normalmente se implementan grandes flechas en los extremos izquierdo y derecho del elemento o utilizar las flechas del teclado. En caso de las interfaces móviles suele ser más discreto y natural, permitiendo al usuario desplazar los elementos del carrusel con un desliz de su dedo.  

### Ventajas

* Este patrón es altamente amigable con entornos de dispositivos móviles, donde el espacio de trabajo es mucho más limitado que en las PCs.  
* Genera un impacto visual agradable al usuario, el cual reconoce fácilmente el contenido de los elementos.  
* Útil para visualizar pequeñas cantidades de elementos de una manera rápida y positivamente impactante.  

### Desventajas

* Se recomienda utilizar pequeñas cantidades de elementos para evitar que sea muy difícil la navegación en el carrusel, lo cual limita si lo que se desea es mostrar cantidades moderadas o grandes de elementos  
* La carga de imágenes posee una mayor gestión del ancho de banda o de uso de procesamiento en comparación al despliegue de texto. Esto limita a evitar las imágenes de altas resoluciones y calidades al a hora de incorporarlas al carrusel  

(Hassan, 2012) (Tidwell, 2011) (Welie, 2015)

![](_figures/ejemplo_carrusel.png)

## Filas en Rayas

En sitios web y aplicaciones suele mostrarse resultados mediante tablas, estas en ocasiones se vuelven visualmente pesadas ya que su contenido es extenso y difícil de interpretar a la vez. Esto aunado que actualmente se tiene a mostrar múltiples tipos de información en los resultados desplegados en tablas (imágenes, texto u objetos entre otros), genera aún más sobrecarga visual. El patrón Fila en Rayas utiliza combinaciones de colores para diferenciar las filas contenidas en una tabla, lo que facilita al usuario identificar los contenidos de una fila como pertenecientes a ese registro. 

Este patrón se utiliza en la mayoría de páginas web y sistemas de información. Normalmente la selección de colores es de dos, además de ser colores suaves y claros como el gris claro y el blanco, esto para evitar generar estrés visual en el usuario y además de no competir con los colores de fuentes e imágenes. La implementación de estas combinaciones de colores pueden en ocasiones remplazar los márgenes y encabezados de las columnas, lo que genera una vista más limpia de la información. Es importante destacar que dichos colores se intercalan entre filas para generar el efecto deseado  

### Ventajas

* Facilita la identificación de los resultados contenidos en una tabla  
* Reduce la implementación de bordes y encabezados de columnas lo que genera una interfaz minimalista  

### Desventajas

* Las filas muy estrechas verticalmente pueden generar un efecto visual negativo, ya que generan una sobrecarga visual.
* El patrón puede llegar a ser innecesario en casos en los que hayan muy pocos elementos que mostrar en el sistema (3 o 4) o los elementos posean pocas columnas (2 o 3) con escasa información.
* Si se utilizan combinaciones de colores muy llamativos puede generar un efecto negativo de respuesta por parte del usuario.

(Tidwell, 2011) (Welie, 2015)

![](_figures/ejemplo_filas_en_rayas.png)

## Listas en Cascada

Al implementar el patrón de Listas en Cascada se puede visualizar y seleccionar información jerarquizada de una manera que se puede visualizar toda la jerarquía de dicha selección. El patrón implementa una secuencia de listas, alineadas preferiblemente de izquierda a derecha, donde la lista que se encuentra más a la izquierda representa el elemento padre de la información, seguidamente se acomodan los descendientes hacia la derecha respectivamente según su nivel en la jerarquía. Al seleccionar un elemento de la lista padre aparecerán los elementos hijos en la lista inmediata a su derecha y así sucede progresivamente con las demás hasta llegar al último nivel.

Este tipo de patrón es particularmente útil en sistemas de instalación de programas y software que posea niveles de personalización avanzados, como editores de texto y exploradores de archivos. Las listas anidadas pueden combinarse con patrones de rejillas de miniaturas para generar una vista de explorador de archivos. En caso de ambientes móviles que poseen un limitado espacio, se puede implementar este patrón desplazando las listas una vez que se haya seleccionado el elemento de la lista que se encuentra en pantalla; en estos casos se debe contar con opción de regresar en la jerarquía de listas para cambiar la opción seleccionada en el nivel anterior.  

### Ventajas

* Permite navegar claramente entre jerarquías de información dejando en claro siempre cual ha sido el camino tomado y permitiendo ver las opciones de cada nivel de la jerarquía de listas seleccionado.  
* Útil en muchos programas con alto nivel de personalización y grandes cantidades de opciones como software de ofimática y manipulación de imágenes.  

### Desventajas

* Este patrón en poco práctico cuando se cuentan con niveles de jerarquía relativamente pequeños.  
* El implementar este patrón en sistemas de jerarquías muy amplias puede generar vistas muy amplias lo que puede generar confusión o sobrecarga visual.  

(Neil, 2012) (Tidwell, 2011)

![](_figures/ejemplo_listas_cascada.png)

## Árbol en Tabla

El patrón posee las ventajas de presentación de información que posee la herramienta de tabla y la disponibilidad de acceso a la información contenida en el disco que presenta el árbol de archivos. Esta técnica presenta la posibilidad de visualizar el contenido de las carpetas seleccionadas del árbol de carpetas, esto a modo de tabla.   
Se implementa este tipo de patrones en muchos sitios web de correo, exploradores de archivos, aplicaciones de base de datos. Es importante destacar que la mayoría de programas informáticos que se encargan de modificar o editar archivos como por ejemplo archivos de texto, imágenes y música entre otros, poseen una funcionalidad para abrir archivos del formato que trabajan, estas aplicaciones en muchas ocasiones implementa este patrón con muy buenos resultados.  

### Ventajas

* Combina la versatilidad del árbol de archivos con la facilidad de despliegue de información de las tablas  
* Permite mostrar gran cantidad de elementos aun en entornos de espacios reducidos.  
* El componente de árbol de carpetas facilita la navegación entre contenidos de un sitio o archivos de un computador de una manera rápida.  

### Desventajas 

* Presenta un nivel de complejidad al usuario mayor que los otros patrones, lo que puede requerir más tiempo para familiarizarse con el sistema.  
* Es poco funcional en sistemas y páginas que posean un contenido indexado de manera jerárquica.  

(Oracle, 2015)  (Tidwell, 2011)

![](_figures/ejemplo_arbol_tabla.png)

## Fila de Nuevo Ítem

La principal función de este patrón es brindar al usuario una manera rápida y fácil de crear nuevos elementos de un tipo en particular, pudiendo agregar nuevos atributos al mismo con la mínima cantidad de pasos. Fila de nuevo ítem (*New-Item row*) se aplica cuando los elementos son mostrados en tablas, listas o arboles de jerarquía, en este punto debe bastar con una acción sencilla para que el usuario pueda agregar un nuevo elemento a cualquier estructura de datos, dicha agregación deberá venir acompañada de un corto proceso en el cual el usuario le da atributos personalizados a dicho elemento. Se puede apreciar la aplicación de este método en la mayoría de software de ofimática como Microsoft Excel, Power Point, Word, donde con un simple clic o presionar una tecla crea una nueva diapositiva o celda en la tabla; además este patrón está incorporado en las funciones de guardar y abrir en Microsoft Windows, donde el usuario al guardar o abrir un documento puede crear nuevas carpetas y nombrarlas; la carpeta y el archivo a guardar en este caso son los nuevos elementos y el nombre de ambos sería el atributo a personalizar. 
 
### Ventajas

* Agiliza el proceso de trabajo del usuario, permitiendo crear sin mucho esfuerzo nuevos elementos en su estructura de datos.  
* Es intuitivo y requiere un mínimo aprendizaje para su utilización.  
* Evita saltar a otras ventanas para observar el resultado del objeto creado  

### Desventajas

* El patrón se presta para la creación de elementos de manera errónea ya que los métodos abreviados de creación de elementos pueden utilizarse por error durante el trabajo regular con la interfaz.  
* El carácter minimalista del patrón reduce la cantidad de información que indica el tipo de contenido debe agregarse en cada campo del nuevo elemento, lo que puede generar errores de tipo.  

![](_figures/ejemplo_fila_nuevo_item.png)

## Bibliografía

* Hassan, Y. (09 de 11 de 2012). http://www.human-computer.net/. Obtenido de http://www.human-computer.net/blog/2012/11/patrones-de-diseno-de-interaccion/
  
* Neil, T. (2012). Mobile Design Pattern Gallery: UI Patterns for Mobile Applications. Canada: O'Reilly Media, Inc.
   
* Oracle. (12 de 04 de 2015). Tree Table Hierarchies Pattern Set. Obtenido de http://www.oracle.com/webfolder/ux/applications/fusiongps/patterns/content/hierarchies/treetable/index.htm
 
* Tidwell, J. (2011). Designing Interfaces. Canada: O'Reily Media, Inc.

* Welie, M. v. (12 de 04 de 2015). http://www.welie.com/. Obtenido de http://www.welie.com/patterns/index.php