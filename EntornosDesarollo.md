# Guía de Estudio: Software, Programación y UML

## Cuestionario de Comprensión

Responda brevemente a las siguientes preguntas (2-3 frases cada una):

1.  ¿Cuál es la principal diferencia entre un programa informático y el software según la norma IEEE/ISO/IEC 24765:2017?
2.  Proporcione dos ejemplos de software de sistema y explique su propósito general.
3.  ¿Cómo se define un algoritmo según el IEEE?
4.  ¿Qué diferencia clave existe entre los lenguajes de bajo nivel y los de alto nivel?
5.  Explique la distinción entre código fuente, código objeto y código ejecutable en el proceso de desarrollo.
6.  ¿Cuál es la función principal de una máquina virtual de proceso (como la JVM o el CLR)?
7.  ¿Qué significa que un software sea multiplataforma?
8.  Describa brevemente la fase de diseño en el ciclo de vida del desarrollo de software.
9.  ¿En qué se diferencia el modelo de desarrollo iterativo e incremental del modelo en cascada?
10. ¿Cuál es el propósito del comando `svn add` en Subversion?

---

## Clave de Respuestas del Cuestionario

1.  **¿Cuál es la principal diferencia entre un programa informático y el software según la norma IEEE/ISO/IEC 24765:2017?**
    Un programa informático es una combinación de instrucciones y datos para realizar funciones computacionales. El software, en un sentido más amplio, engloba programas, procedimientos, documentación y datos asociados.

2.  **Proporcione dos ejemplos de software de sistema y explique su propósito general.**
    Los **sistemas operativos** y los **drivers** son ejemplos de software de sistema. Su propósito es facilitar el funcionamiento y mantenimiento del hardware y sus programas asociados.

3.  **¿Cómo se define un algoritmo según el IEEE?**
    Según el IEEE, un **algoritmo** es un conjunto finito de reglas bien definidas para solucionar un problema en un número finito de pasos, o una secuencia de operaciones para una tarea específica.

4.  **¿Qué diferencia clave existe entre los lenguajes de bajo nivel y los de alto nivel?**
    Los **lenguajes de bajo nivel** están más cerca del hardware y son específicos del procesador (como el ensamblador), mientras que los **lenguajes de alto nivel** tienen un mayor nivel de abstracción y son más cercanos al lenguaje natural.

5.  **Explique la distinción entre código fuente, código objeto y código ejecutable en el proceso de desarrollo.**
    El **código fuente** es el código escrito por el programador; el **código objeto** es el resultado de la compilación del código fuente; el **código ejecutable** es el archivo final listo para ser ejecutado después del enlazado con las bibliotecas necesarias.

6.  **¿Cuál es la función principal de una máquina virtual de proceso (como la JVM o el CLR)?**
    Una **máquina virtual de proceso** actúa como puente entre el código intermedio (bytecode o CIL) y el código máquina, proporcionando un entorno de ejecución independiente del hardware y sistema operativo.

7.  **¿Qué significa que un software sea multiplataforma?**
    Un software **multiplataforma** es aquel que puede ser ejecutado en diferentes combinaciones de hardware y sistemas operativos.

8.  **Describa brevemente la fase de diseño en el ciclo de vida del desarrollo de software.**
    La **fase de diseño**, basada en los requisitos del análisis, establece cómo se va a implementar la solución al problema, definiendo estructuras de datos, clases y algoritmos.

9.  **¿En qué se diferencia el modelo de desarrollo iterativo e incremental del modelo en cascada?**
    El **modelo iterativo e incremental** combina las fases del modelo en cascada de forma repetida con la interacción del cliente, reutilizando y aumentando gradualmente la funcionalidad de un prototipo, a diferencia del **modelo en cascada** que es secuencial.

10. **¿Cuál es el propósito del comando `svn add` en Subversion?**
    El comando `svn add` en Subversion se utiliza para añadir un fichero o directorio a la lista de elementos que serán puestos bajo el control de versiones en la copia de trabajo local.

---

## Preguntas de Ensayo

Responda a las siguientes preguntas en formato de ensayo, utilizando información de los textos proporcionados:

