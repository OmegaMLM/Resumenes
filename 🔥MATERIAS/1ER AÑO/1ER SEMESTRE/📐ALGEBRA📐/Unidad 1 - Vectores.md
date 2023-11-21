> # <p align = "center">Índice: [[📐ALGEBRA📐]]</p>
---
> ## <p align = "center"> Vectores</p>
---
$$\overrightarrow{A}$$

### Concepto
Es todo segmento orientado determinado por un par ordenado de puntos *O* y **P**.
*O* = Origen
**P** = Extremo del vector
![[Pasted image 20230720132122.png]]

---
### Partes de un vector
*Para obtener AB debemos hacer B-A, es decir punto final menos punto inicial.*
$$\overrightarrow{AB}=\overrightarrow{B}-\overrightarrow{A} = x_{f}-x_{i},\,y_{f}-y_{i}$$

- ***Dirección:*** Dada por la recta que lo contiene o por la paralela de la misma.
- ***Sentido:*** Dada por la orientación (La flecha).
- ***Modulo:*** La longitud del vector.
	**Sacar modulo**
	$$C=\sqrt{a^{2}+b^{2}}$$
	Or
	$$\mid\widehat{AB}\mid\,=\sqrt{({x_{f}-x_{i})}^{2}+{(y_{f}-y_{i})}^2}$$	


![[Pasted image 20230720134425.png]]
---
### Operaciones vectoriales
***Igualdad de vectores:*** Dos vectores son iguales si su modulo es 0 o si tienen misma dirección, modulo y sentido

- #### Suma de vectores
$$\overrightarrow{U}\,+\overrightarrow{V}=(x_{1}+x_{2},\,y_{1}+y_{2})$$
- #### Multiplicación de un vector por un escalar
	***$\mid\alpha\mid$ = Escalar***
	$$\mid\alpha.\overrightarrow{V}\mid = \mid\alpha\mid\,.\overrightarrow{V}=\alpha\,.x, \,\alpha\,.y$$

---
### Combinación Lineal
Los vectores linealmente dependiente se pueden expresar como combinación lineal por lo tanto los linealmente independiente no se puede expresar como combinación lineal.
*Si son linealmente independientes se le puede agregar un tercer vector para intentar expresarlo como combinación lineal.*
Teniendo $\overrightarrow{V}\,y\,\overrightarrow{U}.$
- #### Vectores linealmente dependientes
	$$\frac{x_{1}}{x_{2}}=\frac{y_{1}}{y_{2}}$$
- #### Vectores linealmente independientes
	 $$\frac{x_{1}}{x_{2}}\neq\frac{y_{1}}{y_{2}}$$
	 *Aquí se puede agregar otro vector para expresar como combinación lineal.*
	 EJ: Expresar  $\overrightarrow{W}$ como combinación lineal
	 ***$\overrightarrow{W}=22,8$ | $\overrightarrow{U}=5,1$ | $\overrightarrow{V}=2,4$***
	
	 **1 -Primero revisar si es combinación lineal**
	 $\frac{5}{2}\neq\frac{1}{4}$ son LI
	
	 **2 - Empezamos con la ecuación**
	 $(22,8)=a.(5,1)+b.(2,4)$
	 $(22,8)=(5a,1a)+(2b,4b)$
	
	 **3 - La ecuación quedaría**
	 $(22,8)=5a+2b,\,1a+4b$
	
	 $\begin{cases}5a+2b=22 \\ 1a+4b=8\end{cases}$

	**4 - Despejar una incógnita en una de las dos ecuaciones**
	$a+4b=8$
	$a=8-4b$

	**5 - Remplazar la incógnita en la otra ecuación**
	$5a+22b=22$
	$5(8-4b)+2b=22$
	$40-20b+2b=22$
	$-18b=22-40$
	$-18b=18$
	$b=\frac{-18}{-18}$
	***$b=1$***

	**Despejar b en la otra ecuación**
	$a=8-4b$
	$a=8-b(1)$
	***$a=4$***

	***Son distintos por lo tanto son LI $\begin{cases}a=4 \\ b=1\end{cases}$***

---
### Sistema de Ecuaciones Lineales
![[Pasted image 20230720155150.png]]

---
> # <p align = "center"> Tema Siguiente: [[Unidad 2 - Matrices]]</p>
> # <p align = "center">Índice: [[📐ALGEBRA📐]]</p>