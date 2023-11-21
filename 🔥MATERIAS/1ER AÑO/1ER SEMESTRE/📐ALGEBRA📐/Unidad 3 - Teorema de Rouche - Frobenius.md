> # <p align = "center">Índice: [[📐ALGEBRA📐]]</p>
> # <p align = "center"> Tema Anterior: [[Unidad 2 - Matrices]]</p>
---
> ## <p align = "center">Teorema de Rouche-Frobenius</p>
---
*r = Rango
n = Numero de incógnitas*

> ***$r (A)=r '(A)=n\rightarrow\, SCD = 1\, Solucion$***
***$r (A)=r '(A)\neq n\rightarrow\, SCI = \infty\, Solucion$***
***$r (A)\neq r '(A)\rightarrow\, SI = Sin\, Solucion$***

- **1 - Sacamos el rango de A**
	*$\text{Si el det}\, \neq 0\; |\;  R=Filas$
	$\text{Si el det}\, = 0\; |\;  R=Filas - 1$*

- **2 - Sacamos el rango de 'A**
	*Elegimos una columna y le cambiamos por la columna ampliada. Lo hacemos hasta que de distinto de 0*

EJ:
$\begin{cases}3x + 2x + z = 4 \\ 8x - y + 3z = 4\\ x + y + z = 0 \end{cases}$
$M = \begin{pmatrix}3 & 2 & 1 \vdots & 4 \\ 8 & 1 & 3 \vdots & 4  \\ 1 & 1 & 1 \vdots & 0\end{pmatrix}$

$det(M) = \begin{pmatrix}3 & 2 & 1 \\ 8 & 1 & 3 \\ 1 & 1 & 1\end{pmatrix} =- 9 =R(3)$

$det(M') = \begin{pmatrix}3 & 2 & 4 \\ 8 & 1 & 4 \\ 1 & 1 & 0 \end{pmatrix} =4 =R(3)$

***$R(M) = R(M') = n(3) = SCD$***

---
> # <p align = "center">Índice: [[📐ALGEBRA📐]]</p>