> # <p align = "center">Índice: [[✖️ANALISIS MATEMATICO✖️]]</p>
> # <p align = "center"> Tema Anterior: [[Unidad 0 - Casos de Factoreo y Casos de Racionalización]]</p>
---
> ## <p align = "center">Funciones</p>
---
### Clasificación de funciones
- ***Funciones Inyectivas:***  Cuando al hacer líneas horizontales, corta una sola vez a la función.
- ***Funciones Sobreyectivas:*** Al hacer líneas horizontales, en todas corta a la función.
- ***Función Biyectiva:*** Cuando es inyectiva y sobreyectiva.


---

### Función Identidad
$$y=x$$
![[Pasted image 20230817133145.png]]

---
### Función Lineal
$$y=ax+b$$
- ***$a$ = Pendiente***
- ***$b$ = Ordenada al origen***

#### Formas dadas
1. $y = ax+b$
	![[Pasted image 20230817134317.png]]<br><br>

2. $a$ = Pendiente y $P1(x_{1},y_{1})$
	- $y = m(x -x_{1}) + y_{1}$
	 ![[Pasted image 20230817135749.png]]

	Ej: 
		$y=\frac{3}{2}[x-(+1)]+(-2)$
		$y=\frac{3}{2}x-\frac{3}{2} -2$
		$y=\frac{3}{2}x-\frac{7}{2}$<br><br>


3. Dos puntos: $P(x_1; y_1) y Q(x_2; y_2)$
	$a =\frac{y_2-y_1}{x_2-x_1}$
	$b = y_1 - a*x_1$

4. Un punto, ax + b y una condición
	#### Paralela
	**Identificamos $a$**<br>
	**Utilizamos la formula**
	$y-y_1=a(x-x_1)$<br>
	**Despejamos y**
	$y =a(x-x_1)+y_1$<br><br>
	#### Perpendicular
	**Identificamos $a$ y la invertimos**
	$a_perpendicular = -\frac{1}{a}$<br>
	**Utilizamos la formula**
	$y-y_1=-\frac{1}{a}(x-x_1)$<br>
	**Despejamos y**
		$y =-\frac{1}{a}(x-x_1)+y_1$

#### Calcular la intersección
**Igualamos las dos funciones**
$ax_1+b=ax_2+b$<br>
**Dejamos las x de un solo lado y eso nos da $x_i$**
$ax_1-ax_{2}=b-b \rightarrow x_i$

**Remplazamos $x_i$ en alguna de las funciones  y nos da $y_i$**
$y_i=ax_i+b$

#### Sacar inversa
*Solo existe si es biyectiva*
**Intercambiamos x por y. Luego despejamos y**
$y = ax + b \rightarrow x = ay+b$
$x-b =ay$
$\frac{x-b}{a}= y$
$\frac{1}{a}x-b$

---

### Función cuadrática

> $$y = ax{^2}+bx+c$$

*Puntos Notables*
- $a>0$  ***Ramas hacia arriba.***  $a<0$ ***Ramas hacia abajo***
- $\mathcal{Signo~ }b =\mathcal{Signo~ } a$ ***Desplazamiento a la izquierda.*** $\mathcal{Signo~ }b \neq\mathcal{Signo~ } a$ ***Desplazamiento a la izquierda***
- $c$ ***Ordenada al origen***

**Para sacar las raíces se utiliza Bhaskara**
$\begin{equation} x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} \end{equation}$

**Sacar El vértice en X**
$\frac{-b}{2a}$

---
### Función Parabólica
> $y= a_n x^n + a_{n-1} x^{n-1} + \ldots + a_2 x^2 + a_1 x + a_0$

**Debemos probar hasta sacar una raíz con prueba error y luego aplicar Ruffini, hasta sacar poder lograr Bhaskara**


---
### Funciones Exponenciales
> $$y = a{^2}$$

*Son inversas a las logarítmicas por lo tanto también simétricas. Siempre la cortan en el eje Y en el 1*

*Puntos Notables:*
- Si $a > 1$ la funciones ***creciente***, es decir, la rama sube en el primer cuadrante. Si $0<a<1$ la función es ***decreciente***, la rama sube en el segundo cuadrante.
- $a$ ***no puede ser ni negativa ni 1***
- Dende de que tengamos junto a la base puede cambiar la asíntota

$f(x)=3{^x}$

![[Pasted image 20231001194042.png]]
Dom: $\mathbb{R}\quad (-\infty,\infty)$
Img: $(0,\infty)$


*Transformaciones*
- **Cambiar el signo del expontente:** Se refleja respecto al eje Y. No cambia ni el dominio ni el rango.
![[Pasted image 20231001194537.png]]

- **Multiplicar el exponente:** Cambia la inclinación. No cambia ni el dominio ni el rango.
![[Pasted image 20231001195029.png]]

- **Sumar o restar del exponente:** Se corre todo a la izquierda o derecha. Si el signo es positivo se mueve todo a la izquierda. Si es negativo a la derecha. No cambia ni el domingo ni el rango.
![[Pasted image 20231001195918.png]]

- **Cambiar el signo de la base:** Se refleja respecto al eje X. Cambia el rango por el contrario.
- **Suma o resta de la base:** Se mueve todo hacia abajo o arriba. Si es positivo es hacia arriba, si es negativo es hacia abajo. Por lo tanto se mueve la asíntota, es decir cambia el rango.
![[Pasted image 20231001200839.png]]

---

### Funciones Homografías
*La parte de arriba es m(x) y la de abajo es d(x)*

> $$y = \frac{ax +b}{cx +d}$$

$y = \frac{2x + 3}{x-1}$

**1 - Sacar la raíz**
**Despejamos x en m(x)**<br>
$xr = 2x +3$
$xr = -\frac{3}{2}$

**2 - Sacamos la ordenada al origen**
**Remplazamos x por 0 en tanto en m(x) como d(x)**<br>
$yr = \frac{b}{d}$
$yr = \frac{3}{-1}$

**3 - Sacamos asíntota vertical**
**Despejamos x en d(x)**
$AV =x - 1=0$
$AV = x = 1$

**4 - Sacamos asíntota horizontal**
**Dividimos a/c**
$AH = \frac{2}{1} = 2$
![[Pasted image 20231001220948.png]]

---
> # <p align = "center"> Tema Siguiente: [[Unidad 2 - Limites]]</p>
> # <p align = "center">Índice: [[✖️ANALISIS MATEMATICO✖️]]</p>