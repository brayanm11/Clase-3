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

  - $$A+B+C=2$$

 - $$-5A-2B-C=0$$

 -  $$6A-3B-2C=-4$$

4. Se reuelve el sistema de ecuaciones:

  -  $$A=2, B=-1, C=1$$

5. Sustitución en la fracción parcial:



## 9. Ejercicios
Deben agregar 2 ejercicios con su respectiva solución, referentes a los temas tratados en cada una de las clases. Para agregar estos, utilice la etiqueta #, es decir como un nuevo título dentro de la clase con la palabra 'Ejercicios'. Cada uno de los ejercicios debe estar numerado y con su respectiva solución inmediatamente despues del enunciado. Antes del subtitulo de cada ejercicio incluya el emoji 📚

## 10. Conclusiones

La descomposición en fracciones parciales es una técnica fundamental para simplificar funciones racionales y resolver ecuaciones algebraicas en cálculo y análisis de señales.

Se pueden manejar distintos casos según el tipo de raíces del denominador.

Matlab y Python permiten automatizar estos cálculos de forma eficiente.

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
