> # <p align = "center">Índice: [[📐ALGEBRA📐]]</p>
> # <p align = "center"> Tema Anterior: [[Unidad 1 - Vectores]]</p>
---
> ## <p align = "center">Matrices</p>
---
### Partes de una matriz

***Matriz de coeficientes***
![[Pasted image 20230720213629.png]]

***Matriz Ampliada***
![[Pasted image 20230720214045.png]]


---
### Resolución con Gauss
#### Operaciones elementales
> - ***Intercambiar una fila con otra:*** $F_{i}\,\leftrightarrow\,F_j$
>- ***Multiplicar una fila por un escalar:*** $K.F_{i}\,$    siendo $K\neq 0$
> - ***Sumar una fila previamente multiplicado con un escalar:***$F_{i}\leftarrow F_{i}+K.Fj$

***Idea: $\begin{Bmatrix}
       1 & 0   \\
       0 & 1  \\
        \end{Bmatrix}$***


 
Ej:

$M = \begin{Bmatrix}
       6 & 2 & \vdots \; 0    \\
       -2 & 5  &  \vdots \;17 \\
        \end{Bmatrix} \to F_{1}. -\frac{1}{6}$


$M = \begin{Bmatrix}
       1 & \frac{1}{3} & \vdots \; 0    \\
       -2 & 5  &  \vdots \;17 \\
        \end{Bmatrix} \to F_2+2.F_1$

$M = \begin{Bmatrix}
       1 & \frac{1}{3} & \vdots \; 0    \\
       0 & \frac{17}{3}  &  \vdots \;17 \\
        \end{Bmatrix} \to  F_2.\frac{3}{17}$

$M = \begin{Bmatrix}
       1 & \frac{1}{3} & \vdots \; 0    \\
       0 & 1 &  \vdots \;3 \\
        \end{Bmatrix} \to  F_1.+\frac{1}{3}.F_2$

$M = \begin{Bmatrix}
       1 & 0 & \vdots \; -1    \\
       0 & 1  &  \vdots \;3 \\
        \end{Bmatrix}$


#### Tips
- ***Para buscar 1 =***  Multiplicar fila por $\frac{1}{a}$
- ***Para buscar 0 =*** Sumar fila del 1 principal por el opuesto.

---
### Tipos de Matrices
- ***Matriz cuadrada (nxn):*** $\begin{pmatrix}2 & 5 & 0  \\ 7 & 0 & 1  \\ 3 & 0 & 1\end{pmatrix}$

- ***Matriz diagonal:*** $\begin{pmatrix}2 & 0 & 0  \\ 0 & 3 & 0  \\ 0 & 0 & 1\end{pmatrix}$

- ***Matriz identidad (I):***
*Se adapta a cualquier matriz para operarla*
 $\begin{pmatrix}1 & 0 & 0  \\ 0 & 1 & 0  \\ 0 & 0 & 1\end{pmatrix}$ 

- ***Matriz triangular superior:*** $\begin{pmatrix}2 & 5 & 1  \\ 0 & 2 & 1  \\ 0 & 0 & 1\end{pmatrix}$

- ***Matriz triangular inferior:*** $\begin{pmatrix}2 & 0 & 0  \\ 7 & 4 & 0  \\ 3 & 2 & 1\end{pmatrix}$

- ***Matriz nula:*** $\begin{pmatrix}0 & 0 & 0  \\ 0 & 0 & 0  \\ 0 & 0 & 0\end{pmatrix}$

- ***Matriz Transpuesta ($[a_{ij}]^T\rightarrow\,a_{ji}$):*** $\begin{pmatrix}1 & 7 & -20 \\ 0 & 4 & 5\end{pmatrix}\rightarrow\,\begin{pmatrix} 1 & 0 \\ 7  & 4 \\ -20 & 5\end{pmatrix}$

---
### Operaciones con matrices
- #### Suma de matrices
	*Deben ser del mismo orden (Tamaño) mxn.*


	**Sumamos cada lugar $a_{1}\, con\, a_{1}...$**

