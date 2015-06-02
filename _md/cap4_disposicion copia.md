# Disposición de página

**Recopilado por**:  Cruz Martínez Montalván, Jonathan Madrigal Mora y Pedro Arguedas Montero

La distribución de página (page layout) es el arte de manipular, la atención del usuario en una página para transmitir significado, secuencia, y puntos de atención.

## Marco visual

Un marco visual ("visual framework") es un patrón de diseño de interfaces que se utiliza para diseñar cada página utilizando el mismo diseño básico, colores y elementos estéticos.

### Características

Se utiliza cuando se está construyendo un sitio web con muchas páginas o una interfaz de usuario que requiere ser implementada con múltiples ventanas. Es una forma de mantener una estándar en el diseño de la interfaz de usuario que se desea implementar. Un marco visual debe estar presente en todas las páginas y ventanas en una interfaz.

Aún cuando cada página debería contar con un diseño similar, la página principal es diferente y puede contar con un diseño especial pero compartiendo algunos elementos del marco visual. Algunos de los elementos que pueden ser similares incluyen:

* Colores: el color de fondo y el color de texto.
* Fuentes de letra: títulos, subtítulos, texto ordinario.
* Estilo de escritura y gramática: títulos, nombres, contenido, descripciones cortas.
* Otros elementos: ayudas de ubicación: logos, migas de pan, navegación global, espaciamiento y alineamiento

### Ventajas

Permite que una interfaz sea fácil de usar y que también sea fácil de navegar. Además, un marco visual da la sensación de cohesión a todas las páginas que componen el sitio o aplicación.

También, facilita al usuario el cambio de una página a otra pues no requiere reconocer la nueva página. Un marco visual se enfoca en la jerarquía visual de toda la página, pantalla, o ventana por lo que es independiente del tipo de contenido que presente en dicha página.

Una de las facilidades que ofrece un marco visual es que ayuda en la usabilidad, la gente sabe dónde mirar para ciertos tipos de elementos. Si la navegación está siempre en el mismo lugar, entonces la gente sabe dónde encontrarlo cuando lo necesitan o pueden ignorarlo cuando no lo necesitan.

Del mismo modo, la colocación de los mismos tipos de botones (como Aceptar, Cancelar) en el mismo lugar en los cuadros de diálogo puede ayudar a las personas con mayor rapidez las opciones que desean y evitar errores.

En general, se puede ayudar a la gente a centrarse en el tipo de elemento visual que les interesa sin tener que volver a evaluar la interfaz.

### Desventajas

Un marco visual requiere una mayor planeamiento en cuanto a los colores, fuentes y logos afines a la aplicación que se desea implementar.

### Ejemplos

El primer ejemplo está basado en la interfaz de usuario presente en el aula virtual institucional de la universidad nacional el cual muestra como se mantiene un estándar en todas las paginas relacionadas al sistema de aula virtual ya que se utilizan los mismos colores, logos entre otros componentes.  

![](_figures/VisualFramework1-1.png)

![](_figures/VisualFramework1-2.png)

En este otro ejemplo de puede notar que la interfaz de usuario mantiene los componentes de una manera muy similar y que solo cambia según lo que desea hacer el usuario.

![](_figures/VisualFramework2-1.png)

![](_figures/VisualFramework2-2.png)

Para obtener más información sobre este patrón es recomendable visitar los siguientes links:

