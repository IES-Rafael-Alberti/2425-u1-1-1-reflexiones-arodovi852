## PDF con la resolución de los apartados 1 y 2 de P1.10

**P 1.10: Reflexión y discusión sobre los resultados**
**1. Relación software y hardware**
**1.1. Primera parte**
**1.1.1. ¿Cómo se ejecuta el código en el procesador?**
    Cuando se ejecuta un programa en el ordenador, este se carga en la memoria RAM y la CPU va recuperando una a una las instrucciones y las va ejecutando, dividiéndolas en pequeños pasos que el procesador sigue.

 **1.1.2. ¿Qué hace la memoria RAM con la información del botón o el LED?**
    La guarda esa información temporalmente, y desaparece cuando se apague el equipo.

**1.1.3. ¿Cómo se comunican los periféricos (botón y LED) con el procesador?**
    Los periféricos recogen datos desde su entrada y estas son recibidas por la CPU como información para utilizar dentro de sus instrucciones.
**1.2. Segunda parte**
**1.2.1. ¿Cómo interactúan el procesador, la memoria y los periféricos en la ejecución del programa?**
    El procesador recibe instrucciones que ya entiende en lenguaje máquina, la memoria se encarga de almacenar temporalmente la información temporalmente y los periféricos ayudan a que el usuario pueda comunicarse con el usuario

 **1.2.2. ¿Qué pasa con los datos en la memoria cuando el programa se ejecuta?**
    Se almacenan temporalmente en la memoria RAM y se eliminan cuando el dispositivo se apague.

 **1.2.3. ¿Qué roles juegan las instrucciones del software en esta interacción?**
    Envían las instrucciones a la CPU para que estas sean realizadas

 **1.2.4. ¿Cómo se relaciona esta simulación con lo que ocurre en un ordenador real?**
El software envía instrucciones a la CPU, el procesador ejecuta estas instrucciones y finalmente el sistema operativo libera memoria y recursos que el programa estaba usando.

**2. Del código fuente al ejecutable**
**2.1. ¿Cómo se diferencia el código fuente del código objeto y del ejecutable?**
    El código fuente es el conjunto de instrucciones que el programador escribe usando un lenguaje de programación que los humanos pueden entender, mientras que el código objeto es una versión intermedia del código fuente 	que aún no es completamente ejecutable y el código ejecutable es aquel que puede entender la máquina.

 **2.2. ¿Por qué el ordenador no puede entender el código fuente directamente?**
    Porque solo entienden el lenguaje máquina (basado en ceros y unos)

 **2.3. ¿Por qué es importante el paso de enlazado en la creación de programas?**
    Porque va traduciendo parte por parte y el código objeto contiene las instrucciones traducidas de una sola parte para enlazarlas en la siguiente parte.

 **2.4. ¿Qué ocurre si falta alguna de las etapas (código objeto o ejecutable)?**
    El código no podría llegar a ejecutarse puesto que la máquina no lo podría reconocer.

**3. Generación de código intermedio**
**3.1. ¿Cómo difiere el código intermedio del código ejecutable tradicional?**
    Este está diseñado para ser ejecutado en una máquina virtual.

 **3.2. ¿Por qué es útil tener una máquina virtual?**
    Para poder interpretar el código intermedio y para poder traducir el bytecode al lenguaje de máquina específico de un procesador Intel/AMD

 **3.3. ¿Qué ventajas ofrece el código intermedio?**
    Es portable gracias a que el mismo programa puede correr en diferentes sistemas operativos sin necesidad de recompilar el código, las máquinas virtuales proporcionan seguridad y optimiza su tiempo de ejecución

 **3.4. ¿Además de java, qué otros lenguajes usan máquinas virtuales?**
    C# genera CIL, Kotlin usa el mismo tipo que Java…

**4. Lenguajes de programación**
**4.1. Primera parte**
**Compara el proceso de ejecución entre el lenguaje compilado y el interpretado.**
 **4.1.1. ¿Qué diferencias notaron en el proceso de compilación frente a la ejecución directa?**
    El proceso de compilación es más rápida que la ejecución directa pero necesita ser recompilado para cada plataforma, mientras que la ejecución directa es más lenta pero no necesita compilar por lo que es mucho  más sencillo.

 **4.1.2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?**
    Si hay un error en el lenguaje compilado, el programa se frenará y se detectará durante la fase de análisis sintáctico, mientras que en el interpretado el error de sintaxis se dará al final.

**4.2. Segunda parte**
    Compara un lenguaje de alto nivel con uno de bajo nivel.
 **4.2.1. ¿Qué notaron sobre la abstracción entre los lenguajes de alto nivel y bajo nivel?**
    Los lenguajes de alto nivel son muchos más abstractos frente a los de bajo nivel.

 **4.2.2. ¿Qué ventajas y desventajas encontraron en cada uno?**
    Los de bajo nivel se acercan más al hardware pero son menos abstractos y difícil de entender para un humano mientras que los de alto nivel son más fáciles de entender por los humanos y abstractos pero no tienen tanto control sobre el hardware como los de bajo nivel

**4.3. Tercera parte**
**Compara un lenguaje orientado a objetos vs funcional.**
 **4.3.1. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?**
    En Java se pueden crear clases y objetos que almacenan datos.

 **4.3.2. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?**
    En vez de dar instrucciones sobre cómo cambiar el estado del programa, las funciones toman entradas y producen salidas sin cambiar el estado del programa