1.  Compare y contraste los sistemas de control de versiones locales, centralizados y distribuidos, discutiendo las ventajas y desventajas de cada tipo.
2.  Explique en detalle el ciclo de vida del desarrollo de software tradicional (modelo en cascada) y cómo se relaciona con los modelos iterativo e incremental y en espiral.
3.  Describa el proceso completo para obtener un código ejecutable a partir del código fuente, incluyendo las fases de edición, traducción/compilación y enlazado, y cómo las tecnologías de virtualización (JVM, CLR) encajan en este proceso.
4.  Analice los diferentes tipos de lenguajes de programación según su nivel y evolución (generaciones), proporcionando ejemplos de cada categoría.
5.  Explique los componentes y tipos de relaciones en un diagrama de casos de uso de UML, describiendo cómo representan la interacción del sistema con elementos externos y entre sí.

---

## Glosario de Términos Clave

* **Algoritmo:** Conjunto finito de reglas bien definidas para la solución de un problema en un número finito de pasos. También, secuencia de operaciones para realizar una tarea específica.
* **Bytecode:** Código intermedio (Java bytecode o CIL) generado por un compilador para ser ejecutado en una máquina virtual de proceso (JVM o CLR).
* **Check-in (ci):** Operación en un sistema de control de versiones local (como RCS) para registrar o confirmar cambios realizados en un fichero bajo control de versiones.
* **Checkout (co):** Operación en un sistema de control de versiones para obtener una copia de trabajo local de un fichero o proyecto desde el repositorio. En RCS, también se utiliza para obtener una versión editable.
* **CLR (Common Language Runtime):** Entorno de ejecución del entorno .NET de Microsoft, basado en la idea de máquina virtual de proceso y que ejecuta CIL.
* **Código Ejecutable:** Código que, tras el proceso de compilación y enlazado, puede ser ejecutado directamente por el ordenador.
* **Código Fuente:** Unidad sintáctica que se ajusta a las reglas de un lenguaje de programación particular, compuesta por declaraciones e instrucciones para realizar una función o tarea.
* **Código Objeto:** Código obtenido mediante un proceso de compilación del código fuente. Generalmente lenguaje máquina o bytecode, no es directamente ejecutable sin la fase de enlazado.
* **Commit (`svn ci`):** Operación en Subversion para enviar los cambios realizados en la copia de trabajo local al repositorio remoto, creando una nueva revisión.
* **Compilador:** Programa que genera código objeto a partir de código fuente.
* **Diagrama de Casos de Uso (UML):** Diagrama que representa la interacción del sistema con elementos externos (actores) y las funcionalidades del sistema (casos de uso), mostrando el sistema desde la perspectiva del usuario.
* **Diagrama de Clases (UML):** Diagrama estructural que representa la estructura de clases, atributos, métodos y relaciones entre las clases que forman un sistema.
* **Diagrama de Secuencia (UML):** Diagrama de interacción que muestra la interacción entre diferentes objetos dentro de un escenario particular de ejecución del sistema.
* **`diff`:** Comando utilizado para comprobar las diferencias línea a línea entre dos ficheros de texto.
* **Editor de Código:** Aplicación para crear y modificar código fuente.
* **Enlazado:** Fase en el proceso de obtención de un ejecutable donde se combinan los diferentes ficheros de código objeto con las bibliotecas del sistema necesarias.
* **Hardware:** Componentes físicos y tangibles de un sistema informático.
* **IDE (Integrated Development Environment):** Entorno de desarrollo integrado, una aplicación que proporciona herramientas completas para el desarrollo de software, como editor de código, compilador, depurador, etc.
* **Ingeniería Inversa:** Proceso de generar un diagrama (como un diagrama de clases) a partir del código fuente existente.
* **Iterativo e Incremental (Modelo):** Modelo de desarrollo de software que combina las fases del modelo en cascada aplicadas repetidamente, incrementando la funcionalidad de un prototipo con cada iteración.
* **JDK (Java Development Kit):** Kit de desarrollo de Java, que incluye el JRE, el compilador y otras herramientas necesarias para desarrollar aplicaciones Java.
* **JRE (Java Runtime Environment):** Entorno de ejecución de Java, que incluye la JVM y las bibliotecas necesarias para ejecutar aplicaciones Java.
* **JVM (Java Virtual Machine):** Máquina virtual de Java, una máquina virtual de proceso que ejecuta Java bytecode, permitiendo el desarrollo multiplataforma.
* **Lenguaje de Programación:** Lenguaje diseñado para especificar el conjunto de reglas que debe realizar un sistema informático para resolver un problema.
* **Multiplataforma:** Software que puede ser ejecutado en diferentes combinaciones de hardware y sistemas operativos.
* **Peopleware:** Componente humano de un sistema informático, abarcando los aspectos relacionados con el papel de las personas en el desarrollo y uso de software y hardware.
* **Programa Informático:** Combinación de instrucciones y definiciones de datos que permiten al hardware realizar funciones computacionales o de control.
* **Prototipado:** Modelo de desarrollo de software que implica la creación rápida de una versión preliminar del sistema (prototipo) para validar requisitos o explorar soluciones.
* **Pseudocódigo:** Representación de un algoritmo de modo más cercano al ordenador que el lenguaje natural, pero sin las reglas sintácticas estrictas de un lenguaje de programación.
* **RCS (Revision Control System):** Un sistema de control de versiones local que guarda las diferencias entre versiones de ficheros.
* **`rlog`:** Comando en RCS para obtener información del registro de cambios de un fichero.
* **`rcsdiff`:** Comando en RCS para ver las diferencias entre dos revisiones de un fichero.
* **SCV (Sistema de Control de Versiones):** Sistema que registra los cambios producidos en un conjunto de ficheros a lo largo del tiempo, permitiendo volver a versiones anteriores, ver cambios y quién los hizo.
* **Scrum Diario (Daily Scrum):** Reunión diaria corta en la metodología Scrum para sincronizar tareas del equipo, comentar el estado del trabajo y problemas surgidos.
* **Software:** Programas informáticos, procedimientos, documentación asociada y datos relacionados con el funcionamiento de un sistema informático. La parte intangible del sistema informático.
* **Software de Aplicación:** Software diseñado para ayudar al usuario a realizar tareas concretas o resolver problemas específicos (ej: procesadores de texto, hojas de cálculo).
* **Software de Soporte:** Software dedicado al desarrollo y mantenimiento de otro software (ej: compiladores, intérpretes, editores).
* **Software de Sistema:** Software diseñado para facilitar el funcionamiento y mantenimiento de un sistema informático y sus programas asociados (ej: sistemas operativos, drivers).
* **Sprint (Scrum):** Periodo de tiempo fijo en la metodología Scrum durante el cual el equipo de desarrollo trabaja para completar un conjunto de tareas.
* **Sprint Planning:** Reunión al comienzo de un sprint en Scrum para planificar las tareas y objetivos del sprint a partir del Product Backlog.
* **`svn add`:** Comando en Subversion para añadir un fichero o directorio al control de versiones en la copia de trabajo local.
* **Subversion (SVN):** Un sistema de control de versiones centralizado.
* **`svn ci` (commit):** Comando en Subversion para enviar los cambios realizados en la copia de trabajo local al repositorio remoto.
* **`svn checkout`:** Comando en Subversion para obtener una copia de trabajo local de un proyecto desde el repositorio.
* **`svn st`:** Comando en Subversion para consultar el estado de los ficheros en la copia de trabajo local.
* **`svn up`:** Comando en Subversion para actualizar la copia de trabajo local con los últimos cambios del repositorio.
* **UML (Lenguaje Unificado de Modelado):** Lenguaje de modelado visual estándar para especificar, construir y documentar los artefactos de un sistema de software.
* **Umbrello:** Editor de diagramas UML.
* **Virtualización:** Posibilidad de ejecutar una o varias máquinas virtuales sobre una única máquina física. Puede ser de sistema/hardware o de proceso/aplicación.
* **Visual Studio Code (VSCode):** Editor de código ligero y multiplataforma.
* **Workspace (Eclipse):** Directorio de trabajo en Eclipse donde se guardan los proyectos, preferencias y extensiones.