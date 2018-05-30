Toda vez que se efectúa una medición, debemos tener en cuenta la existencia de un _error absoluto_, un _error relativo_ y un _error relativo porcentual_. 

###Error absoluto
También conocido como _**error residual**_ o _**desviación**_, es la diferencia entre el valor más probable y el de cada una de las mediciones realizadas:  

$$
\varepsilon = \overline {x} - x_{i}
$$

!!!Ejemplo

	Tomando los valores del ejemplo anterior, calcularemos el **error absoluto ($\varepsilon$)** para cada medición realizada:

	$\varepsilon_{x_1} = 10,36 - 10,40 = -0,04$ 
	
	$\varepsilon_{x_2} = 10,36 - 10,30 = +0,06$
	
	$\varepsilon_{x_3} = 10,36 - 10,30 = +0,06$
	
	$\varepsilon_{x_4} = 10,36 - 10,30 = +0,06$
	
	$\varepsilon_{x_5} = 10,36 - 10,40 = -0,04$
	
	$\varepsilon_{x_6} = 10,36 - 10,40 = -0,04$
	
	$\varepsilon_{x_7} = 10,36 - 10,40 = -0,04$
	
	$\varepsilon_{x_8} = 10,36 - 10,30 = +0,06$
	
	$\varepsilon_{x_9} = 10,36 - 10,40 = -0,04$
	
	$\varepsilon_{x_{10}} = 10,36 - 10,40 = -0,04$
	
	Como dato curioso, la suma de los _errores abosolutos_ debería ser siempre cero.

#### Valor aproximado
Podemos establecer la **aproximación del resultado** tomando el valor absoluto del **error absoluto máximo** asignándole doble signo ($\pm$) y aplicándolo al **valor probable**:

$$
\overline{x} \pm \varepsilon_{max}
$$

!!!Ejemplo
	En nuestro ejemplo, el valor de la longitud del objeto medido quedará expresada como: 
	
	$$
	10,36 \: mm \pm 0,06 \: mm
	$$
	
	Este resultado implica que, si bien $10,36 \: mm$ es el **valor probable**, existen otros **valores posibles** comprendidos entre: 

	$10,42 \: mm \: (10,36\: mm + 0,06\: mm)$ 

	y 

	$10,30 \: mm \: (10,36\: mm - 0,06\: mm)$


**IMPORTANTE**: cuando se realizan _varias mediciones_, el error absoluto se calcula como se explica más arriba. Sin embargo, cuando se realiza _sólo una medición_ el error absoluto está dado por el instrumento de medida, siendo la menor magnitud que éste es capaz de medir. Por ejemplo, si nuestro instrumento de medición fuese una regla de tipo escolar, el error absoluto sería igual a $\varepsilon = \pm \: 0,1 \: cm$ que es la menor magnitud que se puede medir con dicho instrumento. 

###Error relativo
Es el cociente entre el error absoluto y el valor probable: 

$$
\varepsilon_r = \frac {| \varepsilon |} {\overline {x}}
$$

!!!Ejemplo
	Podemos calcular ahora el **error relativo** tomando el **valor aproximado** obtenido en la sección anterior: 

	$\varepsilon_r = \frac {0,06} {10,36} = 0,0058$

	Es decir que se cometió un error de $0,0058 \: mm$ por unidad del valor medido. 

### Error relativo porcentual
Se trata de otra manera de visualizar el _erorr relativo_ y surge de multiplicar el error relativo por cien: 

$$
\varepsilon_{\%} = \varepsilon_r \cdot 100
$$

!!!Ejemplo
	Tomando el valor del _error relativo_ calculado, tenemos que: 
	
	$\varepsilon_{\%} = 0,0058 \cdot 100$
	
	$\varepsilon_{\%} = 0,58\: %$

$$
\\
$$


## Bibliografía
* MIGUEL, C., _Física_, Buenos Aires, Ed. Troquel, 1975. 
* CASTIGLIONI, R., PERAZZO, O., RELA, A., _Física 1_, Buenos Aires, Ed. Troquel, 1981. 