**4.4. Reflexión final**
**4.4.1. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?**
    Los de nivel alto ya que son mucho más sencillos de utilizar por los humanos.

 **4.4.2. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?**
    En casos donde se necesite tener mayor rapidez de ejecución o necesiten ser recompilados en otras plataformas.

 **4.4.3. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?**
    En ocasiones donde se requiera alta abstracción y por lo general para tener comodidad

 **4.4.4. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?**
    En la programación orientada a objetos el código se organiza por objetos que contienen datos y comportamientos,  a traves del uso de clases.

**5. Herramientas de desarrollo**
**5.1. Primera parte**
    Respecto a las proceso de creación de software identifica un conjunto de herramientas a usar.
 **5.1.1. ¿Qué hace cada una de las herramientas?**
    Los editores de texto se usan para escribir y editar el código fuente de los programas.
    Los compiladores traducen el código fuente a código máquina para pueda ser procesado.
    Los intérpretes ejecutan código línea por línea sin necesidad de compilarlo previamente.
    La documentación se utiliza para facilitar la claridad y comprensión del código
    Los depuradores permiten detener la ejecución de los programas en puntos específicos.
    Los sistemas de gestión de versiones dan la posibilidad de rastrear cambios en el código, trabajar en varias ramas y contribuir sin preocupación por sobreescribir el trabajo de ota persona.
    Los frameworks proporcionan una estructura predefinida para desarrollar aplicaciones.
    Las herramientas de prueba se encargan de comprobar que el software funcione correctamente.

 **5.1.2. ¿Qué tipo de tareas facilita?**
    Los editores de texto facilitan la edición de código fuente.
    Los compiladores ayudan con el control sobre la optimización del código.
    Los intérpretes facilitan la edición y ejecución inmediata del código gracias a no requerir ser compilados.
    La documentación se utiliza para facilitar la comprensión del código
    Los depuradores facilitan la identificación de errores complejos.
    Los sistemas de gestión de versiones ayudan a trabajar en equipo.
    Los frameworks facilitan la creación de proyectos gracias a las librerías y plantillas reutilizables
    Las herramientas de prueba sirven para mejorar la mantenibilidad y legibilidad del código.

 **5.1.3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?**
    Los editores de texto consumen muy pocos recursos y pueden ser utilizados por múltiples sistemas.
    Los compiladores generan código ejecutable de alto rendimiento y ofrecen más control sobre la optimización del código.
    Los intérpretes no requieren de procesos de compilación y permite ejecutar código de manera interactiva.
    La documentación reducen el esfuerzo manual de crear documentación y hace que se mantenga actualizada.
    Los depuradores permiten identificar errores y ver el estado del programa a tiempo real.
    Los sistemas de gestión de versiones permiten trabajar en equipo mucho más fácilmente.
    Los frameworks ahorran tiempo por reutilizar componentes y estandarizan la estructura del código.
    Las herramientas de prueba detectan errores y mantienen el código legible.

 **5.1.4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?**
    Los depuradores permiten ejecutar el programa paso a paso, con lo cual se pueden detectar fallos específicos con bastante facilidad. 
    Python Debugger tiene una serie de comandos que le permiten al depurador ir de línea en línea comprobando el código, de forma que el programador puede ver claramente dónde se encuentra el problema de forma extremadamente sencilla, ya que solo requiere de un comando.
 **5.1.5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?**
    Los depuradores son perfectos para utilizarlos en programas extensos que posean algún error difícil de ser identificado, ya que puede comprobarse en qué linea puede hallarse este.

 **5.1.6. Elige una ¿Qué limitaciones encontraste en la herramienta?**
    El problema de los depuradores se halla especialmente en el tiempo que se invierte en el análisis del código, ya que su uso puede llevarse a cabo durante periodos bastante prolongados.

**5.2. Segunda parte**
    Céntrate en una herramienta dentro de la misma categoría y compárala con otras:
 **5.2.1. ¿Qué herramienta se considera más útil y por qué?**
    De los compiladores para Python, entre CPython y Pypy, PyPy ofrece mayor utilidad puesto que este es mucho más rápido por su compilación en tiempo de ejecución en vez de ser compilado antes como CPython

 **5.2.2. ¿Qué ventajas tiene una sobre la otra?**
    PyPy es mucho más rápido que CPython pero puede no ser compatible con ciertas extensiones, mientras que CPython es más compatible con extensiones.

 **5.2.3. ¿Cuál herramienta resultó ser la más intuitiva y por qué?**
    Ambas son igual de intuitivas debido a su funcionamiento casi idéntico.

**5.2.4. ¿En qué casos se recomendaría usar un compilador en lugar de un intérprete?**
    En casos donde se requiera ejecutar el programa más rápido.

 **5.2.5. ¿Qué tipo de proyectos se beneficiarían más de un framework como Django?**
    En proyectos grandes que requieran alta adaptabilidad donde haya que cambiar constantemente el código para ahorrar tiempo.

**5.3. Reflexión final**
 **Con base en la experiencia de evaluación de las herramientas:**
 **5.3.1. ¿Cómo crees que impacta la elección de la herramienta en la calidad del software?**
    Escoger una herramienta adecuada para cada proyecto puede ayudar a ahorrar mucho tiempo y facilitar el proceso de creación del propio código.
**5.3.2. ¿Qué características buscarías en una herramienta para facilitar tu flujo de trabajo?**
    Lo ideal sería encontrar características que coincidan con las necesidades del proyecto

 **5.3.3. ¿Cómo cambió tu percepción de estas herramientas después de haberlas probado y evaluado?**
    Como Pypy es más rápido en tiempo de ejecución que el propio intérprete de Python, esto lo hace más útil en lo que a programas con tiempos de ejecución prolongados se refiere. 
