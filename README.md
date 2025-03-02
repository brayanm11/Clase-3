# Descomposición en Fracciones Parciales
La descomposición en fracciones parciales es una técnica utilizada en cálculo y álgebra para simplificar expresiones racionales, es decir, fracciones donde el numerador y el denominador son polinomios. Esta técnica es especialmente útil para resolver integrales y transformadas de Laplace, ya que permite descomponer una fracción compleja en una suma de fracciones más simples que son más fáciles de manejar.
## 1. Casos de Descomposición en Fracciones Parciales
1.1  Raíces Reales Distintas

Si el denominador tiene raíces reales distintas, la descomposición es de la forma: $G(s)=\frac{A}{s+p1}+\frac{B}{s+p2}+\frac{C}{s+p3}$

1.2  Raíces Reales Repetidas

Si el denominador tiene raíces repetidas, se debe considerar: $G(s)=\frac{A}{s+p}+\frac{B}{(s+p)^{2}}+\frac{C}{(s+p)^{3}}$

1.3  Raíces Complejas Conjugadas

Cuando el denominador tiene términos cuadráticos irreducibles: $G(s)=\frac{As+B}{s^{2}+bs+c}+\frac{Cs+D}{s^{2}+ds+e}$

## 2. Conceptos Claves
🔑 Fracción Propia:

Una fracción donde el grado del polinomio del numerador es menor que el grado del polinomio del denominador.

🔑 Fracción Impropia:

Una fracción donde el grado del numerador es mayor o igual al grado del denominador. En estos casos, se debe realizar una división de polinomios antes de aplicar la descomposición.

🔑 Raíces de un Polinomio:

Los valores de la variable que hacen que el polinomio sea igual a cero.

## 3. Ejemplos

💡 Ejemplo 1: Obtener la descomposición en fracciones parciales de:  $G(s)=\frac{2s^{2}-4}{(s+1)(s-2)(s-3)}$

Solución

1. Expresión en fracciones parciales:  $G(s)=\frac{2s^{2}-4}{(s+1)(s-2)(s-3)}=\frac{A}{s+1}+\frac{B}{s-2}+\frac{C}{s-3}$
2. Multiplicamos ambos lados por el denominador común:  $2s^{2}-4= A(s-2)(s-3)+B(s+1)(s-3)+C(s+1)(s-2)$
3. Expandimos y agrupamos términos en $s^{2}$, s  y constantes:

3.1  $A+B+C=2$
3.2 $-5A-2B-C=0$

## 4. Ejemplos
Si en algún caso pretende dar un ejemplo explicativo ya sea a través de texto o através de ecuaciones matemáticos, utilizar la palabra 'Ejemplo' seguido de una numeración consecutiva dentro de la clase. Utilice el emoji 💡 antecediendo la palabra.

## 5. Ecuaciones
Para la edición de ecuaciones debe utilizar la etiqueta '$$' al comienzo y final de la ecuación para que la ecuación quede centrada ocupando una línea. Si se quiere que la ecuación quede integrada en el texto debe utilizar la etiqueta '$' al comienzo y final de la ecuación. Las ecuaciones pueden ser editadas utilizando el código LATEX, en el siguiente enlace encuentran un editor de ecuaciones que les genera el código. http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp . Sin embargo hay muchas otras herramientas que pueden utilizar para esto.

💡**Ejemplo 1:** si se va a representar la ecuación de la ley de Ohm se puede mostrar así $R=\frac{V}{I}$ o también,

$$R=\frac{V}{I}$$

## 6. Figuras
Todas las figuras que incluya deben ser generadas por ustedes, **no utilizar las figuras de las presentaciones**. Para incluir figuras puede seguir los siguientes pasos:
* Primero escribimos ![]().
* Después escribimos, dentro de los corchetes, el texto alternativo. Este es opcional y solo entra en acción cuando no se puede cargar la imagen correctamente.
* Después escribimos, dentro de los paréntesis, la ubicación del archivo (ya sea una url o una ubicación dentro de algun folder local). Se recomienda poner las imágenes en una carpeta que se llame imágenes dentro del repositorio github para que no tengan problemas al cargar las imágenes.

💡**Ejemplo 2:**

![Figura de prueba](images/plantilla/Captura2.PNG)

Figura 1. Figura de prueba

Incluya la respectiva etiqueta a modo de descripción de la figura y mantenga numeración consecutiva para todas las figuras de la clase.

## 7. Tablas
En caso de necesitar la inclusión de tablas para organizar información se recomienda el uso de la herramienta del siguiente enlace https://www.tablesgenerator.com/markdown_tables , la cual permite organizar la información dentro de la tabla y genera el código markdown automáticamente:

💡**Ejemplo 3:** 

| **Resultado** | **x = número de intentos hasta primer éxito** |
|---------------|-----------------------------------------------|
|       S       |                       1                       |
|       FS      |                       2                       |
|      FFS      |                       3                       |
|      ...      |                      ...                      |
|    FFFFFFS    |                       7                       |
|      ...      |                      ...                      |

Tabla 1. Tabla de ejemplo

Cada tabla debe llevar la etiqueta que describa su contenido y numeración consecutiva para todas las tablas

## 8. Código
Teniendo en cuenta que el curso requiere del desarrollo de código matlab, c, c++ u otro. Si requiere incluir pequeños segmentos de código en los apuntes hágalos de la siguiente manera:

💡**Ejemplo 4:**
```
var sumar2 = function(numero) {
  return numero + 2;
}
```

## 9. Ejercicios
Deben agregar 2 ejercicios con su respectiva solución, referentes a los temas tratados en cada una de las clases. Para agregar estos, utilice la etiqueta #, es decir como un nuevo título dentro de la clase con la palabra 'Ejercicios'. Cada uno de los ejercicios debe estar numerado y con su respectiva solución inmediatamente despues del enunciado. Antes del subtitulo de cada ejercicio incluya el emoji 📚

## 10. Conclusiones

La descomposición en fracciones parciales es una técnica fundamental para simplificar funciones racionales y resolver ecuaciones algebraicas en cálculo y análisis de señales.

Se pueden manejar distintos casos según el tipo de raíces del denominador.

Matlab y Python permiten automatizar estos cálculos de forma eficiente.

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
