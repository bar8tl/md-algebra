[Indice general](_index.md) > [Capitulo 2](ch02-00-operaciones-algebraicas.md)

# Álgebra

## Capítulo 2 Operaciones Algebraicas

### **2.4. SUSTRACCION**

En el Art. 1.3 describimos la sustracción como la operación inversa de la
adición. La sustracción queda *definida* bajo la siguiente

HIPOTESIS. Dados dos números cualesquiera $a$ y $c$, existe un número $b$ y solo
uno tal que

(1) $a+b=c$.

Este número $b$ está dado por la igualdad

(2) $b=c-a$

que se lee "$b$ es igual a $c$ menos $a$" y en la cual diremos que $b$ es la
*diferencia* obtenida al *restar el sustraendo* $a$ del *minuendo* $c$.

Ejemplo: $5+2=7$, siendo $2=7-5$.

También podemos decir que $b$ es el número que debe ser *sumado* con $a$ para
producir el número $c$. Así, de (1) y (2) obtenemos la relación

(3) $a+(c-a)=c$.

La sustracción tiene la siguiente propiedad:

*Propiedad sustractiva de la igualdad*. Si $a$, $b$ y $c$ son números
cualesquiera tales que $a=b$, entonces $a-c=b-c$.

El estudiante reconocerá esta ley como el conocido axioma que dice: si se restan
números iguales de números iguales las diferencias son iguales.

Es importante observar que según la hipótesis hecha anteriormente el resultado
de la sustracción es *único*. Ahora veremos cómo se puede hacer posible la
operación de restar en cualquier caso. Para ello veamos primero lo que significa
la expresión "un número es *mayor* que otro".

**Definición**. Se dice que el número $x$ es *mayor* que el número $y$ si $x-y$
es un número positivo. Entonces escribimos $x>y$, que se lee "$x$ es mayor que
$y$".

*Ejemplo:* $7>5$, ya que $7-5=2$, siendo $2$ un número positivo.

La relación $x>y$ implica también que $y$ es *menor* que $x$, escribiéndose
$y<x$. Estas dos relaciones son, por supuesto, equivalentes.

Haciendo referencia a la anterior relación (2), resulta que se deben considerar
tres casos.

(I) $a<c$. Entonces $b=c-a$ es un número positivo. Este caso corresponde al caso
aritmético ordinario en que se resta un número de otro mayor.

(II) $a=c$. En este caso $b=c-a=c-c=0$ por definición de cero (Art. 1.3). Por lo
tanto, de (1) tenemos

$a+0=a$

y luego, por la ley conmutativa de la suma (Art. 2.3), tenemos

(4) $a+0=0+a=a$,

lo cual expresa una importante propiedad del cero.

(III) $a>c$. En este caso se trata de restar un número de otro menor. Esta es la
primera desviación importante respecto a las operaciones aritméticas.

De $a>c$ se concluye que $a-c=p$, en donde $p$ es un número positivo, de modo
que la expresión $c-a$ de la relación (2) no tiene sentido en un sistema
restringido a los números enteros y positivos. Para hacer posible la resta en
este caso *definimos* a $c-a$ en la relación (2) como un *número negativo* y
escribimos

$c-a=-p$,

(5) $c-a=-(a-c)$.

Como un ejemplo de la relación (5) tenemos

$5-7=-(7-5)=-2$.

En el caso particular en que $c=0$, el número negativo $c-a$ que hemos definido
toma la forma $0-a$, que se abrevia escribiendo $-a$ y se llama el *negativo* de
$a$. Esto es,

(6) $0-a=-a$.

El número positivo $p$ se escribe a veces $+p$, leyéndose "más $p$" para hacer
destacar el signo positivo. El número negativo $-p$, eue se lee "menes $p$"
siempre va precedido del signo negativo. Si $p$ es cualquier número positivo, es
conveniente llamar a $-p$ su *número negatiuo correspondiente*. Así, $-5$ es el
número negativo correspondiente a $5$.

El *valor absoluto* de cualquier número $a$, se representa por $|a|$, y
significa su valor aritmético ordinario sin considerar el signo. por ejemplo
$|5|=5$ y $|-2|=2$. Evidentemente, cualquier número positivo y su número
negativo correspondiente tienen el mismo valor absoluto.

