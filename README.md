# 1.Introduccion_Python
En esta bitacora vamos a ver una leve sintesis de como empezar a trabajar con las funciones de Python desde nivel inicial.

Contenido:

1.Variables, Tipos de Datos y Operaciones,

2.Listas y Loops.


# Una nueva forma de interactuar con datos:

Python es, según su creador Guido Van Rossum, "el lenguaje de programación de alto nivel, y su filosofía de diseño central se basa en la legibilidad del código y una sintaxis que permite a los programadores expresar conceptos en unas pocas líneas de código". Esta facilidad de expresión es la que hace a Python un lenguaje de programación versátil y tan útil en Data Science.

Empezamos a conocer Python, el lenguaje de programación que más se destaca en el mundo de datos, no es la única opción, pero sí es la más popular.

Como todo lenguaje de programación, Python cuenta con diferentes elementos:

Tipos de datos básicos: Números - enteros y floats -, texto -strings-, variables de verdad -bool-, etc. Es importante prestarle atención al tipo de dato con el que estás trabajando, porque eso definirá qué cosas se pueden hacer. Por ejemplo, puedes sumar dos números como lo hacemos habitualmente, pero ¿qué sucederá si sumas dos strings?
https://s3.amazonaws.com/sc.acamica.com/content/toolbox/ds/ds_02_a.png

Estructuras de datos: a veces, trabajar con variables que representan un solo dato no será suficiente, sino que necesitarás trabajar con conjuntos de datos. En ese caso, deberás pasar a las estructuras de datos más complejas, que te permitan generar variables de más de un elemento. Además, muchas estructuras de datos vienen con funcionalidades propias, lo cual suele ser muy útil. Por ejemplo, las listas. Una aclaración: la distinción entre estructura de datos y tipo de datos básicos es un poco arbitraria, pero preferirás hacerlo así para diferenciar qué elementos individuales puedes crear (tipos de datos básicos) y cómo los agrupas luego (estructuras de datos).
Variables:* puedes pensar las variables como un contenedor de información que te interesa guardar para utilizar más tarde. Otra forma de pensarlo es la siguiente: al crear una variable le estás poniendo un nombre a un objeto. Prácticamente cualquier cosa puede ser asignada a una variable. Cuando creas variables, es importante ponerle un nombre informativo, es decir, que represente la información que esa variable contiene. ¡Y si es en inglés, mejor! En Python se usa el símbolo "=" para asignar una variable, lo cual puede traer confusión con el "=" que usamos en matemática. No te preocupes, ya te vas a acostumbrar.

Funciones propias: la mayoría de los lenguajes de programación ya vienen con algunas funciones implementadas. Los ejemplos más sencillos son print(),type(), etc. Verás que la mayoría de los entornos de desarrollo les asigna un color específico. En el caso de Jupyter, ese color es verde claro.

Keywords y Herramientas de controles de flujo: todos los lenguajes de programación tienen un conjunto de palabras predefinidas que cumplen una tarea específica. Algunas de esas palabras predefinidas te ayudarán a crear un flujo en tu programa, ayudándote a tomar decisiones (if/else) o a repetir operaciones (for/while). En Jupyter, estas palabras tienen un color verde oscuro.
A veces en lugar de keyword se usa el término palabra reservada, aunque técnicamente no son lo mismo. Una palabra reservada refiere a una palabra que NO puedes usar como nombre de un variable, ya que esta palabra es tan importante en tu lenguaje de programación que no sería conveniente asignarle una nueva función. ¡Tiene sentido que los keywords sean palabras reservadas! Este cuadro contiene todas las keywords:

https://s3.amazonaws.com/sc.acamica.com/content/toolbox/ds/ds_02_a2.png
