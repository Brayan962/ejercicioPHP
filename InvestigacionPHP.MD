# Trabajo investigacion PHP

### ¿Que es el PHP? ###
#### R) Es un lenguaje de programacion de código abierto que se utiliza para desarrollar sitios web dinámicos es un lenguaje de scripting del lado del servidor que se ejecuta en el servidor y genera HTML desarrollar aplicaciones para la web y crear páginas web, favoreciendo la conexión entre los servidores y la interfaz de usuario. Entre los factores que hicieron que PHP se volviera tan popular, se destaca el hecho de que es de código abierto y que se ejecuta en el servidor web.
#### Caracteristicas de PHP
- Documentación y plantillas: este lenguaje, al ser abierto y gratuito, permite el desarrollo y crecimiento de una comunidad que, además de ser muy activa, ofrece sus conocimientos al momento de trabajar con PHP con la comunidad.
- Oferta laboral: el lenguaje permite el desarrollo de sitios webs complejos y dinámicos. Por ello, cada vez son más las empresas e instituciones que requieren de este servicio en particular para sus páginas y plataformas.
- Orientado a objetos: permite que el procesamiento de datos sea mucho más rápido debido a que los scripts en métodos.

### Casos de usos donde se usa el PHP

 **Algunos casos de usos encontramos los siguientes:**

 - Generar contenido dinámico para sitios web.
 - Crear sitios web estáticos.
 - Recolectar datos de formularios.
 - Enviar y recibir cookies.
 - Consultar contenidos de bases de datos.
 - Crear aplicaciones de escritorio.
 - Crear secuencias de comandos de línea de comandos.
 
 **Además de eso en las páginas que más se usan estan:**
 - Facebook.
 - Wikipedia. 
 - Etsy.
 - Slack.
 - Alibaba.com

 ### Ventajas y Desventajas de PHP
**Algunas de las ventajas se encuentran:**
 - Autocompletado de código: Que sugiere terminaciones posibles mientras se escribe.
 - Refactorización inteligente: Que permite modificar estructuras de código sin romper la funcionalidad.
 - Herramientas de búsqueda de definiciones y referencias: Que permiten moverse entre clases, métodos y archivos.

**Algunas de las desventajas se encuentran:**
 - Aprender sobre framework de PHP: si bien tener entornos de trabajo o frameworks permite añadir funciones sin escribir código adicional, para un desarrollador esto supone tener que aprender las utilidades del framework.
 - Mala calidad de manejo de errores: una de las principales desventajas de PHP es que no tiene herramientas de depuración, que son necesarias para buscar errores y advertencias.
 - Se necesita un servidor web: para ejecutar el software en Internet hay que contar con un hosting.

### Estructura de Control de PHP
Las estructuras de control en PHP son instrucciones que modifican el flujo de ejecución de un programa. Permiten tomar decisiones, repetir acciones o realizar bifurcaciones condicionales
las estructuras de control son fundamentales en PHP porque permiten que los scripts respondan de manera diferente a distintas entradas o situaciones. 

**Los tipos de estructura de control PHP son:**

 **Estructuras condicionales** 
+ If: Ejecuta un fragmento de código si la expresión es verdadero por ejemplo:

`$edad = 25; if ($edad >= 18) {echo "Eres mayor de edad. Puedes votar.";}`

 **Estructuras repetitivas**
 + For: es una instrucción que permite repetir un bloque de código un número determinado de veces. Es útil cuando se conoce el número de iteraciones que se quieren realizar por ejemplo:

`for ($i = 1; ; $i++) {
if ($i > 10) {
break;
}
echo $i;
}`

 + ForEach: permite ejecutar bloques de código varias veces, cada uno con su propia parte se utiliza para iterar a través de una matriz o colección de elementos y realizar acciones específicas en cada elemento
   El bucle foreach es una estructura repetitiva que, junto con el bucle for, es esencial para automatizar tareas y procesar datos de manera eficiente por ejemplo:

`$frutas = array("Manzana", "Banana", "Naranja", "Pera");
foreach ($frutas as $fruta) {
echo "La fruta es: $fruta <br>";
}`

