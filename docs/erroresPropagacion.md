Antes de averiguar en qué consiste la propagación de errores conviene aclarar que existen dos **tipos de mediciones**: 

1. **Directas**

2. **Indirectas**

Las **mediciones directas** son aquellas que nos permiten obtener un valor cuando realizamos la lectura del instrumento de medición. Por ejemplo, al medir una longitud con una regla, el peso con una balanza, etc. 

En cambio, las **mediciones indirectas** son aquellas que resultan de diversos tipos de cálculos que involucran las _mediciones directas_. Por ejemplo, cuando a partir del valor de los lados de una figura geométrica se calcula su perímetro o superficie. En estos casos se debe tener en cuenta los errores de cada medición directa a la hora de realizar los cálculos. Estas cuestiones están contempladas por la llamada **Ley de propagación de errores**. 

###Error absoluto de una suma
El **error absoluto máximo** está dado por la **suma de los errores absolutos máximos** de los números que intervienen en la operación. 

$$
\varepsilon_{max} = \varepsilon_{x_1} + \varepsilon_{x_2}
$$

Para comprenderlo mejor, lo ilustraremos con un ejemplo. 

!!!Ejemplo
	Los valores más probables de dos longitudes medidas son: 
	
	$x_1 = 10,32 \:cm \pm \: 0,04 \: cm$
	
	$x_2 = 6,18 \:cm \pm \: 0,02 \: cm$
	
	Y se desea sumar ambas longitudes. El **valor probable** será:
	
	$\overline{x} = 10,32\:cm + 6,18\:cm = 16,50\:cm$
	
	El **valor máximo posible** (sumando los valores máximos posibles): 
	
	$x_{max} = 10,36\:cm + 6,20\:cm = 16,56\:cm$

	El **valor mínimo posible** (sumando los valores mínimos posibles): 
	
	$x_{min} = 10,28\:cm + 6,16\:cm = 16,44\:cm$ 

	Calculamos el error absoluto máximo: 
	
	$\varepsilon = \overline{x} - x_{max}$
	
	$\varepsilon = 16,50 \: cm - 16,56 \: cm = -0,06 \: cm$

	Y el error absoluto mínimo: 
	
	$\varepsilon_{min} = \overline{x} - x_{min}$

	$\varepsilon_{min} = 16,50 \: cm - 16,44 \: cm = +0,06 \: cm$
	
	Por tanto, el **error absoluto máximo de la suma** será 

	$\varepsilon = \pm 0,06\:cm$

	Finalmente, $\overline{x} = 16,50\:cm \pm 0,06\:cm$, lo que corrobora que **el error absoluto máximo de una suma, es igual a la suma de los errores absolutos máximos de los sumandos**

###Error absoluto de una diferencia
Al igual que la suma, el **error absoluto máximo de una resta** está dado por la **suma de los errores absolutos máximos** de los números que intervienen en la operación. 

$$
\varepsilon_{max} = \varepsilon_{x_1} + \varepsilon_{x_2}
$$

!!!Ejemplo
	Tomando los mismos valores que en ejemplo anterior: 
	
	$x_1 = 10,32 \:cm \pm \: 0,04 \: cm$
	
	$x_2 = 6,18 \:cm \pm \: 0,02 \: cm$
	
	Abreviaremos los cálculos con el fin de demostrar que llegaremos, de todos modos, al resultado esperado según la definición. 

	Calculamos el **valor probable**:
	
	$\overline{x} = 10,32\:cm - 6,18\:cm = 4,14\:cm$
	
	Siendo el valor del **error absoluto máximo de la resta** la **suma de los errores absolutos máximos**: 

	$\varepsilon = \varepsilon_{x_1} + \varepsilon_{x_2}$ 

	$\varepsilon = 0,04\:cm + 0,02\:cm = \pm 0,06\:cm$
	
	Por último, el valor esperado será: 
	
	$\overline{x} = 4,14\:cm \pm 0,06\:cm$


### Error absoluto de un producto
El cálculo del **error absoluto máximo en una multiplicación** está dado por la siguiente ecuación: 

$$
\varepsilon_{max} = {x_1} \cdot \varepsilon_{x_2} + {x_2} \cdot \varepsilon_{x_1}
$$

Donde:
* ${x_1}$ y ${x_2}$ son dos **mediciones** realizadas 
* $\varepsilon_{x_1}$ y $\varepsilon_{x_2}$ sus **errores absolutos máximos**, respectivamente. 