***$$\begin{pmatrix}2 & 4 & 6  \\ 8 & 3 & 2 \end{pmatrix} + \begin{pmatrix}3 & 5 & 8  \\ 7 & 2 & 1 \end{pmatrix} = \begin{pmatrix}5 & 9 & 14  \\ 15 & 5 & 3 \end{pmatrix}$$***

- #### Producto con un escalar
	***$$K.A=k.a_{ij}$$***

$$5\begin{pmatrix}2 & 4 & 6  \\ 8 & 3 & 2 \end{pmatrix} = \begin{pmatrix}10 & 20 & 30  \\ 40 & 15 & 10 \end{pmatrix}$$

- #### Producto matricial
	*Las columnas del primero deben coincidir con las filas del segundo.*
	***$$A.B = C$$***
	$$m_{x}n\, n_{x}l = mxl$$

![[Pasted image 20230721005423.png]]

---
### Rango de una matriz
*Es la mínima cantidad de ecuaciones validas que contiene el sist.*
**Cantidad de filas no nulas**

***$$Rango(a)=2 \begin{cases}A = \begin{pmatrix} 1 & 5 & 0 \\ 0 & 1 & 8 \\ 0 & 0 & 0\end{pmatrix} \end{cases} $$***

---
### Determinante de una matriz
- #### Matriz 2x2
	![[Pasted image 20230721010805.png]]

- #### Matriz 3x3
	![[Pasted image 20230721011559.png]]

---
### Inversa
***$$A^{-1}=Adj(A^T).\frac{1}{det}$$***
*Para sacar al inversa el $Det \neq 0$*

- #### Adjunta
	$A = \begin{pmatrix}4 & 1 & 3 \\ 2 & 1 & 4 \\ 0 & 1 & 2 \end{pmatrix}$
	
	- **1 - Sacar determinante**
		Determianante = -6

	- **2 - Sacar transpuesta**
		$A^{T}= \begin{pmatrix}4 & 2 & 0 \\ 1 & 1 & 1 \\ 3 & 4 & 2\end{pmatrix}$
	- **3 - Sacar adjunta**
		*Tapamos fila uno columna 1 y sacamos determinante, luego fila 1 columna 2, etc.*
		![[Pasted image 20230721144943.png]]
	- **4 - Armamos la adjunta**
		$Adj(A^{T})=\begin{pmatrix}-2 & -1 & 1 \\ 4 & 8 & 10 \\ 2 & 4 & 2\end{pmatrix}$
	- **5 - Le cambiamos los signos**
		 *$\begin{pmatrix}+ & - & + \\ - & + & - \\ + & - & +\end{pmatrix}$*

		$Adj(A^{T})=\begin{pmatrix}-2 & -1 & 1 \\ 4 & 8 & 10 \\ 2 & 4 & 2\end{pmatrix}$
- #### Inversa

	- **6 - Armamos la inversa**
		$A^{-1}= -\frac{1}{6}\begin{pmatrix}-2 & 1 & 1 \\ -4 & 8 & -10 \\ 2 & -4 & 2\end{pmatrix}$
	- **Resultado**
		***$\begin{pmatrix}\frac{2}{6} & -\frac{1}{6} & -\frac{1}{6}  \\ \frac{4}{6} & -\frac{8}{6} & \frac{10}{6} \\ -\frac{2}{6} & \frac{4}{6} & -\frac{2}{6}\end{pmatrix}$***

---
### Ecuaciones matriciales

*Debemos ver por donde multiplicamos la inversa, esto es donde se introduzca la inversa no allá nada a los lados. Ej: $A^{-1}.A.X + B\: o \: B + X.A.A^{-1}$*
*Las matrices deben ser cuadradas y tener inversa*

***$A.X+B=C$***
***$A.X=C - B$***
***$A^{-1}.A.X=A^{-1}(C - B)$***
***$I.X=A^{-1}(C - B)$***
***$X=A^{-1}(C - B)$***


---
> # <p align = "center"> Tema Siguiente: [[Unidad 3 - Teorema de Rouche - Frobenius]]</p>
> # <p align = "center">Índice: [[📐ALGEBRA📐]]</p>