Al hablar de los números con signos hemos usado los signos positivo y negativo
como *signos de cualidad que denotan "número positivo" o "número negativo"*. Sin
embargo estos mismos signos han sido usados previamente como *sígnos de
operación*. Este doble uso o significado de los signos positivo y negativo queda
justificado con los teoremas siguientes.


**Teorema 1**. *La suma de cualquier número poitivo con su correspondiente
número negatiuo es cero*.

DEMOSTRACIÓN. Sea $a$ cualquier número positivo, de modo que $-a$ es su número
negativo correspondiente. Entonces por la anterior relación (6),

$a+(-a)=a+(0-a)$.

Si ahora hacemos $c=0$ en la relación (3), que es la definición de sustracción,
tenemos $a+(0-a)=0$, de modo que el segundo miembro de la igualdad anterior se
anula.

Por lo tanto, $a+(-a)=0, como se quería demostrar.

Un ejemplo sencillo de este teorema es $5+(-5)=0$.

**Teorema 2**. *La operación de sumar un número negativo es equivalente a la
operación de restar un número positivo que tenga el mismo valor absoluto.*

DEMOSTRACION. Sea $a$ un número cualquiera y $b$ un número positivo, de modo que
$-b$ es su número negativo correspondiente. Vamos a probar que

(7) $a+(-b)=a-b$.

Por la ley de unicidad de la adición (Art. 2.3),

(8) $a+(-b)=c$,

Añadiendo $b$ a ambos lados (propiedad aditiva de la igualdad, Artículo 2.3),

$[a+(-b)]+b=c+b$.

de donde, por la ley asociativa, $a+[(-b)+b]=c+b.

Por el teorema 1, $(-b)+b=0$.

Luego, $a+0=c+b$,

y por (4), $a=c+b$

y por las relaciones (1) y (2), tenemos

(9) $c=a-b$.

De las igualdades (8) y (9) obtenemos (7) que es lo que se quería demostrar.

También se puede establecer, por medio del teorema 2 y de la definición de
sustracción, el teorema siguiente:

**Teorema 3**. *La operación de restar un núnero negatiuo es equiavalente a la
operación de sumar un número positivo del mismo valor absoluto*.

Es decir. si $a$ es un número cualquiera y $b$ es un número positivo, siendo
$-b$ su número negativo correspondiente, entonces

$a-(-b)=a+b$

la demostración de este teorema se deja como ejercicio.

Ahora estamos en situación de caracterizar completamente la operación de la
adición algebraica.

**Teorema 4**. *Si $a$, $b$ y $p=a+b$ son tres números positivos,de modo que
$-a$, $-b$ y $-p$ representan, respectivamente sus números negativos
correspondientes, entonces en la adición algebraica son válidas las siguientes
relaciones:*

I\. $a+b=p$.

II\. $-a+(-b)=-a-b=-(a+b)=-p$.

