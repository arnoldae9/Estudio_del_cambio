---
author: "Prof. Arnoldo Del Toro Peña"
date: \today
geometry: margin=1in
fontsize: 12pt
lang: es
documentclass: article
header-includes:
  - \usepackage{amsmath}
  - \usepackage{amssymb}
  - \usepackage{mathtools}
  - \everymath{\displaystyle}
  - \everydisplay{\displaystyle}
  - \usepackage{xcolor}
  - \usepackage{tcolorbox}
  - \usepackage{fancyhdr}
  - \pagestyle{fancy}
  - \fancyhead[L]{Arnoldo Del Toro}
  - \fancyhead[R]{Preparatoria}
  - \fancyfoot[C]{\thepage}
  - \tcbuselibrary{most}
  - \newtcolorbox{objetivo}{colback=green!5!white,colframe=green!75!black,title=OBJETIVO}
  - \newtcolorbox{definicion}{colback=yellow!5!white,colframe=orange!75!black,title=DEFINICIÓN}
  - \newtcolorbox{ejemplo}{colback=blue!5!white,colframe=blue!75!black,title=EJEMPLO}
  - \newtcolorbox{ejercicio}{colback=cyan!5!white,colframe=cyan!75!black,title=EJERCICIO}
  - \newtcolorbox{formula}{colback=gray!5!white,colframe=gray!75!black,title=FÓRMULA}
  - \newtcolorbox{nota}{colback=red!5!white,colframe=red!75!black,title=NOTA IMPORTANTE}
---
# Examen de Cálculo Diferencial
## Conceptos Fundamentales: Cambio, Límites, Continuidad y Derivadas

**Nombre:** _________________________________ **Fecha:** _________________

**Instrucciones:** Resuelve todos los problemas mostrando claramente tu procedimiento. Usa las definiciones y teoremas estudiados en clase.

---

## **Sección I: Concepto de Cambio (25 puntos)**

### Problema 1 (10 puntos)
Dada la función $f(x) = x^3 - 2x + 1$:

a) Calcula la razón de cambio promedio en el intervalo $[1, 3]$.

b) Encuentra la ecuación de la recta secante que pasa por los puntos $(1, f(1))$ y $(3, f(3))$.

c) Interpreta geométricamente el resultado del inciso (a).

### Problema 2 (8 puntos)
Un objeto se mueve según la ecuación de posición $s(t) = 2t^2 - 3t + 1$ (en metros), donde $t$ es el tiempo en segundos.

a) Calcula la velocidad promedio entre $t = 1$ y $t = 4$ segundos.

b) ¿Cuál es el significado físico de este resultado?

### Problema 3 (7 puntos)
Explica la diferencia conceptual entre razón de cambio promedio e instantánea. Ilustra tu respuesta con un ejemplo de la vida real.

---

## **Sección II: Límites y Continuidad (30 puntos)**

### Problema 4 (12 puntos)
Evalúa los siguientes límites usando las propiedades de límites:

a) $\lim_{x \to 2} \frac{x^2 - 4}{x - 2}$

b) $\lim_{x \to 0} \frac{\sin(3x)}{x}$

c) $\lim_{x \to \infty} \frac{2x^2 + 3x - 1}{x^2 - 5}$

### Problema 5 (10 puntos)
Dada la función:
$$f(x) = \begin{cases} 
x^2 + 1 & \text{si } x < 2 \\
ax + b & \text{si } x \geq 2 
\end{cases}$$

Encuentra los valores de $a$ y $b$ para que $f(x)$ sea continua en $x = 2$.

### Problema 6 (8 puntos)
Clasifica el tipo de discontinuidad (evitable, de salto, o esencial) para cada función en el punto indicado:

a) $g(x) = \frac{x^2 - 9}{x - 3}$ en $x = 3$

b) $h(x) = \begin{cases} x + 1 & \text{si } x < 0 \\ x - 1 & \text{si } x \geq 0 \end{cases}$ en $x = 0$

c) $k(x) = \frac{1}{x^2}$ en $x = 0$

---

## **Sección III: La Derivada como Razón de Cambio (35 puntos)**

### Problema 7 (15 puntos)
Usando la definición de derivada por límites, calcula $f'(x)$ para:

a) $f(x) = 3x^2 - 4x + 1$

b) $f(x) = \frac{1}{x}$

Muestra todos los pasos del proceso límite.

### Problema 8 (10 puntos)
La ecuación de la recta tangente a la curva $y = x^3 - 2x^2 + x$ en el punto donde $x = 1$ es:

a) Encuentra la derivada de la función.

b) Calcula la pendiente de la recta tangente en $x = 1$.

c) Escribe la ecuación de la recta tangente.

### Problema 9 (10 puntos)
Un tanque de agua tiene forma cónica invertido. El volumen del agua en el tanque está dado por $V(h) = \frac{1}{3}\pi h^3$, donde $h$ es la altura del agua en metros.

a) Encuentra la razón de cambio instantánea del volumen respecto a la altura cuando $h = 2$ metros.

b) Si la altura aumenta a razón de $0.5$ m/min, ¿a qué razón está cambiando el volumen cuando $h = 2$ metros?

---

## **Sección IV: Notaciones y Conceptos Teóricos (10 puntos)**

### Problema 10 (5 puntos)
Convierte las siguientes expresiones entre las notaciones de Newton y Leibniz:

a) $\dot{x}(t) = 3t^2$ (notación de Newton) → notación de Leibniz

b) $\frac{dy}{dx} = 2x + 5$ (notación de Leibniz) → notación de Newton

### Problema 11 (5 puntos)
**Verdadero o Falso** (justifica tu respuesta):

a) Si una función es continua en un punto, entonces es derivable en ese punto.

b) Si una función es derivable en un punto, entonces es continua en ese punto.

c) La función $f(x) = |x|$ es continua pero no derivable en $x = 0$.

---

## **Sección V: Aplicaciones y Análisis (Problema Bonus - 10 puntos extra)**

### Problema 12 (10 puntos)
Una empresa determina que el costo total de producir $x$ unidades de un producto está dado por:
$$C(x) = 0.01x^3 - 0.5x^2 + 100x + 2000$$

a) Encuentra la función de costo marginal $C'(x)$.

b) Calcula el costo marginal cuando se producen 50 unidades.

c) Interpreta económicamente el resultado del inciso (b).

d) ¿En qué intervalo de producción el costo marginal es mínimo?

---

## **Criterios de Evaluación:**

- **Procedimiento correcto:** 60% de la calificación
- **Respuesta correcta:** 30% de la calificación  
- **Claridad y organización:** 10% de la calificación

**Fórmulas importantes a recordar:**

- Definición de límite: $\lim_{x \to a} f(x) = L$ ssi para todo $\varepsilon > 0$ existe $\delta > 0$ tal que si $0 < |x - a| < \delta$, entonces $|f(x) - L| < \varepsilon$

- Definición de derivada: $f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$

- Razón de cambio promedio: $\frac{f(b) - f(a)}{b - a}$

- Ecuación de recta tangente: $y - f(a) = f'(a)(x - a)$

**¡Buena suerte!**