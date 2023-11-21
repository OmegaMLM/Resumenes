> # <p align = "center">Índice: [[✖️ANALISIS MATEMATICO✖️]]</p>
> # <p align = "center"> Tema Anterior: [[Unidad 2 - Limites]]</p>
---
> ## <p align = "center">Derivadas</p>
---
Es la medida de rapidez de cambio de un valor

![[Derivada grafica]]

La recta secante la corta en los dos puntos. La recta tangente solo en uno

$\frac{\Delta_y}{\Delta_{x}}=\frac{y_2-y_{1}}{x_{2}-x_{1}}$

$\lim_{x \to 0} \frac{\Delta_{y}}{\Delta_{x}}=\frac{d_{y}}{d_{x}} \to \text{La recta secante se transforma en una tangente}$

## Propiedades
1. Derivada de una constante es igual a 0 ***$\frac{d}{dx} (C) = 0$***<br><br>
2. Derivada de una constante por una función $y=f(x)$, es la constante por la derivada de una función ***$\frac{d}{dx} (C \cdot f(x)) = C \cdot \frac{d}{dx} f(x)$*** <br><br>
3. La derivada de una función potencial ***$\frac{d}{dx} (x^n) = n \cdot x^{n-1}$***
	EJ: $\frac{d}{dx} (x^3) = 3 \cdot x^2$<br><br>
4. Derivada de una suma de funciones ***$\frac{d}{dx} (f(x) + g(x) + h(x)) = \frac{d}{dx} f(x) + \frac{d}{dx} g(x) + \frac{d}{dx} h(x)$***<br>
	EJ: $\frac{d}{dx} (3x^2 + 2x + 1) = \frac{d}{dx} (3x^2) + \frac{d}{dx} (2x) + \frac{d}{dx} (1) = 6x + 2$<br><br>

## Casos especiales
1. $y = \frac{1}{x} = x^{-1}\to y' = -1x{^{2}}= -\frac{1}{x^2}$<br><br>
2. $y = \sqrt{x} = x{^{\frac{1}{2}}}\to y'=\frac{1}{2}{^{-\frac{1}{2}}}=\frac{1}{2\sqrt{x}}$ 

## Derivada de una función compuesta (Regla de la cadena)

***$y = f[g(x)] \to y´= f(x)g(x)$***

EJ:
	$y = (3x^{2}-4x+2)^{2\to f}=[g(x)]^{2}\to (\text{grado 4})$<br><br>
	**Bajamos el f=2 de la potencia**
	$y'=2g(x).g(x)'=2.(3x^{2}-4x+2).(6x-4)^{\to {\text{derivada de g}}}$
	$y' = 2.(18x^{3}-12x^{2}-24x^{2}+16x+12x-8)$
	$y' = 2.(18x^{3}-36x^{2}+28x-8)$
	$y' =36x^{3}-72x^{2}+56x-16 \to \text{grado 3} \to \text{Minima Expresion Polinomica}$
	*Cuando hacemos una derivada desciende un grado*
	
EJ:
	$y = (x+2x^{3})^{4}$
	$y' = 4.(x+2x^2)^3.(1+2.x^{2})$
	$y' = 4.(x+2x^{3})^{3}.(6x^{2}+1) \to \text{Minima Expresion Factorizada}$

## Derivada de un producto de funciones

***$y = U(x).V(x)$
$y' = U'(x).V(x)+ U(x).V'(x)$***
***La U derivada por V  mas la U por la V derivada***

EJ:
	$f(x) = 3x^2 + 2x$
	$g(x) = 4x - 1$<br><br>
	$h(x) = f(x) \cdot g(x) = (3x^2 + 2x) \cdot (4x - 1)$
	$h'(x) = (3x^2 + 2x)' \cdot (4x - 1) + (3x^2 + 2x) \cdot (4x - 1)'$
	$h′(x)=(6x+2)⋅(4x−1)+(3x2+2x)⋅4$
	$h′(x) = 24x2−6x+8x−2+12x2+8x$
	$h'(x)=36x2+10x−2$

## Derivada de un cociente de funciones
***$h(x) = \frac{U(x)}{V(x)}$***

***$h'(x) = \frac{U'(x) \cdot V(x) - U(x) \cdot V'(x)}{(V(x))^2}$***

***Como el producto solo que dividimos todo por V al cuadrado***

EJ:
	$f(x) = 3x^2 + 2x$
	$g(x) = 4x - 1$<br><br>

$h(x) = (3x^2 + 2x) / (4x - 1)$
$h'(x) = ((6x + 2) * (4x - 1) - (3x^2 + 2x) * 4) / (4x - 1)^2$
$h'(x) = (12x^2 - 6x - 2) / (4x - 1)^2$

## Derivadas logarítmicas
**Aplico logaritmo natural en ambos lados**
$y = e^{cos(x)} \to Ln(y)=Ln(e^ {cos(x)})$<br><br>
**Bajo la función trigonométrica**
$Ln(y)=cos(x)Ln(e)$ *Ln(e) = 1*<br><br>
**Derivo en ambos lados. Paso y para el otro lado**
$\frac{y'}{y}=-sen(x) \to y' =-y.sen(x)$<br><br>
**Remplazo y**
$y' = -e^{cos(x)}.sen(x)$

--- 
> # <p align = "center"> Tema Siguiente: [[]]</p>
> # <p align = "center">Índice: [[✖️ANALISIS MATEMATICO✖️]]</p>