!!!Ejemplo
	Supongamos que debemos calcular la superficie de un rectángulo de lados: 
	
	${x_1}= 10,02 \: cm \pm 0,04 \: cm$
	
	${x_2}= 5,04 \: cm \pm 0,02 \: cm$

	Entonces, la superficie probable ($\overline{x}$) será:
	
	$Superficie =  {x_1} \cdot  {x_2} = 10,32 \: cm \cdot 6,18 \: cm$
	
	$Superficie = 50,50 \: cm$
	
	Luego, el error absoluto máximo: 
	
	$\varepsilon = 10,02\: cm \cdot 0,02\: cm + 5,04\: cm \cdot 0,04\: cm$
	
	$\varepsilon = \pm 0,40\: cm$
	
	Y el valor de la superficie correctamente expresada:
	
	$Superficie = 50,50 \: cm\pm 0,40\: cm$

### Error absoluto de un cociente

Cuando dos mediciones participan de una división, el **error absoluto máximo de un cociente** se calcula multiplicando el error del dividendo por el divisor mas el error del divisor por el dividendo, todo divido por el divisor al cuadrado: 

```
$$
Suponiendo \: que \hspace{0.7cm} R = \frac{x_1}{x_2} \hspace{0.7cm} entonces, \hspace{0.7cm} \varepsilon_{max} = \frac { \varepsilon_{x_1} \cdot {x_2} + \varepsilon_{x_2} \cdot {x_1}  } { {x_2}^2 }
$$
```

!!!Ejemplo
	Dados los siguientes valores de peso (P) y volumen (V): 
	
	$P = 1206\:g \pm 4\:g$
	
	$V = 508\:cm^3 \pm 2\:cm^3$
	
	Calculamos el peso específico del cuerpo, según: 
	
	$\gamma = \frac {P}{V}$

	Entonces: 
	
	$\gamma = \frac {1206\:g}{508\:cm^3} = 2,37402$

	Calculamos el **error absoluto máximo del cociente**: 
	
	$$
	\varepsilon = \frac { 4 \cdot 508   + 2 \cdot 1206 } {{508}^2} = 0,017221
	$$
	
	Entonces, el valor del peso específico (redondeando convenientemente los valores) es:
	
	$\gamma = 2,374 \frac{g}{cm^3} \pm 0,017 \frac{g}{cm^3}$

### Error relativo de un producto
El **error relativo de un producto**, está dado aproximadamente por la **suma de los errores relativos de los factores**: 

$$
\varepsilon_{r_{producto}}=\varepsilon_{r_{$1}} + \varepsilon_{r_{2}}
$$

!!!Ejemplo
	Tomando los datos anteriores, para el cálculo de la superficie de un rectángulo: 

	${x_1}= 10,02 \: cm \pm 0,04 \: cm$
	
	${x_2}= 5,04 \: cm \pm 0,02 \: cm$
	
	Calculamos los **errores relativos** de los lados del rectángulo: 

	$\varepsilon_{x_1}= \frac {0,04}{10,02}= 0,003992$
	
	$\varepsilon_{x_2}= \frac {0,02}{5,04}= 0,003968$
	
	Entonces, el **error relativo del producto** será:
	
	$\varepsilon_{r_{producto}}= 0,003992 + 0,003968$
	
	$\varepsilon_{r_{producto}}= 0,0080$

### Error relativo de un cociente
Análogamente al cálculo del error relativo de un producto, el **error relativo de un cociente** está dado por la **suma de los errores relativos** del dividendo y del divisor:

$$
\varepsilon_{r_{cociente}}=\varepsilon_{r_{dividendo}} + \varepsilon_{r_{divisor}}
$$

!!!Ejemplo
	Tomando los valores anteriores de peso (P) y volumen (V): 

	$P = 1206\:g \pm 4\:g$

	$V = 508\:cm^3 \pm 2\:cm^3$
	
	Calculamos el $\varepsilon_r$ de cada uno de ellos: 

	$\varepsilon_{r_{P}}= \frac {4}{1206}= 0,003317$

	$\varepsilon_{r_{V}}= \frac {2}{508}= 0,003937$
	
	Entonces, el **error relativo del cociente** será:

	$\varepsilon_{r_{cociente}}=0,003317 + 0,003937$

	$\varepsilon_{r_{cociente}}=0,0073$