III\. Si $a>b$, entonces $a+(-b)=a-b$.<nb>
Si $a<b$, entonces $a+(-b)=a-b=-(b-aJ$.

La relación I es aritmética y es parte de la hipótesis. Las relaciones II y III
son consecuencia del teorema 2 y de la relación (5).

Estas relaciones pueden ser enunciadas como sigue:

I y II. Para sumar dos números de signos iguales súmense sus valores absolutos y
antepóngase a la suma el signo común.

III\. Para sumar dos números de signos contrarios réstese el de menor valor
absoluto del de mayor valor absoluto y antepóngase a la diferencia el signo del
número que tenga mayor valor absoluto.

Ejemplos:<br>
$2+5=7$.<br>
$(-2)+(-5)=-2-5=-(2+5)=-7$.<br>
$(-2)+(5)=-2+5=5-2=3$.<br>
$(2)+(-5)=2-5=-(5-2)=-3$.

Las relaciones del teorema 4 pueden ser generalizadas a tres o más números.

Como una consecuencia directa de los teoremas 2, 3 y 4, se establece el
siguiente procedimiento para restar:

**Teorema 5**. *La operación de restar un número de otro consiste en cambiar el
signo del sustraendo y luego proceder como en la suma algebraica (Teorema 4)*.

Ahora podemos observar una sencilla pero importante propiedad que relaciona a
los números positivos y negativos y el cero. Sea $a$ un número positivo y por lo
tanto $-a$ un número negativo. Por la relación (4):

$a+0=a$,

de donde, por la definición de sustracción, relación (2), tenemos

(10) $a-0=a$.

Por el teorema 3, $0-(-a)=0+a$

de donde, por la relación (4), resulta:

(11) $0-(-a)=a$,

Ahora, de la definición anterior de "mayor que" se concluye de (10) que

(12) $a>0$,

y de (11), que $0>-a$, o sea,

(13) $-a<0$.

De las relaciones (12 y (13) tenemos:

**Teorema 6**. *Un número positivo es mayor que cero y un número negativo es
menor que cero*.

De este teorema se infiere que el cero *no es ni un número positivo ni un número
negatívo*. Consecuentemente, con el nombre *números no negativos* designamos a
todos los números positivos *y al cero*. Si $a$ es un número de esta clase (no
negativo) escribimos $a\ge0$, que se lee "a es mayor o igual que cero".

Ahora veamos unos ejemplos de operaciones de adición y sustracción algebraicas.

**Ejemplo 1**. Calcular la suma de las siguientes expresiones algebraicas:
$x^3+2x^2y-4xy^2$, $2x^3-4x^2y+3y^3$, $2xy^2-4y^3$,

SOLUCIÓN. Primero escribimos las expresiones de modo que los términos semejantes
queden en columna. Luego aplicamos las leyes de la suma enunciadas en el Teorema
4. El resultado es el siguiente:

$\hspace{50pt}\:\:x^3+2x^2y-4xy^2$<br>
$\hspace{50pt}2x^3-4x^2y\qquad\quad\:+3y^3$<br>
$\hspace{50pt}\qquad\qquad\qquad2xy^2-4y^3$

Suma = $\hspace{20pt}3x^3-2x^2y-2xy^2-y^3$

**Ejemplo 2**. Hallar la diferencia obtenida al restar $a^3-3a^2+4a-7 de
$2a^3+a^2-3a-5$.

SOLUCION. Escribimos el sustraendo debajo del minuendo de modo que los
términos semejantes queden en columna. Entonces, considerando que el signo de
cada término del sustraendo cambia, sumamos los términos semejantes de acuerdo
con el Teorema 5.

Minuendo $\quad2a^3+\:\:\:a^2-3a-5$</br>
Sustraendo $\quad\: a^3-3a^2+4a-7$</br>
Diferencia $\quad\:\:\: a^3+4a^2-7a+2$.

Si al lector le parece más sencillo, al escribir el sustraendo se puede
cambiar el signo de cada término y luego sumar.

La adición v sustracción de expresiones algebraicas a menudo requieren el uso de
símbolos de agrupación (Art.2.3). La simplificación de tales expresiones
requiere quitar estos símbolos. Según nuestros resultados anteriores tenemos el
siguiente procedimiento para manejar una expresión algebraica que está encerrada
entre paréntesis.

Un paréntesis precedido del signo más puede suprimirse sin hacer ningún otro
cambio. Un paréntesis precedido del signo menos puede suprimirse cambiando el
signo de cada uno de los términos encerrados en él.

Si una expresión contiene más de un símbolo Ce agrupación puede usarse cualquier
orden para suprimir dichos símbolos. Sin embargo, es generalmente más sencillo
suprimir un símbolo de agrupación en cada paso, suprimiendo cada vez el símbolo
que no tiene en su interior otros símbolos de agrupación.

**Ejemplo 3**. Simplificar la expresión:

$5a-(2a-{4a+2b+[a-3b]})$.

SOLUCION. Suprimiendo primero el paréntesis rectangular tenemos

$5a-(2a-{4a+2b+a-3b})$</br>
$=5a-(2a-4a-2b-a+3b)$</br>
$=5a-2a+4a+2b+a-3b=8a-b$.

Al adquirir práctica, el estudiante puede efectuar dos o más pasos a la vez
acortando considerablemente la simplificación.

**EJERCICIOS. GRUPO 1.**

En cada uno de los ejercicios 1-5 calcular la suma de las expresiones
algebraicas dadas.

1\. $2a^3-2a^2b+2b^3$, $3a^2b-4ab^2-4b^3$, $2ab^2-a^3$.

2\. $4m^2-3mn+2n^2$, $6mn-2n^2+5$, $3n^2-3-2m^2$.

3\. $x^2-4xy+3y^2$, $2x^2+2xy-2y^2$, $2xy-y^2-x^2$.

4\. $3x^3-8x^2+9x$, -x^3+3x^2-8$, $2x^3-2x^2-7x+5$.

5\. $c^2+2cd-2d$, $3c-3cd-2d^2$, $c^2+4d-2c+2d^2$.

En cada uno de los ejercicios 6-10 hallar la diferencia obtenida al restar la
segunda expresión de la primera.

6\. $3a-2b+4c-d$, $2a+b-3c-d$.

7\. $x^3-4x^2+2x-5$, $-x^3+2x^2-3x-3$.

8\. $a^3-3a^2b+3ab^2-b^3$, $a^3-4a^2b+2ab^2+b^3$.

9\. $2a+4by-2cy^2+dy^3$, $2dy^3-2by-a+3cy^2$.

10\. $m^4+6m^3-7m2+8m-9$, $2m^3+3m^2-4m-3$.

En los ejercicios 11-15, $A=x^3+2x^2-3x+1$, $B=2x^3-x^2+4x-7$, y
$C=x^3+x^2-6x-2$.

11\. Calcular $A+B-C$.

12\. Calcular $A-B+C$.

13\. Calcular $A-B-C$.

14\. Calcular $B-A+C$.

15\. Calcular $B-A-C$.

16\. Demostrar que la suma de todas las expresiones en los ejercicios 11-15 es
igual a la expresión en el ejercício 11.

En cada uno de los ejercicios 17-21, simplificar la expresión dada.

17\. $5-{2+3-(4-\overline{3-2})+[5-8]}$.

18\. $4+[5-(6-9+{7-2})-(12-5)]$.

19\. $x+2y-(4y-x+[3x-2y]-{2x-2y})$.

20\. $4a-[6b+{2a-[3b+a-\overline{b+4a}]}]$.

21\. $m+2n-{3m-\overline{2m+n}-(2n-[m-4n])}$.

22\. (a) Hallar el número que debe añadirse. a $4$ para que la suma sea igual a
$15$. (b) Encontrar el número que debe añadirse a $7$ para que la suma sea igual
a $-3$.

23\. (a) Hallar el número que debe restarse de $4$ para que la diferencia sea
$6$. (b) Encontrar el número que debe restarse de $-11$ para que la diferencia
sea $4$.

24\. (a) Hallar el número que al restarle $8$ se obtenga $-2$. (b) Encontrar el
número que al disminuirle $-7$ resulte $4$.

25\. Hallar la expresión que debe sumarse a $3a-2b+4c$ para obtener $2a+3b-2c$.

26\. Encontrar la expresión que debe restarse de $4x+2y-7$ para que la
diferencia  sea igual a $3x-y+5$.

27\. Encontrar la expresión que debe disminuirse en $2m-2n+3p$ para obtener una
diferencia igual a $4m+n-2p$.

Cada uno de los ejercicios 28-31 se refiere a un problema de sustracción.

28\. El minuendo es $2a^2+2ab-b^2$; la diferencia es $a^2+3ab-2b^2$, Hallar el
sustraendo.

29\. El sustraendo es $x^2+3x-7$; la diferencia es $3x^2-3x+4$. Encontrar el
minuendo.

30\. La diferencia es $x^2+2xy-3y^2$; el minuendo es $3x2-2xy+y^2$. Hallar el
sustraendo.

31\. La diferencia es $a^3+3a^2-2a+5$; el sustraendo es $2a^3-2a^2+a-5$. Hallar
el minuendo.

32\. Por medio de Ia definición de "mayor que" comprobar las siguientes
relaciones: $9>2$; $-2>-9$; $2>-9$.

33\. Si $a$ es un número positivo, comprobar las siguientes relaciones:
$-3a>-5a$; $a>-2a$; $-4a<-a$.

34\. Ampliar a tres o más números la ley de unicidad de la adición.

35\. Ampliar a tres o más números la ley conmutativa de la adición.

36\. Generalizar a cuatro o más números la ley asociativa de la adición.

37\. Demostrar que la suma de cualquier número negativo con su valor absoluto es
igual a cero.

38\. Demostrar el Teorema 3 del Art. 2.4.

39\. Dar una demostración detallada del Teorema 4 del Art. 2.4.

40\. Dar una demostración detallada del Teorema 5 del Art. 2.4.

[❮ previous](ch02-03-adicion.md)&nbsp;|&nbsp;
[index](_index.md)&nbsp;|&nbsp;
[next ❯](ch02-05-multiplicacion.md)