[Designing Interfaces- Visual Framework](http://designinginterfaces.com/firstedition/index.php?page=Visual_Framework) y 
[Quince- Visual Framework](http://quince.infragistics.com/#/Search$filter=V/ViewPattern$pattern=Visual+Framework&lang=en)

## Escenario Central

Este patrón se enfoca en presentar al usuario la parte más importante de la aplicación en una región grande en el centro de la aplicación.

### Características

Las herramientas y contenido secundarios se colocan alrededor en pequeños paneles. El trabajo principal de la página es mostrar una unidad simple de información coherente al usuario, permitirle editar un documento, o permitirle a él ejecutar una cierta tarea.  Otro contenido y funciones son secundarios a esta.
 
En cuanto al desarrollo web, el centro de la escena también es, con mucho, la mayor superficie de la página.  Por lo general, al menos el 50% del ancho de página es para el centro de la escena. Si una página tiene un diseño de varias columnas, el centro de la escena suele ser el centro y la columna más ancha.

El centro de la escena por lo general se colorea con el color más neutral en la combinación de colores, es decir, blanco o de un color suave. El color debe contrastar con otras áreas de navegación o secciones en las cosas relacionadas local, que van a los lados. Un centro del escenario es reconocible incluso sin ser capaz de leer la pantalla. Se deben guiar los ojos del usuario inmediatamente al inicio de la información más importante.

La posición del escenario central realmente no es importante, pero se debe tomar en cuenta algunas convenciones para posicionar otros elementos como: barras de herramientas en la parte de arriba y barras de navegación local a la derecha de la página. Los siguientes factores deben ser considerados al diseñar un escenario central:

* Tamaño: El escenario central debe ser al menos el doble de cualquier otro elemento en la pantalla, tanto en ancho como en alto.
* Color: Se debe usar un color que contraste con la información en los márgenes. En aplicaciones de escritorio y web se usa blanco contra gris.
* Encabezados: Encabezados grandes son puntos focales y pueden llevar los ojos del usuario a la cabecera del escenario central.
* Contexto:  Se debe tomar en cuenta lo que el usuario espera ver un gráfico, un texto, una página, un sistema de archivos en el escenario central por lo que dicho contenido se debe hacerse reconocible. 

### Ventajas y desventajas

Un centro del escenario permite a los usuarios centrarse en una cosa en particular, lo más importante en la página. Muchos tipos de interfaces pueden usar esta técnica, por ejemplo: tablas y hojas de cálculo, formularios, y editores gráficos.

### Ejemplos

Este ejemplo lo que hace notar es como un editor de texto posee implementado este patrón ya que el área de trabajo es la mas extensa y es donde el usuario enfoca su atención al instante.

![](_figures/CenterStage1.png)

Este ejemplo demuestra como un visor de imágenes implementa el patrón escenario central.

![](_figures/CenterStage2.jpg)

Para obtener más información sobre este patrón es recomendable visitar los siguientes links:

[Designing Interfaces - Central Stage](http://designinginterfaces.com/firstedition/index.php?page=Center_Stage) y 
[Welie - Certer Stage](http://www.welie.com/patterns/showPattern.php?patternID=center-stage)

## Rejilla de iguales

Se utiliza para mostrar una variedad de elementos en una interfaz de usuario pero dándole a cada elemento el mismo grado de importancia para ser mostrado en la interfaz. 

### Características

Se debe ordenar los elementos de contenido en una rejilla o matriz. Cada elemento debe seguir una plantilla común, y el “peso” de cada elemento visual debe ser similar. 

Se puede realizar también un enlace a la cada página relacionada si es necesaria. La página contiene muchos elementos de contenido que tiene estilos e importancia simulara, tal como artículos de noticias, entradas de blogs, o áreas de categorías.

Se deben desplegar los elementos con algo más que bloques de texto: titulares de colores diferentes, ser creativos con espacios en blanco, y el uso de imágenes, si se puede hacer de manera uniforme en todos los artículos. 

Se debe experimentar diversas formas para adaptarse a toda la información correcta en un espacio relativamente pequeño de estatura, ancho, o cuadrados y aplicar esa plantilla para los elementos que se necesitan mostrar.

Cuando un usuario se posiciona sobre los elementos de la cuadrícula se pueden utilizar colores y otros cambios de estilo, pero no se debe cambiar las posiciones, tamaños u otros elementos estructurales de la rejilla de los elementos.

Una clave para ayudar a los usuarios notan las diferencias entre los múltiplos es asegurarse de que cada uno de los elementos no difiere en formas distintas de estas dimensiones. Por ejemplo, cada imagen del producto debe ser del mismo tamaño, utilice el mismo color de fondo, etc.
 
Las diferencias notables entre los artículos deben tener algo que ver con las dimensiones que desea que se fijen.

### Ventajas y desventajas

En conjunto, estas técnicas establecen una jerarquía visual de gran alcance que debe coincidir con la semántica de su contenido. La plantilla común para los elementos dentro de la rejilla indica al usuario que los elementos son similares entre sí. Tener que recordar detalles a través de múltiples ejemplos de una en una en realidad haría probable que muchos patrones no se observaron en absoluto.

Estas diferencias se notan sobre todo en los casos en que el conjunto de ejemplos son similares en muchos aspectos, y en realidad sólo difieren ligeramente entre sí. Sólo viendo todos a la vez son estas sutiles diferencias notables.

Al mostrar muchos ejemplos a la vez, lo que demuestra las diferencias entre las dimensiones permite a los usuarios ver los patrones que serían más difíciles de notar si mira un ejemplo a la vez.

### Ejemplos

Se le presentan al usuario las opciones de los productos que puede adquirir para que seleccione el articulo deseado, se puede notar que todos los elementos poseen el mismo tamaño.

![](_figures/GridOfEquals1.png)

Este ejemplo simula una tienda de música en donde se le presenta al usuario diferentes tipos de música agrupadas por genero musical donde puede seleccionar el genero y esta le presentara la música según el genero seleccionado.

![](_figures/GridOfEquals2.png)

Para obtener más información sobre este patrón es recomendable visitar los siguientes links:
[Quince- Grid of equals](http://quince.infragistics.com/#/Search/ViewPattern$pattern=Titled+Sections&lang=en)

## Secciones con títulos

Este método se usa cuando usted tiene una gran cantidad de contenido para mostrar, pero desea hacer la página fácil de explorar y comprender, con todo lo visible. 

Puede agrupar el contenido en secciones basada en temáticas o en trabajo que tengan sentido para el usuario.

### Características

Este método permite crear secciones separadas de contenido dando a cada una un título visualmente fuerte, luego se distribuyen todas en la misma página. Las secciones con títulos hacen que sea fácil explorar y entender una página aún cuando presente una gran cantidad de contenido.

El contenido se puede agrupar en secciones basadas en temas o tareas, de forma que tenga sentido para el usuario. Utilizando visualmente secciones distintas guiará a la gente a ver la información como trozos. 

Algunos factores que pueden ser utilizados son:

* Títulos: Usar fuentes de letra que sobresalgan del resto del contenido, negrilla, ancha, grande, colores fuertes, etc.
* Contraste: El título se puede contrastar contra una barra de fondo.
* Usar espacios en blanco para separar las secciones.
* Poner las secciones en diferentes colores de fondo.
* El dibujo de cajas es muy popular en aplicaciones de escritorio. Sin embargo, se debe tener cuidado en no hacerlas muy grandes, demasiado cercanas, o muy anidadas.

### Ventajas y desventajas

Cuando un usuario ve una página dividida en secciones, él guía su mirada entre la página de forma más confortable. Este patrón no funcionará si no se puede de manera significativa agrupar la información en trozos. Los títulos ayudarán a escanear rápidamente los trozos para encontrar lo que es interesante para el usuario para luego se poder profundizar en la sección deseada.

Este patrón se aprovecha de que el sistema visual humano siempre busca patrones más grandes, ya sean deliberadas o no, así cuando el usuario ve una página seccionada en trozos, su ojo es guiado a lo largo de la página con mayor comodidad. 

### Ejemplos

El primer ejemplo muestra una ventana donde se agruparon los componentes y cada grupo posee su titulo para que sea fácil de utilizar para el usuario.

![](_figures/TitledSection1.png)

Este otro ejemplo muestra como se puede agrupar el contenido de una ventana por secciones. 

![](_figures/TitledSection2.png)

Para obtener más información sobre este patrón es recomendable visitar los siguientes links:
[Designing Interfaces- Titled Section](http://designinginterfaces.com/firstedition/index.php?page=Titled_Sections) y 
[Quince- Titled Section](http://quince.infragistics.com/#/Search/ViewPattern$pattern=Titled+Sections&lang=en)

## Distribución líquida

Este patrón surge ante la necesidad de que la gente quiere ver el contenido de un tamaño adecuado para el factor de forma que están usando. La solución que plantea el patrón es tratar el contenido como líquido y hacer que se expanda para llenar la forma de su envase.

### Características

La idea aquí es que conforme el usuario modifica el tamaño de la ventana, el contenido de la página se reordene para rellenar toda el área disponible. 

A menos que el diseño se realice para una interfaz cerrada es difícil predecir las condiciones bajo las que el usuario verá la aplicación ya que ni el tamaño de la pantalla, ni las fuentes de letra pueden ser establecidos de antemano. Al agrandar dicha ventana todo el contenido debería acomodarse de forma adecuada al nuevo espacio disponible. 

De igual forma, si se cuenta con una ventana demasiado grande se podría reducir su tamaño y el contenido debería re ordenarse en la nueva área reducida.

### Ventajas y desventajas

Este modelo ayuda a optimizar la experiencia de los diferentes factores de forma. Además, el uso de diseño líquido puede ayudar cuando la localización a otros idiomas o cambiar el tamaño de la fuente del contenido.

Un usuario puede querer asignar más espacio a un texto o aplicación que tiene una ventana muy pequeña. El dar al usuario control sobre la distribución de la página hace que la interfaz sea más flexible a condiciones cambiantes. 

Sin embargo, ciertas aplicaciones requieren un tamaño mínimo (o máximo) para ser útiles. Un re ordenamiento más allá de esos límites podría ser contraproducente.

### Ejemplos

Este ejemplo tiene como objetivo hacer notar como se adaptan los componentes de la aplicación a la hora de cambiar el tamaño de la ventana.

![](_figures/LiquidLayout1-1.jpg)

![](_figures/LiquidLayout1-2.jpg)

Este otro ejemplo es similar al anterior, ejemplifica como se adaptan los componentes de la ventana al reducir su tamaño.

![](_figures/LiquidLayout2.png)

Para obtener más información sobre este patrón es recomendable visitar los siguientes links:
[Designing Interfaces- Liquid Layout](http://designinginterfaces.com/firstedition/index.php?page=Liquid_Layout) y 
[Quince- Liquid Layout](http://quince.infragistics.com/#/Search$filter=L/ViewPattern$pattern=Liquid+Layout&lang=en)

## Módulo de tabuladores

Este patrón consiste en separar 2 o más módulos de la aplicación de tal forma que sólo sea visible uno a la vez, y el usuario puede acceder a ellos mediante el tabulador usualmente ubicado en la parte superior de la vista de los módulos. 

Este patrón es utilizado principalmente por sitios web debido a que permite al usuario navegar libremente por el contenido de la página web sin la necesidad de cambiar de página en sí, permitiendo al desarrollador tener un sitio más dinámico. No por esto los tabuladores no son utilizados en las aplicaciones de escritorio, por ejemplo existen aplicaciones de uso diario que manejan este diseño. 

Sin ir más lejos uno de los ejemplos claros son los navegadores web, tanto Firefox como Chrome utilizan tabuladores para manejar las diferentes páginas cargadas por el usuario sin necesidad de abrir más ventanas. Además este patrón permite mantener un orden no solo en la aplicación o página en sí, sino también para el usuario a quien se le facilita la navegabilidad por la aplicación o sitio web.
 
### Características

Las características de este patrón son:

*	El usuario necesita ver únicamente un módulo a la vez.
*	El tamaño necesario para los diferentes módulos es muy similar.
*	La cantidad de módulos es poca (menos de 10), si la cantidad de módulos es mayor la interfaces puede verse cargada y poco amena a la vista del usuario.
*	No se estará agregando módulos constantemente, y de igual forma no se eliminarán los ya existentes, en otras palabras el contenido es estático y no existirán variaciones mayores.
*	El contenido de los módulos podría estar relacionado o ser parecido.

### Ventajas:

*	Al ser una interfaz muy utilizada tanto en interfaces de escritorio como en web no habrá confusiones en cómo funciona.
*	Es muy efectivo para ordenar una interfaz.

### Desventajas:

*	Sólo se puede visualizar un módulo a la vez.
*	No es recomendado para aplicación que constantemente se reinventan o actualizan y agregan contenido según las necesidades.

### Ejemplos

Los ejemplos presentan una versión en dispositivos móviles lo cual presenta los tabuladores cómo botones, lo cual demuestra la variación que se le puede dar a dicho patrón. Después Podemos observar una interfaz muy normal en cuanto a la implementación del patrón.

![](_figures/ModuleTabs.png)
	
## Acordeón

Éste es otro patrón que se basa en la separación de módulos, por lo tanto es una variación del patrón anterior. Sin embargo la idea de dicho patrón es acomodar los módulos en una pila de paneles que pueden ser abiertos independientemente. Esto quiere decir que se pueden mostrar uno o más paneles al mismo tiempo, según el tamaño del dispositivo dónde se visualice; esto no implica que no pueden ser abiertos todos, pero dependiendo de sus dimensiones no todos serán visibles al mismo tiempo. 

Cada panel con su respectivo título produce la activación de su panel asociado. Al ser una variación del patrón anterior es igualmente utilizado en páginas web y aplicaciones. La activación de los paneles usualmente es mediante un clic del mouse, la cual es la mejor opción, sin embargo existen otros métodos como el arrastrar el cursor por encima. Éste último no es recomendable debido a que para el usuario puede parecer molesto debido a la constante apertura y cierre no deseado de los módulos.

### Características

Se caracteriza por: 

*	El usuario puede visualizar más de un módulo. Como se comentó repetidas veces es una variación del patrón de tabuladores, y su principal diferencia y punto fuerte es que puede mantener más de un módulo abierto en caso de que el usuario lo necesite.
*	Los módulos pueden diferir en cuanto a su altura más no su ancho. Otro punto importante de diferenciación que la altura de los módulos no debe ser necesariamente igual como en el patrón anterior.
*	Es importante usarlo cuando el nivel de cosas que se desea mostrar es 2 como máximo, si fuera mayor a ese número la interfaz se vería recargada y pesada a la vista del usuario.
*	Ayuda a mantener un orden lineal de los módulos.
*	Los módulos son parte de una paleta de herramientas, menú de 2 niveles u otros sistemas de elementos interactivos.
*	El contenido de los módulos puede estar relacionado. La relación puede ser en sus funciones, por ejemplo pueden ser formularios cuya principal diferencia es la información solicitada al usuario.

### Ventajas:

*	Son casi tan conocidos como los módulos tabulados, por lo que tampoco habrá confusión en cuanto a su uso.
*	Ayuda a mantener una interfaces ordenada y limpia.

### Desventajas:

*	Pueden llevar a la confusión del usuario si se usan de manera anidada. Al poseer varios módulos dentro de otros al  momento de ser abiertos van a ocupar mucho más espacio del que debería en la interfaz, con lo cual la vista de la aplicación se verá recargada con contenido secundario.

### Ejemplos

El primer ejemplo demuestra uno de los principales usos que se le dan a dicho patrón, el cual es para separa y visualizar archivos. En éste caso imágenes. El segundo ejemplo presenta como podemos podemos separa diferentes tipos de contenido y aún así mantenerlo todo visible al usuario. 

![](_figures/Accordion.png)

## Paneles plegables:

Éste patrón es usado con elementos secundarios u opcionales de la interfaz, poniéndolos en paneles que pueden ser abiertos y cerrados por el usuario. La idea es que los componentes que se sitúan en esta clase de paneles sean de ayuda o complementen el panel principal, sin embargo su importancia no es la suficiente para permanecer en el panel principal. Es importante no sobrecargar estos paneles, con esto me refiero a que se pueden anidar unos con otros sin embargo llega un punto donde son incómodos y molestos para el usuario.

### Ventajas:

*	Simplifica la interfaz al ocultar contenido secundario. Ayuda a mantener la interfaz limpia, aun así posee los componentes necesarios para que el usuario realice las tareas que requiera.
*	Es muy útil para aplicaciones con que poseen muchas funciones como por ejemplo el software para realizar Photoshop.

### Desventajas:

*	Su ubicación debe ser bien definida para no estorbar con el contenido principal de la interfaces, haciendo que su implementación no tenga sentido.
*	Los componentes presentes en estos módulos deben ser bien definidos ya que si un componente principal termina en un módulo secundario será un problema para el usuario final de la aplicación o pagina web.

### Ejemplos:

El mayor ejemplo de los paneles plegables es sin duda alguna el sistema operativo Windows, el cuál le da uso para manejar los sitios a los que accede el usuario en su directorio de carpetas y archivos.

El siguiente ejemplo son los navegadores, que en su mayoría por no decir todos, utilizan los paneles plegables para mostrar diferente contenido. en este caso específico son los marcadores de los sitios web visitados.

![](_figures/CollapsiblePanels.png)

## Paneles Móviles

Consiste en poner contenido dentro de cajas separadas e independientes una de la otra, con lo cual el usuario puede abrirlas o cerrarlas según sus necesidades además de poder moverlas y colocarlas en la configuración que desee. Se utilizan principalmente cuando el usuario muy probablemente necesitará ver más de un módulo.

### Características

En este diseño el tamaño de los módulos puede variar. Además, posicionamiento de la página es más importante para el usuario que para el desarrollador. La estructura por defecto de la página web o aplicación no es de mucha importancia para el desarrollador debido a que tan pronto como el usuario empiece a utilizar el software también empezará a personalizarlo a su gusto con lo que la configuración por defecto cae en un segundo o tercer plano de importancia.

La cantidad de módulos que se pueden mostrar es muy amplia por lo cual se deben elegir unos únicamente, ya sea por el desarrollador (módulos a mostrar por defectos) o por el usuario (personalización). Debido a que en toda aplicación hay un espacio limitado, sea grande o pequeño se debe definir de manera correcta las módulos más importantes para mostrar. Esto quiere decir que a pesar de los módulos que sean visualizados en la interfaz, existen más módulos que pueden ser cambiados por los que se muestran.

Se le da la posibilidad al usuario de ocultar algunos módulos, sin embargo puede volver a mostrarlos. Esto quiere decir que aunque un usuario por alguna razón decida que un módulo no es de su importancia y lo elimine, puede volver a recuperarlo y agregarlo a la interfaz de manera fácil y rápida para él.

### Ventajas

La implementación  de éste patrón es muy usada en móviles, más específicamente en el manejo de widgets en las pantallas de los dispositivos. Se pueden mover los widgets en el lugar que el usuario necesita y dependiendo del espacio puede tener más de uno. Además es el usuario quién escoge cuáles widgets se muestran.

### Ejemplo

El otro ejemplo es de una aplicación web llamada trello la cuál ayuda a la administración de tareas en un proyecto. Su interfaz permite mover notas y tareas por realizar en el lugar que más le convenga al usuario que lo utiliza siento cada tarea o ventana independiente de las otras.

![](_figures/MovablePanels.png)

## Alineamiento derecha/izquierda

Este patrón se utiliza cuando se desea crear o diseñar un formulario de dos columnas, en el cual los elementos de la izquierda representan las etiquetas o información solicitada, mientras que a la derecha se ubican los elementos que permiten al usuario ingresar o seleccionar la información solicitada, pueden ser campos de texto, botones, entre otros.

Se puede utilizar en formularios que tiene un conjunto de elementos que llevan etiquetas en frente de ellos, también se puede aplicar en la estructura interna de una tabla o bien en toda estructura que se componga de dos columnas. Este patrón surge debido a que a las personas no les gusta los formularios debido a su complejidad.

Además explica que para los usuarios es importante llenar un formulario de principio a fin y con un orden especifico y de esta manera no tener que buscar campos deseados  por todo el formulario.

### Características

Las etiquetas pueden tener varios tamaños, algunas pueden ser pequeñas y otras grandes, sin embargo lo más importante es no dejar demasiado espacio entre una etiqueta y su campo asociado ya que puede causar confusión en los usuarios. Si la etiquetas resultan ser muy largas es recomendable dividirla en varias líneas.

El principal motivo por lo que se puede utilizar este patrón es porque cuando se coloca la etiqueta al lado del componente que la asocia, se crea un fuerte agrupación perceptible permitiendo al usuario asociar con facilidad los elementos de la interfaz.

Mientras que para el patrón de alineamiento a la izquierda es usado cuando la información necesitada no es familiar, presenta menor claridad en la asociación entre la etiqueta y el campo. El cambio de tamaño de las etiquetas deteriora el diseño de la interfaz.

La forma en cómo se implementa este patrón,  es tan simple como alinear a la derecha de cada etiqueta textual el campo que describe y con una distancia mínima entre ambos. No hay problema que las etiquetas sean irregulares en su tamaño o bien los campos respectivos de cada etiqueta. Es importante que el espacio entre cada etiqueta y su campo asociado sea el mismo para todos, de esta manera se creara un efecto simétrico hacia abajo siendo más agradable a la vista y más fácil de comprender en su totalidad el formulario.

### Ventajas y desventajas

Como desventaja del patrón de alineamiento a la derecha se especifica que la legibilidad se ve reducida,  mientras que la desventaja del alineamiento a la izquierda se describe que el espacio entre la etiqueta y el campo no es el mismo para todos, lo cual dificulta la asociación etiqueta-campo. 

Mientras que las ventajas del alineamiento a la derecha son que reduce el espacio vertical y que cada etiqueta se encuentra adyacente a su campo de texto asociado permitiendo crear una línea imaginaria vertical entre etiquetas y campos y para el alineamiento a la izquierda están que el espacio vertical es reducido y que es fácil encontrar las etiquetas.

### Ejemplos

En el siguiente ejemplo se puede observar como las etiqueta se encuentra lo más cerca posible de su elemento asignado y se crea una línea imaginario vertical en medio de ambos, además permite ubicar fácilmente una etiqueta en la interfaz.

![](_figures/RightLeftAlignment1.jpg)

En este ejemplo de alineamiento a la izquierda se puede ver como ya no se crea la línea imaginaria vertical y hay más espacio entre la etiqueta y su elemento asociado, puede resultar más difícil de asociar ambos componentes, sin embargo se puede buscar una etiqueta específica con facilidad.

![](_figures/RightLeftAlignment2.jpg)

## Balance diagonal

Este patrón se puede utilizar cuando el diseño de la interfaz es suficientemente corto y no se tiene la necesidad de desplazarse.

Proporciona un equilibrio diagonal que permite al usuario desplazarse fácilmente de una esquina a la otra, además de dar la impresión de un balance de peso en la página, y ser más agradable a la vista del usuario.

Este patrón consiste en organizar los elementos de la página en forma asimétrica pero a su vez poniendo peso visual en zonas especificas para evitar que la interfaz se vea sobrecarga de elementos en una zona más que en otra.

Este patrón se usa ya que los usuarios leen de izquierda a derecha y tienen un movimiento natural de los ojos de la parte superior izquierda hacia la parte inferior derecha, la solución consisten en organizar los elementos de manera asimétrica, equilibrar la interfaz poniendo peso visual tanto en la parte superior izquierda como en la parte inferior derecha.

Es un patrón diseñado a partir del diagrama de Gutenberg que explica que el movimiento natural del ojo de una persona es de manera diagonal, comenzando en la parte superior izquierda POA  (Primary Optical Area por sus siglas en inglés)  y terminando en la parte inferior derecha TA (Terminal Anchor por sus siglas en inglés) .

A continuación se puede ver una imagen donde se especifica o explica el modelo de Gutenberg

![](_figures/DiagonalBalance1.png)

Este autor menciona que las interfaces con el patrón de balance diagonal son generalmente ejemplo de buenos diseños. También menciona que no todos los diseños se pueden resolver utilizando este patrón, que no se recomienda forzar su uso

### Características

La estructura de este patrón consisten en colocar el titulo o algún otro elemento fuerte en la parte superior izquierda de la página, los botones en la parte inferior derecha de la misma y cualquier elemento de cualquier anchura en medio dejando en  la mayoría de lo posible el mismo espacio en blanco a ambos lados de la página.

### Ventajas y desventajas

Entre las ventajas que ofrece este patrón están ser más agradable a la vista, y establecer la página para que los ojos del usuario se muevan con facilidad desde la parte superior izquierda a la parte inferior derecha. Mientras que como desventaja está que un mal uso de este patrón puede no ofrecer al usuario una interfaz agradable, por el contrario se torna tosca y pesada, también se ve limitado a usar los elementos correctos para provocar el balance y utilizar un tamaño correcto para la página.

### Ejemplos

En la siguiente imagen se puede ver como las pestañas junto con los botones de la parte inferior de la ventana principal equilibran la cantidad de información que los gráficos pueden mostrar dando una vista agradable y no pesada a la vista de la ventana principal.

![](_figures/DiagonalBalance2.jpg)

En este ejemplo se puede ver que es un titulo de tamaño considerable junto con los botones los que crean ese balance entre los componentes de la interfaz, lo cual demuestra que hay diversas maneras de crear este efecto visible y las opciones para hacerlos quedan a decisión del desarrollador.

![](_figures/DiagonalBalance3.jpg)

## Descubrimiento sensitivo

Este patrón consiste en mostrar al usuario elementos de la interfaz conforme selecciona otros, comenzando con una interfaz simple, sencilla, limpia, fácil de entender y seguidamente mostrar más elementos al usuario, generando poco a poco una interfaz más compleja.

Se puede utilizar cuando el usuario va a realizar una tarea que muy pocas veces se hace o bien que es muy complicada o compleja y que no se desea guiar al usuario por diferentes páginas o ventanas, sino más bien se pretende que el usuario realice toda la tarea en una misma página.

Sin embargo hay que tener mucho cuidado a la hora de utilizar este patrón ya que si el espacio donde se realizara es muy pequeño o bien si se utilizan demasiados elementos, podría provocar confusión en el usuario y su vez hacer que este no utilice el sistema para efectuar la tarea o que lo haga sintiéndose incomodo.

El patrón de descubrimiento sensitivo es usado ya que no todos los usuarios necesitan todas las opciones habilitadas todo el tiempo. 

Algunas pruebas prácticas que establece este autor son:

* Priorizar aquellos componentes que el usuario necesite más comúnmente para su habilitación.
* Este patrón es más eficiente cuando el usuario inicia la habilitación de componentes, ósea cuando realiza alguna acción.
* Mantener un enfoque consistente entre los componentes.

Este patrón es usado cuando los usuarios se encuentran con una serie de pasos que deben realizar para completar una tarea, cada uno de estos pasos será habilitado al usuario solo cuando sea necesario.

Se recomienda utilizar este patrón para hacer que un proceso pesado se sienta más ligero para el usuario. Este patrón surge debido a que la información que no es necesario hasta cierto momento en especifico puede distraer a los usuarios.

Además describen que los usuarios pueden sentirse engañados si sienten que la tarea está tomando más tiempo de lo que pensaba y con más y más pasos sin terminar. Para evitar que los usuarios se sientan así es posible considerar el uso del patrón de Habilitación sensitiva.

## Características

La tarea se desarrolla frente al usuario de manera dinámica, eso quiere decir que en principio se muestran solo los elementos básicos para comenzar la tarea y progresivamente se muestran los nuevos elementos junto con los anteriores. Esto permite al usuario poder regresar fácilmente a pasos anteriores y cambiar de opinión, se debe mantener todo en una sola página.

###  Ventajas y desventajas

Como desventaja se pude ver que el usuario debe completar toda la información que se le solicita en un paso para poder continuar, mientras que como ventaja se puede ver que permite al usuario cambiar de opinión en algún dato en cualquier momento y que evita que el usuario ingrese datos innecesarios para completar tareas especificas.

### Ejemplos

En el primer ejemplo se puede ver como en la pantalla inicial solo se muestran las opciones básicas para comenzar a realizar una tarea.

![](_figures/ResponsiveDisclosure1-1.jpg)

Seguidamente se muestran otros elementos en la misma pantalla que permiten al usuario completar su tarea, estos elementos se muestran según la opción que el usuario elija en el paso uno.

![](_figures/ResponsiveDisclosure1-2.jpg)

En la siguiente imagen podemos ver como al seleccionar otra opción, solo se muestran los elementos necesarios para realizar la tarea que el usuario desea hacer.

![](_figures/ResponsiveDisclosure1-3.jpg)

En el segundo ejemplo se muestra la interfaz de una red social, la cual permite al usuario iniciar sesión o crear una cuenta nueva, sin embargo estos otros pasos no se muestran al usuario desde un comienzo.

![](_figures/ResponsiveDisclosure2-1.jpg)

Por el contrario se muestran una vez que el usuario a elegido alguna opción inicial, como es el caso de crear una nueva cuenta mostrándose el formulario de ingreso de datos como se muestra en la siguiente imagen.

![](_figures/ResponsiveDisclosure2-2.jpg)

## Habilitación sensitiva

Este patrón consiste en mostrar toda la información y elementos de interfaz de usuario al mismo tiempo, pero inicialmente solo habilitar aquellos elementos que son necesarios para el paso inicial. Luego permite que el usuario interactúe con otros elementos a medida que los necesite.

Si toda la información que el usuario necesita para realizar la tarea se muestra habilitada desde un principio puede resultar abrumador para el usuario. Un gran número de elementos disponibles para que el usuario utilice puede resultar desalentadores. En este patrón, la interfaz de usuario le dice a éste las consecuencias de realizar alguna acción, habilitando elementos específicos.

### Características

Este patrón consiste en una interfaz que presenta la mayoría de elementos deshabilitados desde un comienzo y que se habilitaran permitiendo al usuario realizar más acciones conforme este realice alguna otra acción, al igual que el patrón anterior, toda la información se mantiene en una misma página y se va completando paso a  paso, mostrando todo lo realizado por el usuario para que este tenga facilidad si desea cambiar de opinión.

### Ventajas y desventajas

Como desventaja se puede mencionar que todos los componentes se muestran en la pantalla aún estando deshabilitados, lo cual puede convertirse en un problema ya que si hacemos uso de este patrón en una interfaz que no lo amerite podríamos saturar la interfaz de elementos, mientras que como ventaja tenemos que permite que el usuario no realice acciones que metan en  problemas al sistema al mantener los elementos que no se estén usando bloqueados, también que la interfaz mantiene bloqueadas las opciones que no son necesarias haciendo más fácil la interacción del usuario.

### Ejemplos

En la siguiente imagen vemos como se habilitan solamente las opciones básicas para comenzar la tarea, sin embargo se muestran todos los demás elementos que el usuario podría utilizar.

![](_figures/ResponsiveEnabling1-1.jpg)

Ahora se puede ver que se habilitan solamente elementos según la opción que elija el usuario, en este caso se permite solamente el registro de un nuevo usuario.

![](_figures/ResponsiveEnabling1-2.jpg)

Mientras que en esta otra imagen se habilita solamente la opción de modificar un usuario bloqueando la anteriormente seleccionada.

![](_figures/ResponsiveEnabling1-3.jpg)

En el segundo ejemplo tenemos la interfaz de un sistema para aplicar a carreras de una universidad, en principio solo se muestran habilitadas en una tabla las opciones de carrera que se ofrecen en las diferentes universidades y deshabilitado el formulario de aplicación a la carrera.

![](_figures/ResponsiveEnabling2-1.jpg)

Sin embargo al seleccionar una de las opciones se habilita el formulario permitiendo aplicar a la carrera seleccionada en la tabla.

![](_figures/ResponsiveEnabling2-2.jpg)

## Referencias
 
* Best Practices for Form Design por Luke Wroblewski, http://static.lukew.com/webforms_lukew.pdf
* Designing Interfaces por Jenifer Tidwell, http://designinginterfaces.com
* Designing Web Interfaces por Bill Scott y Theresa Neil, http://designingwebinterfaces.com/
* Quince, http://quince.infragistics.com)
* Welie, http://www.welie.com)