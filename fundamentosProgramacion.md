# FUNDAMENTOS DE PROGRAMACÓN CON ALEJANDRO

**1ro aprenderemos unos conceptos.**

Una **computadora** es un procesador de datos y sistemas de procesamiento de la información.

Un **sistema** es un conjunto de componentes conectados e interactivos que tienen un propósito y una unidad total.

Un **sistema de procesamiento** es el que se encarga de transformar los datos brutos (es decir desordenados) en información organizada, significativa y útil.

El **hardware** es la parte tangible de una computadora ( con tangible se refiere a que que se puede tocar) es todo lo físico de una computadora.

El **software** es la parte lógica, es lo intangible de una computadora, es el conjunto de programas que controlan el hardware.

EL **dato** es una representación simbólica (números, caracteres, dibujos, etc..), un atributo o característica de una entidad. Los datos describen hechos empíricos, sucesos y entidades reales. Un dato puede ser un simple caracter, tal como "a", un número, y dibujo, etc.

En **informática** un dato es el que describe los objetos con los cuales opera una computadora, extisten dos tipos de datos:

- Simples (Sin estructuras):

    - Numéricos (Enteros, reales)
    - Logicos (Bolean)
    - Caracter (Char, string)

- Compuestos (Estructurados):
    - Registros
    - Arreglos (Vectores, Matrices)
    - Archivos

La **Información** de conjunto de datos.

## 1. Capitulo I - Informacion y procesamiento de la información
## 1.1 Concepto
Es la **entrada de datos (input)** a la computadora para que luego sea **procesada** y al final se devuelva un resultado como **salida (output)**.

## 1.2 Algoritmo
Es un método que sirve para resolver problemas, el algoritmo sigue una secuencia de pasos ordenados y es finito, es decir tiene un inicio y un final.

**Características de un algoritmo**
- Tiene que ser preciso.
- Tiene que estar bien definido.
- Tiene que ser finito.
- Un algoritmo debe describir: La Entrada, Proceso y Salida.

**Tipos de algoritmos:**

**Cualitativos**

Son aquellos en los que se describen usando sólo palabras.

**Cuatnitativos**

Son aquellos en los que se utilizan cálculos numéricos para definir los pasos del proceso.

**Lenguajes algorítmicos**

Es una serie de símbolos y reglas que se utilizan para describir de manera explícita un algoritmo.

- Existen los **Gráficos** : Es la representación gráfica de las operaciones que realiza un codigo. Diagramas de Flujo, diagramas N-S

- Existen los **No Gráficos** : Representa en forma descriptiva las operaciones que debe realizar un algoritmo. Pseudocódigo.

**Programa**

Es un conjunto de instrucciones escritas en un lenguaje de programación y que ejecutada secuencialmente resuelven un problema específico.

## 1.3 Lenguaje de programación

Es un conjunto de símbolos y reglas semánticas y sintácticas que definen su estructura y el significado de sus elementos y expresiones, es utilizado para controlar el comportamiento físico y lógico de un computador, es decir sirve para crear programas.

## Tipos de lenguaje de programación

- Según su Abstracción (Lenguaje de Máquina).
- Según su Ejecución (Compilación e Interpretado).
- Según su Paradigma (Algorítmico o imperativo, Orientado a Objetos).

## 1.4 Metodologías para la solución de problemas por medio de computadora.

- Analizar el problema (1ro definimos el problema, analizamos el problema, los datos de entrada, cual es la información que desea producir, los datos y formulas que se necesita en el programa).

- Diseñar el algoritmo (Debe tener un punto particular de Inicio, debe ser preciso indicando el orden de realización de cada paso, debe ser definido, no debe permitir dobles interpretaciones, debe ser general, debe ser finito en tamaño y tiempo de ejecución es decir debe tener un final).

- Traducir el algoritmo a un lenguaje de programación (Codificar en un lenguaje de programación que se necesite).
- Depurar el programa (Depuración es corregir errores).

- Documentación (Es la guía o documentación escrita en sus variadas formas, ya sea en enunciados, procedimientos, dibujos o diagramas).

    Existen tres tipos de documentación:
    
    - Documentación interna (Poner comentarios al programar indicando para qué funciona tal código, esto obligatorio porque es buena práctica).

    - Documentación externa (Hacer un documento aparte donde va escrito la descripción del problema, el autor del programa, algoritmos, diccionario de datos, código fuente).
    
    - Manual de usuario (Solo hacer un manual para el usuario que sólo se le entrega el programa y no nesecita la documentación)

- Mantenimiento (Se da mantenimiento cuando se necesite algunos cambios en el programa para que siga trabajando de manera correcta, para poder realizar este trabajo se requiere de una buena documentación ya sea documentación interna o externa).

## 2. Capitulo II Entidades Primitivas.

## 2.1 Descargar e Instalar PSeInt de [Aquí](http://pseint.sourceforge.net/?page=descargas.php), para plasmar nuestros algoritmos.

Si abrimos Pseint por 1ra vez hacer lo siguiente -> Perfiles precargados -> Seleccionar el Lenguaje Estricto -> Aceptar

## 2.2 Identificadores (Constantes y Variables).

¿Qué son los identificadores?

 Representan los datos de un programa, un identificador es una secuencia de caracteres que nos permite almacenar informacion en determinada posición de memoria.

 **Reglas para crear un identificador**

- Debe comenzar con una letra del abecedario y no debe tener espacios.
- Se puede utilizar Guiones bajos para dividir palabras.
- El identificador no puede iniciar con un número.

### Constante

Es un dato numéricon o alfanumérico que no cambia durante la ejecución del programa, ejemplo: El valor del nro PI.

### Variables

Es un espacio en la memoria de la computadora que permite almacenar temporalmente un dato durante la ejecución del proceso, puede cambiar el valor durante la ejecución del programa.

## Clasificación de las variables

- Por su contenido
    - Numéricos
    - Lógicos (Que sólo devuelve verdadero o falso)
    - Alfanuméricos (Strings)
- Por su uso
    - De trabajo
    - Contadores
    - Acumuludores

## 2.3 Tipos de Datos

Hacen referencia al tipo de información que puede almacenar una variable. 

Ejemplo:

**Entero** numero1 = 10;

**Real** numero2 = 22,19;

**Caracter**  letra = a;

**Logico** misterio = verdadero;
<br><br>

**Extisten dos tipos de datos:**
- Simples (Sin estructuras):

    - Numéricos (Enteros, reales)
    - Logicos (Bolean)
    - Caracter (Char, string)

- Compuestos (Estructurados, son definido por el usuario):
    - Simples o estáticos
        - Registros
        - Arreglos (Vectores, Matrices)
        - Archivos
        - Conjuntos
        - Cadenas de caracter (string)
    - Compuestos o dinámicos
        - Punteros
        - Listas (pilas, colas)
        - Listas enlazadas
        - Árboles
        - Grafos

## 2.4 Operación de asignación

Consiste en atribuir un valor a una variable. 

Ejemplo:

num = 10

**Se la realiza en 2 fases:**

- Se evalua la expresión de la parte derecha obetiéndose un único valor.
    
- Se asigna ese valor a la variable de la parte izquierda sustituyéndose el valor que tenía antes.


## ¿Qué debemos tener en cuenta?
- En la parte izquierda sólo debe ir una variable.

- La variable a la que se le asigna un valor pierde su valor anterior, es decir se reemplaza.

- La variable no se le puede asignar un valor que no sea de su mismo tipo de dato.

**Usos para PseInt:**
- Cuando usamos pseint debemos agregrar un ";" en cada final de expresión del pseudocódigo.

- Para escribir comentarios empezamos escribiendo "//".

- Para asignar valor a las variables se realiza con "<-"

    ejemplo: numa <- 10;


Ejemplo de pseudocódigo en PSeInt hasta aquí:

    // Operación de Asignación

    Proceso principal

	Definir numero1 como entero; // La variable numero1 es entera
	Definir numero2 como real;
	Definir letra Como Caracter;
	Definir misterio Como Logico;
	Definir palabra como cadena;
	
	numero1 <- 10;
	numero2 <- 20.32;
	letra <- 'a';
	misterio <- Falso;
	palabra <- "hola";
	
    FinProceso

## 2.5 Entrada y Salida de Información 

## Entrada de Información: 

Las operaciones de entrada permiten leer determinados valores y asisgnarlos a las determinadas variables. La entrada se conoce como LEER

## Salida de información:

Son diferente mensajes que se le envia al ususario ya sea para pedir un valor o también para mostrar un resultado. La salida se conoce como ESCRIBIR.

Ejemplo:

    Proceso principal
	Definir num como entero; // Asignamos valor a la variable
	
	Escribir "Digite un valor numérico "; // Salida de información con "Escribir"
	Leer num; // Entrada de información con "Escribir"
	
	Escribir "El número es: " , num; // Salida de información con "Escribir"
    FinProceso

**Para ejecutar el programa en Pseint le damos click en el botón "Ejecutar"**

## 2.6 Operadores y Operandos
## Operadores:

Los operadores nos permieten manipular los diferentes valores que tenemos.

## Tipos de valores:

- Aritméticos
- Relacionales
- Lógicos

**Operadores Aritméticos**

Permiten la realización de operaciones matemáticas con los valores (Variables y Constantes).

Pueden ser utilizados con tipos de datos como enteros, reales. Si ambos son enteros el resultado es entero y si uno es real el resultado es real.

![Ejemplo de algunos operadores aritméticos:](https://danielaneyoyc.files.wordpress.com/2018/08/python-operadoresaritmeticos_thumb2.png)

**Prioridades de los operadores aritméticcos**

- Todas las expresiones dentro de los paréntesis se resuelven primero.

- Dentro de una misma expresión los operadores se evaluan en el siguiente orden:

    - 1 Exponenciación
    - 2 Multiplicación, división y módulo
    - 3 Suma y resta

**Ejemplo en pseint:**

    Proceso cristian
	Definir resultado, num1, num2 Como Entero;
	
	Escribir "Dame el 1er número";
	Leer num1;
	
	Escribir "Dame el 2do número";
	Leer num2;
	
	resultado <- num1 + num2;
	Escribir "El resultado es",resultado;
    FinProceso

## Operadores Relacionales

Se utilizan para establecer una relación entre 2 valores.

Compara estos valores entre sí y esta comparión produce un resultado de certeza o falsedad (verdadero o falso).

Compara valores que sean sólo del mismos tipo de dato.

Tienen el mismo nivel de prioridad en su evalucaión.

Tinen menor prioridad que los operadores aritméticos.

![Ejemplo de algunos operadores relacionales:](https://www.maquinasvirtuales.eu/ipsoapoo/2020/12/python-aprendiendo-desde-cero-vi-operadores-3.png)

Ejemplo en pseint:

    Proceso cristian
	Definir num1, num2 Como Entero;
	Definir resultado Como Logico;
	
	Escribir "Dame el 1er número";
	Leer num1;
	
	Escribir "Dame el 2do número";
	Leer num2;
	
	resultado <- num1 <> num2;
	Escribir "El resultado es: ",resultado;
    FinProceso

## Operadore Lógicos

Estos valores se utilizan para establecer relaciones entre valores lógicos.

Pueden ser resultado de una expresión relacional.

![En pseint son los siguientes que se muestran en la parte de Lógicos:](https://miguelpa2454.files.wordpress.com/2016/09/7c8cb-operadores.png?w=640&h=635)



Operador AND : Es una multiplicación lógica, ambos valores deben ser verdaderos para que el resultado sea verdadero.
Operador OR : Es una suma lógica, basta que un valor sea verdadero para ser verdadero.
Operación de nagación: Todo operador que se niegue sera lo opuesto, es decir si niego al vardadero se hace falso y niego al falso se hace verdaderos.

![Así se muestra en la tabla de la verdad](https://i0.wp.com/dcodingames.com/wp-content/uploads/2016/05/tablasopbooleanos-fw.png?w=567&ssl=1)


Prioridad de los valores lógicos

1. Primero viene el NOT
2. Luego viene el AND
3. Luego viene el OR


## Prioridad de todos los operadores en general

1. ()
2. ^
3. *, /, mod, NOT
4. +, -, AND
5. >, <, =, <=, >=, <>, OR

**Pequeño ejemplo en Pseint:**

    Proceso cristian
	    Definir a, b, c Como Entero;
	    Definir resultado Como Logico;
	    a<-10;
	    b<-10;
	    c<-10;
	
	    resultado <- ((a<b) Y (b<c)) ;
	    Escribir resultado;
    FinProceso

## 2.7 Funciones Internas

Son funciones matemáticas y trigonométricas diferentes a las operaciones básicas pero que se incorporan al lenguaje y se consideran estándar. Depende de qué lenguaje se utiliza, normalmente se encuentran en las librerias matemáticas del lenguaje de programación.

Aquí un pequeño ejemplo de las funciones internas que trae PSeInt:

//FUNCIONES MATEMATICAS

    Proceso pricipal
	    definir num1, resultados Como Real;
	
	    Escribir "Digite un nmr: ";
	    leer num1;
	    resultados <- azar(num1);
	    Escribir "el resultado es : ", resultados;
    FinProceso


## 2.8 Ejercicios de Todo lo aprendido en este punto:

Ejercicio 1

Escribir la sgte expresión en forma de expresión algorítmica

-b + raiz(b^2 - 4ac) / 2a

Resultado en PSeint:

    //Ejercicio 1
    Proceso pricipal
	    definir a, b, c, resultados Como Real;
	
	    Escribir "Digite el valor A: ";
	    leer a;
	
	    Escribir "Digite el valor A: ";
	    leer b;
	
	    Escribir "Digite el valor A: ";
	    leer c;
	
	    resultados <- (-b + raiz(b^2 - 4*a*c))/(2*a);
	    Escribir "el resultado es : ", resultados;
    FinProceso

Ejercicio 2 con los 3 tipos de operadores

Determinar la solución lógica de la sgte operación:

    //Ejercicio 2

    //     ((3+5*8)<3 y ((-6/3*4)+2<2)) o (a>b)

    Proceso pricipal
	    definir a, b Como real;
	    definir resultados Como Logico;
	
	    Escribir "Digite el valor A: ";
	    leer a;
	
	    Escribir "Digite el valor b: ";
	    leer b;
	
	    resultados <- ((3+5*8)<3 y ((-6/3*4)+2<2) o a>b);
	    Escribir "el resultado es : ", resultados;
    FinProceso

Ejercicio 3 

    //Ejercicio 3

    //     Intercamiar el valor de 2 variables

    Proceso pricipal
	    definir a, b, aux Como real;
	
	    Escribir "Digite el valor A: ";
	    leer a;
    
    	Escribir "Digite el valor b: ";
	    leer b;
	
    	aux<-a;
	    a<-b;
	    b<-aux;
	
	    Escribir "el resultado es : a = ", a ," b = ", b;
  
    FinProceso
## 3 Capítulo III Representación de Algorítmos

## 3.1 Diagrama de Flujos

Es la representación gráfica de un algorítmo, es la representación detallada en forma gráfica de cómo deben realizarse los pasos de la computadora para producir resultados.

Esta representación gráfica se dá cuando un conjunto de símbolos (representan los procesos que hace la computadora) se relacionan entre sí mediante líneas que indican el orden que deben ejecutarse.

![Ejemplo de diagrama de Flujo](data:image/png;base64,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)

## 3.2 Diragrama Estructurado N-S (Nassi-Schneiderman)

También conocido como diagrama chapín, es como un digrama de flujo en el que se omiten las flechas y las cajas son contiguas.

![Aquí un ejemplo de N-S](data:image/png;base64,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)

## 3.3 Pseudocódigo

Es una mezcla de un lenguaje de programación y español que se amplia dentro de la programación estructurada para realizar el diseño de un programa.

Es la representación narrativa de los pasos que debe seguir un algoritmo para dar solución a un problema determinado. El pseudocódigo se utiliza palabras puntauales que indicar el proceso a realizar.

Ejemplo de pseudocódigo

	Proceso programa1
		//
		definir a,b,resultado Como Entero;
		a <- 10;
		Escribir "digite un nro: ";
		Leer b;
	
		resultado <- a+b;
	
		Escribir "el resultado es: ",resultado;
	FinProceso

## 4. Capítulo 	VI Estructuras Secuenciales

Es aquella en la que una acción sigue a otra en secuencia. 

Las tareas se suceden de tal modo que la salida de una es la entrada de la siguiente y así sucesivamente hasta llegar al final del proceso.

La estructura secuencial se representa de la siguiente forma:

	Inicio
		acción1
		acción2
		acción3
	Final

Ejercicio 1:

	Proceso programa1
		//Calcular la cantidad de sgdos que estan incluidos en el nro de horas
		//  minutos y sgdos ingresados por el usuario
		Definir h,m,s, segxmin, segxhora Como Entero;
		segxhora<-3600;
		segxmin<-60;
		Escribir "Dame las horas: ";
		leer h;
		Escribir "Dame los mntos: ";
		leer m;
		Escribir "Dame las sgdos: ";
		leer s;
	
		h<-h*segxhora;
		m<-m*segxmin;
	
		Escribir "la cantidad de segundos es: ", h+m+s;
	
	FinProceso

Ejercicio 2

	Proceso programa1
		// 	Hacer un programa para ingresar el radio de un círculo y se reporte su área y la longitud de la circunferencia
		// área = pi * r^2
		// longitud = 2 * pi * r
		Definir r, area, long Como real;
		
		Escribir "Dame el radio: ";
		leer r;
		area <- pi * r^2;
		long <- 2*pi*r;
		
		Escribir "el área es: ",area;
		Escribir "La longitud es: ", long;
	
	FinProceso

Ejercicio 3

Ejercicio 4

	Proceso programa1
		// Un maestro prepara 3  cuestionarios para una evalución final A, B, C. Se sabe que se tarda 5min en revisar el A 
		// 8 min en el B y 6 en el C. La cantidad de exámenes de cada tipo entra por por teclado.	
		// ¿Cuántas horas y cuántos minutos se tardará en revisar los exámenes?
		Definir a,b,c,contador Como Real;
		Definir minA,minB,minC,total_min Como Real;
		Escribir 'Dame la cantidad de examenes A: ';
		Leer a;
		Escribir 'Dame la cantidad de examenes B: ';
		Leer b;
		Escribir 'Dame la cantidad de examenes C: ';
		Leer c;
		//inicializamos variables
		contador<-0;
		minA<-5;
		minB<-8;
		minC<-6;
		
		//Calculamos el tiempo en mntos que tomará en revisar cada tipo de cuestionario
		minA <- minA*a;
		minB <- minB*b;
		minC <- minC*c;
		
		//Calculamos la suma total de los minutos que tomará
		total_min <- minA+minB+minC;
		
		//Calculamos la cantidad de horas con un contador y el restante del total de minutos
		Mientras total_min>=60 Hacer
			contador <- contador+1;
			total_min <- total_min-60;
		FinMientras
		Escribir "el tiempo que tardará es de: ", contador,"hrs. con ",total_min," minutos.";
	FinProceso

Ejercicio 5

	// Una tienda ofrece descuento del 15% sobre el total de la compra y un cliente desea saber cuánto deberá pagar
	// finalmente por su compra
	Proceso estructura_secuenciales
		Definir desc, precio, precioFinal Como Real;
		Escribir "Digite el monto: ";
		leer precio;
		
		desc <- precio*0.15;
		precioFinal <- precio-desc;
		Escribir "El total a pagar es: ", precioFinal;
		
	FinProceso

Ejercicio 6

	// Un alumno desea saber cuál será su calificación final en la materia de Algoritmo, dicha calificicación se compone
	// de los sgtes %
	// 55% del promedio de sus 3 calificaciones de los parciales.
	// 30% de la calificación del exámen final.
	// 15% de la calificación de un trabajo final.

	Proceso estructura_secuenciales
		Definir parcial1, parcial2, parcial3, promedioPar Como Real;
		Definir examenFinal, trabajoFinal como real;
		Definir porcentaje_Del_Promedio, porcentaje_del_ExamenFinal, porcentaje_Del_TrabajoFinal como real;
		
		Escribir "Digite los parciales: ";
		leer parcial1, parcial2, parcial3;
		Escribir  "Digite la nota del exámen final: ";
		leer  examenFinal;
		Escribir  "Digite la nota del trabajo final: ";
		leer  trabajoFinal;
		
		promedioPar <- (parcial1+parcial2+parcial3)/3;
		porcentaje_Del_Promedio <- promedioPar*55/100;
		porcentaje_del_ExamenFinal <- examenFinal*30/100;
		porcentaje_Del_TrabajoFinal <- trabajoFinal*15/100;
		
		Escribir "La nota final es: ", porcentaje_Del_Promedio+porcentaje_del_ExamenFinal+porcentaje_Del_TrabajoFinal;
		
	FinProceso

## 5. Capítulo V Estructuras Condicionales

Comparan una variable contro otro(s) valor(es), para que en base al resultado de ésta comparaciónn se siga un curso de acción dentro del programa. Existen 3 tipos: Simples, dobles y múltiples.

Condicional simple: es cuando se evalua una condición donde si es vverdadera ejecutará un grupo de acciones y si es falsa no hará nada.

- Sintaxis: 
			
			Si <condición> Entonces
				acción(es)
			finSi

Condicionales dobles: es cuando se evalua una condición donde si es verdadero se realizará acciones y si es falsa se realizará otro tipo de acciones.

- Sintaxis: 
			
			Si <condición> Entonces
				acción(es)1
				SiNo 
				acción(es)2
			finSi

Condicionales múltiples: Es cuando se evalua una condición donde puede tener diferentes tipos de valores con e cual podemos compararlas.

- Sintaxis: 
			
			Segun <Condición> Hacear
				opción1:
					Acciones1
				opción2:
					Acciones2
				opción3:
					Acciones3
				opciónN:
					AccionesN	
				De otro modo
			FinSegun

Ejercicio 1

	// Ingrese un nro entero y reportar si es par o impar
	
	Proceso estructura_Condicionales
		Definir num Como Entero;
		Escribir "Digite el nro entero: ";
		leer num;	
		si (num mod 2 == 0) Entonces
			Escribir "El número ",num, " es par ";
		sino 
			Escribir "El número ",num, " es impar ";
		FinSi
	FinProceso

Ejercicio 2

	//  Determinar si un alumno aprueba o reprueba un curso sabiendo que aprobará si su promedio de tres calificaciones
	// 	es mayor o igual a 70, reprueba caso contrario
	
	Proceso estructura_Condicionales
		Definir nota1, nota2, nota3, promedio Como real;
		Escribir "Digite las notas: ";
		leer nota1, nota2, nota3;	
		promedio <- (nota1+nota2+nota3)/3;
		
		si promedio >= 70 Entonces
			Escribir "El alumno tiene como nota final ",promedio, ", por lo tanto aprobó.";
		SiNo
			Escribir "El alumno tiene como nota final ",promedio, ", por lo tanto reprobó.";
		FinSi
	FinProceso

Ejercicio 3

	//  En un almacen se hace un 20% de descuento a los clientes cuya compra supere los 100$
	// 	¿Cuál será la cantidad que pagará una persona por su compra?
	
	Proceso estructura_Condicionales
		Definir precio, descuento Como real;
		Escribir "Digite el precio inicial de la persona: ";
		leer precio;	
		
		si precio > 100 Entonces
			descuento <- precio * 20/100;
			precio <- precio - descuento;
			Escribir "El monto que debe pagar es: ", precio;
		SiNo
			Escribir "El cliente debe pagar: ", precio;
		FinSi

	FinProceso

Ejercicio 4

	//  Leer 2 números, si son inguales que los multiplique, si el 	1ro es mayor que el 2do 
	// 	que los reste y si no que los sume.
		
	Proceso estructura_Condicionales

		Definir num1, num2, resultado Como real;
		Escribir "Digite el 1er numero: ";
		leer num1;	
		Escribir "Digite el 2do numero: ";
		leer num2;
		
		si num1 == num2 Entonces
			// Si son iguales multiplicacmos
			resultado <- num1*num2;
		SiNo
			si num1>num2 Entonces
				// si el 1er nro es mayor restamos.
				resultado <- num1-num2;
			SiNo
				//si el 2do es mayor sumamos
				resultado <- num1+num2;
			FinSi
		FinSi
		Escribir "El resultado es: ", resultado;
	FinProceso

Ejercicio 5

	//  Leer 3 nros diferente e imprimir el nro mayor de los 3

	Proceso estructura_Condicionales
		Definir num1, num2, num3 Como real;
		Escribir "Digite el 1er numero: ";
		leer num1;	
		Escribir "Digite el 2do numero: ";
		leer num2;
		Escribir "Digite el 3er numero: ";
		leer num3;
		
		si num1 > num2 y num1 > num3 Entonces
			// comparamos 1er nro con el 2do y 3er nro.
			Escribir "El mayor es ", num1;
		SiNo
			si num2>num3 Entonces
				// comparamos 2do nro con el 3er.
				Escribir "El mayor es: ", num2;
			SiNo
				//el mayor es el 3er
				Escribir "El mayor es: ", num3;
			FinSi
		FinSi
	FinProceso

Ejercicio 6

	// Una fruteria ofrece las manzanas con descuentos según la sigte tabla:
	//	nro de kgs comprados	descuento
	//	0-2						0%
	//	2.01-5					10%
	//	5.01-10					15%
	//	10.01 en adelante		20%
	// Determinar cuánto pagará una persona que compre manzanas en esa frutería

	Proceso estructura_condicionales
		definir precio_por_kilo, cantidad_kilos, total_inicial, total_final, descuento como real;
		
		Escribir "Digite el precio del Kilo de la manzana: ";
		leer precio_por_kilo;
		Escribir "Digite la cantidad de Kilos que compró la persona; ";
		leer cantidad_kilos;
		total_inicial <- cantidad_kilos*precio_por_kilo;
		
		si cantidad_kilos<=2 Entonces
			// descuento del 0%
			descuento <- total_inicial*0/100;
		SiNo
			si cantidad_kilos>2 Y cantidad_kilos<=5 Entonces
				// descuento del 10%
				descuento <- total_inicial*10/100;
			SiNo
				si cantidad_kilos>5 y cantidad_kilos<=10 Entonces
					// descuento del 15%
					descuento <- total_inicial*15/100;
				SiNo
					si cantidad_kilos>10 Entonces
						// descuento del 20%
						descuento <- total_inicial*20/100;
					FinSi
				FinSi
			FinSi
		FinSi
		total_final <- total_inicial-descuento;
		Escribir "El total que debe cancelar el cliente es de: ", total_final, "$";
	FinProceso

Ejercicio 7 Multiples

	// Elaborar un programa que me muestre los días de la semána cuando ingrese los 1ros 7 nros
	// Lúnes = 1, Martes = 2, Miércoles = 3, Jueves = 4, Viernes = 5, Sábado = 6, Domingo = 7
	Proceso estructura_condicionales
		Definir num como enteros;
		Escribir "Digite los 1 nro del día de la semána (1-7): ";
		leer num;
		Segun num hacer
			1: Escribir "lúnes";
			2: escribir "martes";
			3: escribir "miércoles";
			4: escribir "jueves";
			5: escribir "viernes";
			6: escribir "sábado";
			7: escribir "domingo";
			De Otro Modo:
				Escribir "Error, sólo puede digitar nros de la semána del 1 al 7";
		FinSegun
	FinProceso

Ejercicio 8

	// Elaborar un programa que muestre el significado de cada decada hasta los 60
	// bodas de hojalata			10 años
	// bodas de porcelana			20 años
	// bodas de perla				30 años
	// bodas de rubi				40 años
	// bodas de oro					50 años
	// bodas de diamantes			60 años
	Proceso estructura_condicionales
		Definir decada como enteros;
		Escribir "Digite una decada desde 10 hasta 60: ";
		leer decada;
		Segun decada hacer
			10: escribir "bodas de hojalata";
			20: escribir "bodas de porcelana";
			30: escribir "bodas de perla";
			40: escribir "bodas de rubi";
			50: escribir "bodas de oro";
			60: escribir "bodas de diamantes";
			De Otro Modo:
				Escribir "Error, sólo puede digitar decadas desde 10 hasta 60";
		FinSegun
	FinProceso

Ejercicio 9

	// Elaborar un programa que tenga un menú con las sgts opciones
	// Opción 1: Elevar un número a la potencia X
	// Opción 2: Sacar la raíz cuadrada de un número
	// Opción 3: salir

	Proceso estructura_condicionales
		Definir opcion como real;
		Escribir "MENÚ";
		Escribir "Opción 1: Elevar un número a la potencia X";
		Escribir "Opción 2: Sacar la raíz cuadrada de un número";
		Escribir "Opción 3: salir";
		Escribir "Por favor digite una opción";
		leer opcion;
		
		segun opcion Hacer
			
			1:	Definir numPotencia, potenciaElevada, resultadoPot como reales;
				escribir "Digite un nro: ";
				leer numPotencia;
				Escribir "Digite el nro de la potencia elevada: ";
				leer potenciaElevada;
				resultadoPot <- numPotencia^potenciaElevada;
				Escribir "La potencia es ", resultadoPot;
			2: 	Definir  numRaiz, resultadoRaiz como reales;
				escribir "Digite un nro: ";
				leer numRaiz;
				resultadoRaiz<- raiz(numRaiz);
				Escribir "La raiz cuadrada de ",numRaiz," es igual a: ",resultadoRaiz;
			3: escribir "Saliste del programa";
				
			De Otro Modo:
				escribir "Error, sólo puede elegir una de las 3 opciones.";
		FinSegun
	FinProceso

## 6. Capítulo VI Estructuras Repetitivas

Se llaman problemas repetitivos o ciclicos a aquellos en cuya solución es necesario utilizar un mismo conjunto de acciones que se puede una cantidad específica de veces. Esta cantidad puede ser fija (previamente determinada por el programador).

Los tipos ciclos se clasifican en:

- Ciclos con un número determinado de iteraciones.

	Son aquellos en el que el nro de iteraciones se conoce antes de ejecutarse el ciclo. La forma de esta estructura en pseint es la siguiente:

		Para variableNumerica<-valorInicial Hasta valorFinal Con Paso paso Hacer

		secuenciaDeAcciones
		FinPara


	Ejemplo en Pseint:

		// Imprimir en pantalla los nros del 1 al 10
		Proceso estructura_repetitivas
			// la "i" viene de la palabra iterador, es una variable la cual nos sirve para los bucles y puede aumentar o disminuir su valor.
			Definir i Como Entero;
			Para i<-1 hasta 10 con paso 1 hacer
				escribir i;
			FinPara
		FinProceso

- Ciclos con un número indeterminado de iteraciones.

	Son aquellos en que el nro de iteraciones no se conocen con exactitud, ya que está dado en función de un dato dentro del programa.

	Existen 2 tipos de ciclos 
	
	- Mientras - Hacer
		Es una estructura donde repetira un proceso "N" veces, donde "N" puede ser fijo o variable. Para esto la instrucción se vale de una condición que es la que debe cumplirse para que se siga ejecutando, cuando la condición ya no se cumpla entonces termina el proceso. La forma de esta estructura es la sgte:

			Mientra expresionLogica Hacer
				secuenciaDeAcciones
			FinMientras

		ejemplo

			// Imprimir en pantalla los nros del 1 al 10
				Proceso estructura_repetitivas
					Definir i Como Entero;
					i<-1;
					Mientras i<=10 Hacer
						Escribir i;
						i<-i+1;
					FinMientras
				FinProceso

	- Repetir - Hasta Que

		Esta es una estructura similar en algunar características a la anterior. Repite un proceso una cantidad de veces, pero a diferencia del "Mientras - Hacer", el "Repetir - Hasta Que" lo hace hasta que la condición se cumpla y no mientras. Por otra parte, esta estructura permite realizar el proceso cuando menos una vez, ya que la condición se valua al final del proceso, mientras que en el "Mientras - Hacer" puede que nunca llegue a entrar si la condición no se cumple desde un principio. La forma de esta estructura es la sgte:

			Repetir
				secuenciaDeAcciones
			Hasta Que esxpresioLogica

		ejemplo

Ejercicios de todos los tipos de ciclos.

Ciclo Para - Hasta - Hacer

Ejercicio 1

	// Se desea calcular independientemente la suma de los nros 
	Proceso estructura_condicionales
		Definir i, n, suma Como Entero;
		suma <- 0;
		Escribir "Digite la cantidad de los números que quiere sumar: ";
		leer n;
		
		Para i<-1 Hasta n con paso 1 Hacer
			suma <- suma + i;
		FinPara
		
		Escribir suma;
	FinProceso

Ejercicio 2

	// Se desea calcular independientemente la suma de los nros pares e impares comprendidos entre 1 y 50
	// sumaPares = 2+4+6+8+....+48
	// sumaImpares = 3+5+7+....49
	Proceso estructura_condicionales
		Definir i, sumaPares, sumaImpares Como Real;
		sumaImpares<-0;
		sumaPares<-0;
		para i<-2 hasta 49 Con Paso 1 hacer
			SI i mod 2 == 0 Entonces
				sumaPares<-sumaPares+i;
			SiNo
				sumaImpares<-sumaImpares+i;
			FinSi
		FinPara
		Escribir "La suma de los pares es ",sumaPares;
		Escribir "La suma de impares es: ", sumaImpares;
	FinProceso

Ejercicio 3

	// Leer 10 nros e imprimir cuántos son positivos, cuántos negativos, y cuántos neutros

	Proceso estructura_condicionales
		Definir i, num Como Real;
		definir contadorPositivo, contadorNegativo, contadorNeutro como real;
		contadorPositivo<-0;
		contadorNegativo<-0;
		contadorNeutro<-0;
		para i<-1 hasta 10 Con Paso 1 hacer
			Escribir i, ". Digite un número: ";
			leer num;
			
			SI num==0 Entonces
				contadorNeutro<-contadorNeutro+1;
			SiNo
				si num > 0 Entonces
					contadorPositivo<-contadorPositivo+1;
				SiNo
					contadorNegativo<-contadorNegativo+1;
				FinSi
			FinSi
		FinPara
		
		Escribir "La cantidad de los nros positivos es ",contadorPositivo;
		Escribir "La cantidad de los nros negativos es ",contadorNegativo;
		Escribir "La cantidad de los nros neutros es ",contadorNeutro;
	FinProceso

Ejercicio 4

	// Suponga que tiene un conjunto de calificaciones de un grupo de 10 alumnos
	// Realizar un algoritmo para calcular la calificación promedio y la calificación más baja de todo el grupo.

	Proceso estructura_condicionales
		Definir notaAlumno, sumaNotas,notaBaja, promedio Como reales;
		Definir i como entero;
		sumaNotas<-0;
		notaBaja<-999;
		Para i<-1 hasta 10 Con Paso 1 Hacer
			Escribir "digitar nota ",i;
			leer notaAlumno;
			
			//Suma iterativa de las calificaciones
			sumaNotas<-sumaNotas+notaAlumno;
			
			//Calculamos la menor calificación
			si notaAlumno<notaBaja Entonces
				notaBaja<-notaAlumno;
			FinSi
		FinPara
		promedio<-sumaNotas/10;
		Escribir "El promedio de las calificaciones es ",promedio;
		Escribir "La nota mas baja es ",notaBaja;
		
	FinProceso

Ejercicio 5 (Ciclo Mientras- Hacer)

	//  Calcular el factorial de un nro mayor o igual a cero
	// 	N! = 1*2*3*4*5*6.....N

	Proceso estructura_condicionales
		Definir n, i, factorial como entero;
		i<-1;
		factorial<-1;
		Repetir
			Escribir "Digite el nro: ";
			leer n;
		Hasta Que n>=0 
		
		// 	N! = 1*2*3*4*5*6.....N
		Mientras i<=n Hacer
				factorial<-factorial*i;
				i<-i+1;
			FinMientras
		Escribir "El factorial es: ", factorial;
	FinProceso

Ejercicio 6

	//  Calcular la sgte sumatoria de los "N" elementos
	// 	S = 1+4+9.....
	Proceso estructura_condicionales
		Definir num, i,suma, elevador como entero;
		suma<-0;
		i<-1;
		Escribir "Digite la cantidad: ";
		leer num;
		//Mientras que i sea menor o igual al nro digitado
		Mientras i<=num Hacer
			//Elevamos la variable elevador al cuadrado
			elevador<-i^2;
			i<-i+1;
			//Sumamos hasta que termine el ciclo
			suma<-suma+elevador;
		FinMientras
		Escribir "La suma total es: ", suma;
	FinProceso

Ejercicio 7

	//  Ingresar "N" enteros, visualizar la suma de los N pares de la lista, cuántos nros pares existen
	// 	y cuál es el promedio de los nros impares.

	Proceso estructura_condicionales
		Definir cantidadEnteros, num, i, sumaPares, sumaImpares, cantidadPares, cantidadImpares como entero;
		Definir  promedioImpares como real;
		sumaPares<-0;
		sumaImpares<-0;
		cantidadPares<-0;
		cantidadImpares<-0;
		i<-1;
		// ¿Cuántos enteros va a ingresar?
		Escribir "¿Cuántos enteros va a ingresar?";
		Leer cantidadEnteros;
		Mientras i<=cantidadEnteros Hacer
			Escribir i,". Digite un nro: ";
			leer num;
			si num mod 2==0 Entonces
				//Sumamos los pares
				sumaPares <- sumaPares + num;
				//Contamos  la cantidad de pares
				cantidadPares <- cantidadPares + 1;
			SiNo
				//El nro es impar
				//Sumamos lo impares
				sumaImpares <- sumaImpares + num;
				//Contamos los impares
				cantidadImpares <- cantidadImpares + 1;
			FinSi
			i<-i+1;
		FinMientras
		
		si cantidadPares = 0 Entonces
			Escribir "No se ha digitado ningún nro par";
		SiNo
			Escribir "La suma de los nros pares es: ",sumaPares;
			Escribir "La cantidad de nros pares es: ",cantidadPares;
		FinSi
		si cantidadImpares = 0 Entonces
			Escribir "No se ha digitado ningún nro impar";
		SiNo
			promedioImpares <- sumaImpares/cantidadImpares;
			Escribir "El promedio de los nros impares es: ",promedioImpares;
		FinSi
	FinProceso

Ejercicio 10

	// Dadas las horas trabajadas de 5 personas y la tarifa de pago, calcular el salario, y la sumatoria
	// de todos los salarios.

	Proceso condicionalesRepetitivas
		Definir horasTrabajadas, pagoPorHora, i, salarioIndividual, salarioTotal como enteros;
		i<-1;
		salarioTotal<-0;
		
		
		Mientras i<=5 Hacer
			Escribir "Digite las horas trabajadas del empleado ",i,":";
			leer horasTrabajadas;
			Escribir "Digite la tarifa de pago por hora: ";
			leer pagoPorHora;
			// Calculamos el salario de la persona
			salarioIndividual<-horasTrabajadas*pagoPorHora;
			
			Escribir "El salario de la persona ",i," es de: ",salarioIndividual, "$";
			salarioTotal<-salarioIndividual+salarioTotal;
			i<-i+1;
			Escribir "";
		FinMientras
		Escribir "La sumatoria de todos los salarios es de ",salarioTotal," $";
	FinProceso

Ejercicio 11 (Repetir - Hasta Que)

Hecho de 2 maneras.

1er Manera: 

	// Calcular la suma de los N terminos de la siguiente serie
	// 1 - 1/2 + 1/3 - 1/4 + 1/5 - 1/6 - ......+ 1/N

	Proceso condicionalesRepetitivas
		Definir i, N, suma, termino como real;
		i<-1;
		suma<-0;
		termino<-i;
		Repetir
			Escribir "Digite cuántos términos quiere sumar: ";
			leer N;
		Hasta Que N>0
		
		Repetir
			suma<-suma+termino;
			i<-i+1;
			si i mod 2 == 0 Entonces
				termino<--1/i;
			SiNo
				termino<-1/i;
			FinSi
			
			
		Hasta Que i>N
		
		Escribir "La suma es de: ", suma;
	FinProceso

2da Manera: 

	// Calcular la suma de los N terminos de la siguiente serie
	// 1 - 1/2 + 1/3 - 1/4 + 1/5 - 1/6 - ......+ 1/N

	Proceso condicionalesRepetitivas
		Definir i, N, suma, signo como real;
		Repetir
			Escribir "Digite cuántos términos quiere sumar: ";
			leer N;
		Hasta Que N>0
		i <- 1;
		suma <- 0;
		signo <- 1;
		Repetir
			suma <- suma + signo/i;
			signo <- signo * (-1);
			i <- i + 1;
		Hasta Que i>N
		
		Escribir "La suma es de: ", suma;
	FinProceso

Ejercicio 10

	// Ingresar N nros,calcular el máximo y el mínimo de ellos
	// 

	Proceso condicionalesRepetitivas
		Definir nElementos, i, num,  maximo, minimo como enteros;
		Repetir
			Escribir "Digite la cantidad de nros que va a digitar: ";
			leer nElementos;
		Hasta Que nElementos>0
		Escribir "1. digite un nro: ";
		Leer num;
		maximo <- num;
		minimo <- num;
		i<-2;
		Repetir
			Escribir i," Digite un nro: ";
			Leer num;
			si num>maximo Entonces
				maximo<-num;
			SiNo
				si num<minimo Entonces
					minimo<-num;
				FinSi
			FinSi
			i<-i+1;
		Hasta Que i>nElementos
		Escribir "El mayor nro es: ", maximo;
		Escribir "El menor nro es: ", minimo;
	FinProceso

Ejercicio 11

	//  imprimir la serie de los N terminos de la serie Fibonacci.
	// 		0, 1, 1, 2, 3, 5, 8, 13, 21......
	// 	a	b  c  <----Es la lógica, imaginariamente "a" vale 1 para sumar con "b"
	// 		a  b	 <----Es la lógica, "a" será igual a "b" y "b" será igual a c
	Proceso condicionalesRepetitivas
		Definir nElementos, i, a, b, c, almacenar Como Entero;
		Repetir
			escribir "Dame la cantidad de elementos: ";
			leer nElementos;
		Hasta Que nElementos>0
		i<-1;
		a<-1;
		b<-0;
		c<-0;
		almacenar<-c;
		Repetir
			Escribir almacenar,", ";
			c<-a+b;
			a<-b;
			b<-c;
			
			almacenar<-c;
			i<-i+1;
		Hasta Que i>nElementos
	FinProceso

Ejercicio 12

	//  Calcular la sumatoria 
	// 	s = 1 + x/1! + x^2/2! + x^3/3! + ...., x^n/n!
	// Se debe ingresar X real y N entero positivo

	Proceso condicionalesRepetitivas
		definir  x, potencia, suma, termino como real;
		definir   N, i, factorial como entero;
		Escribir "Digite el valor de X: ";
		Leer X;
		repetir	
			Escribir "Ingrese el Valor de N: ";
			leer N;
		Hasta Que N>0
		suma <- 1;
		termino<-0;
		i<-1;
		
		factorial<-1;
		Repetir
			factorial<-factorial*i;
			potencia <-x^i;
			i<-i+1;
			termino <- potencia/factorial;
			suma <- suma + termino;
		Hasta Que i>N
		Escribir "La sumatoria es: ", suma;
	FinProceso

## 7. Capitulo VII Arreglos (Arrays)

Es una estructura de datos que almacena una colección de datos del mismo tipo. Se las conoce también como vectores(Arreglo unidimencional) y matrices(arreglo bidimencioanl).

[Ver un video](https://www.youtube.com/watch?v=x1WLlQiedic)

Los arreglos se caracterizan por:

- Almacenan los elementos en posiciones contiguas de memoria
- Tienen un mismo nombre de variable como en algún caso números que representa a todos los elementos para hacer referencia a esos elementos es necesario utilizar un índice que especifique el lugar que ocupa cada elemento dentro del arreglo. Ejemplo.

	![ejemplo](https://www.tutorialesprogramacionya.com/delphiya/imagentema/foto055.jpg)


- Podemos crear arreglos de distintas dimensiones.

De ésta manera agregamos un arreglo unidimensional en Pseint:

		Proceso PruebaArreglo
			Definir num como entero;
			Dimension num[5];
		FinProceso

## 7.1 Arreglo Unidimensionales

Es un arreglo de N elementos organizados un una dimesión, donde N es el nro de elementos.

Por ejemplo, con tipo de dato Entero:

	Definir arregloNum Como Entero;
	Dimension arregloNum[5]; // en los corchetes hay un solo elemento
							// eso quiere decir que es de una sola dimesión.

Otro ejemplo, con tipo de dato Real: 

	Definir arregloReales Como Real;
	Dimension arregloReales[4];

Otro ejemplo, con tipo de dato caracter: 

	Definir arregloCaracter Como Caracter;
	Dimension arregloCaracter[5];

Otro ejemplo, con tipo de dato cadena: 

	Definir arregloCadena Como Cadena; //Con cadenas se pueden escribir palabras
	Dimension arregloCadena[5];

Ejemplos en Pseint

LLenando manualmente:

	//  Llenar y mostrar un arreglo

	Proceso arregloUnidimensional
		Definir num Como Entero;
		Definir i Como Entero;
		Dimension num[4];
		
		//Damos valores manualmente
		num[0] <- 14;
		num[1] <-18;
		num[2] <-9;
		num[3] <-2;
		
		//Mostrar los elementos del arreglo
		para i<-0 hasta 3 Con Paso 1 Hacer
			Escribir num[i];
		FinPara
	FinProceso

Ejemplo llenado con elementos que digite el usuario:

	//  Llenar y mostrar un arreglo

	Proceso arregloUnidimensional
		Definir num Como Entero;
		Definir i, longi Como Entero;
		// Pedimos la longitud de los elementos del array
		Escribir "Digite la lingitud del arreglo: ";
		leer longi;
		Dimension num[longi];
		
		//Llenando pidiendo al usuario que digite los elementos
		Para i<-0 hasta longi-1 Con Paso 1 Hacer
			Escribir i , "Digite un nro: ";
			leer num[i];
		FinPara
		//Mostrar los elementos del arreglo
		para i<-0 hasta 3 Con Paso 1 Hacer
			Escribir num[i];
		FinPara
	FinProceso

Ejercicio 1

	//  Crea un arreglo unidimensional con un tamaño dado por el usuario (Nros reales), pregúntale al usuario
	//	los valores y calcula la suma y promedio de todos ellos
	Proceso arregloUnidimensional
		Definir num, longi, suma Como Reales;
		Definir  i Como Entero;
		definir promedio como real;
		// Pedimos la longitud de los elementos del array
		Escribir "Digite el nro de elementos del arreglo: ";
		leer longi;
		Dimension num[longi];
		
		//Llenando pidiendo al usuario que digite los elementos
		para i<-0 Hasta longi-1 Con Paso 1 hacer
			Escribir i, " Digite un nro: ";
			Leer num[i];
		FinPara
		
		//Declaramos variables
		suma<-0;
		// Sumar los elementos
		para i<-0 hasta longi-1 Con Paso 1 hacer
			suma <- suma + num[i];
			promedio <- suma/longi;
		FinPara
		
		Escribir "La suma de todos los elementos es de: ",suma;
		Escribir "El promedio es: ",promedio;
	FinProceso

Ejercicio 2

	//  Crear un arreglo unidimensional donde el usuario indique el tamaño por teclado
	//	Luego llenar el arreglo con nros aleatorios entre 1-100, luego mostrarlos en pantalla

	Proceso arregloUnidimensional
		Definir num, nElementos Como Reales;
		Definir  i Como Entero;
		definir promedio como real;
		// Pedimos la longitud de los elementos del array
		Escribir "Digite el nro de elementos del arreglo: ";
		leer nElementos;
		Dimension num[nElementos];
		
		//LLennar arreglo con nro aleatorios entre 1-100
		para i<-0 hasta nElementos-1 Con Paso 1 Hacer
			num[i]<-azar(100)+1;
			Escribir num[i];
		FinPara
	FinProceso

Ejercicio 3 

	//  Crear un arreglo unidimensional con N caracteres donde el usuario indique el tamaño por teclado,
	//	digitar los elementos por teclado y muestrarlos en orden inverso al introducido

	Proceso arregloUnidimensional
		Definir letras como caracter;
		Definir  i Como Entero;
		definir nElementos como entero;
		// Pedimos la cantidad de elementos del array
		Repetir
			Escribir "Digite el nro de elementos del arreglo: ";
			leer nElementos;
		Hasta Que nElementos>0
		Dimension letras[nElementos];
		// Pedimos al usuario que ingrese elementos de tipo caracter
		para i<-0 hasta nElementos-1 Con Paso 1 Hacer
			Escribir i," Digite un caracter: ";
			leer letras[i];
		FinPara
		para i<-nElementos-1 hasta 0 Con Paso -1 Hacer
			Escribir letras[i];
		FinPara
	FinProceso

Ejercicio 4

	//  Crear un arreglo unidimensional con N nros donde el usuario indique el tamaño por teclado,
	//	digitar los elementos por teclado, calcular cuál de los nros es el mayor y cuál es el menor

	Proceso arregloUnidimensional
		Definir num, mayor, menor, nroMayor, nroMenor como entero;
		Definir  i Como Entero;
		definir nElementos como entero;
		// Pedimos la cantidad de elementos del array
		Repetir
			Escribir "Digite el nro de elementos del arreglo: ";
			leer nElementos;
		Hasta Que nElementos>0
		Dimension num[nElementos];
		// Pedimos al usuario que ingrese elementos de tipo caracter
		para i<-0 hasta nElementos-1 Con Paso 1 Hacer
			Escribir i," Digite un nro: ";
			leer num[i];
		FinPara
		mayor<-num[0];
		menor<-num[0];
		Para i<-1 Hasta nElementos-1 Con Paso 1 Hacer
			si num[i]>mayor Entonces
				mayor<-num[i];
			SiNo
				si num[i]<menor Entonces
					menor<-num[i];
				FinSi
			FinSi
		FinPara
		Escribir "El mayor es: ", mayor;
		Escribir "El menor es: ", menor;
	FinProceso

Ejercicio 5

Resuelto de 2 maneras:

1er manera:

	//  Leer 8 nros enteros dentro de un arreglo, debemos mostrarlos en el sgte orden:
	//	El 1ro, el último, el 2do, el penúltimo, el tercero, etc.

	Proceso arregloUnidimensional
		Definir num, i,i2 Como Entero;
		Definir mitad como entero;
		Dimension num[8];
		mitad<-8/2;
		i2<-7;
		Para i<-0 hasta 7 Con Paso 1 Hacer
			Escribir (i+1),"Digite un nro: ";
			Leer num[i];
		FinPara
		Para i<-0 Hasta mitad Con Paso 1 Hacer
			Escribir num[i];
			si	i2>mitad Entonces
				Escribir num[i2];
				i2<-i2-1;
			FinSi
		FinPara
	FinProceso

2da manera:

	//  Leer 8 nros enteros dentro de un arreglo, debemos mostrarlos en el sgte orden:
	//	El 1ro, el último, el 2do, el penúltimo, el tercero, etc.

	Proceso arregloUnidimensional
		Definir num, i Como Entero;
		Dimension num[8];
		Para i<-0 hasta 7 Con Paso 1 Hacer
			Escribir (i+1),". Digite un nro: ";
			Leer num[i];
		FinPara
		Para i<-0 Hasta 3 Con Paso 1 Hacer
			Escribir num[i];
			Escribir num[7-i];
		FinPara
	FinProceso

Ejercicio 6

	//	Leer pol teclado una serie de 5 nros reales. El programa debe indicarnos si los nros estan ordenados
	//	de forma creciente, decreciente o si estan desordenados.

	Proceso arreglosUnidimensionales
		Definir num Como Real;
		Definir i Como Entero;
		Definir  creciente, decreciente Como Logico;
		Dimension num[5];
		// Pedimos valores al usuario
		para i<-0 Hasta 4 Con Paso 1 Hacer
			Escribir (i+1),". Digite un nro: ";
			Leer num[i];
		FinPara
		// Declaramos variables
		creciente<-falso;
		decreciente<-falso;
		//  Creciente 1,2,3,4,5
		Para i<-0 hasta 3 Con Paso 1 Hacer
			si num[i]<num[i+1] Entonces
				creciente<-Verdadero;
			FinSi
			// Decreciente 5,4,3,2,1
			si num[i]>num[i+1] Entonces
				decreciente<-Verdadero;
			FinSi
		FinPara
		//  Comprobar si los nros están de forma creciente, decreciente o desordenados
		si creciente=Verdadero y decreciente=falso Entonces
			Escribir "Forma creciente";
		SiNo
			si creciente=falso y decreciente=Verdadero Entonces
				Escribir "Forma decreciente";
			SiNo
				Escribir "Forma desordenada";
			FinSi
		FinSi
	FinProceso

Ejercicio 7

	//	Crear un programa que lea por teclado un arreglo de 6 numeros y la desplace hacia adelante:
	//	el 1ro pasa a ser el 2do, el 2do pasa a ser el 3ro y así sucesivamente. El último pasa a ser el 1ro

	Proceso arreglosUnidimensionales
		Definir num, ultimo Como entero;
		Definir i Como Entero;
		Dimension num[6];
		// Pedimos valores al usuario
		para i<-0 Hasta 5 Con Paso 1 Hacer
			Escribir (i+1),". Digite un nro: ";
			Leer num[i];
		FinPara
		//Guardamos el último elemento del arreglo
		ultimo<-num[5];
		//Desplazamos el arreglo una posición 
		// 1-1-2-3-4-5
		Para i<-4 hasta 0 Con Paso -1 Hacer
			num[i+1]<-num[i];
		FinPara
		// Almacenamos el último valor al 1er elemento
		num[0]<-ultimo;
		// Mostramos el arreglo ordenado
		Para i<-0 hasta 5 Con Paso 1 Hacer
			Escribir num[i];
		FinPara
	FinProceso

Ejercicio 8

	// Leer 5 elementos numéricos que se introduciran ordenados de forma creciente.
	// Éstos los guardaremos en un arreglo de tamaño 6. Leer un nro N,
	// e insertarlo en el lugar adecuado para que el arreglo continue ordenado

	Proceso arreglosUnidimensionales
		Definir num, dato, j, posicion Como entero;
		Definir i Como Entero;
		Definir esCreciente Como Logico;
		esCreciente<-falso;
		Dimension num[6];
		
		Repetir
			esCreciente<- Verdadero;
			// Pedimos valores al usuario
			para i<-0 Hasta 4 Con Paso 1 Hacer
				Escribir (i+1), ". Digite un nro";
				Leer num[i];
			FinPara
			// Comprobamos si los nros van digitados de forma creciente
			Para i<-0 hasta 3 Con Paso 1 hacer
				si num[i]>=num[i+1] Entonces
					esCreciente<-falso;
				FinSi
			FinPara
			Si esCreciente=Falso Entonces
				Escribir "Debe digitar los digitos en forma creciente. ";
			FinSi
		Hasta Que esCreciente=Verdadero 
		//Agregamos el valor a agregar al arreglo
		Escribir "Digite el valor para agregar al arreglo";
		leer dato;
		j<-0;
		posicion<-0;
		// Ubicamos la posicion donde se insertará el dato
		Mientras num[j]<dato y j<5 Hacer
			posicion<-posicion+1;
			j<-j+1;
		FinMientras
		//Recoremos los elementos
		Para j<-4 hasta posicion Con Paso -1 Hacer
			num[j+1]<-num[j];
		FinPara
		num[posicion]<-dato;
		// Escribimos el nuevo arreglo ordenado
		Para i<-0 Hasta 5 Con Paso 1 Hacer
			Escribir num[i];
		FinPara
	FinProceso

Ejercicio 9

	// Leer por teclado un arreglo de 5 elementos numéricos y una posición y(entre 0-4).
	// Eliminar el elemento situado en la posición dada sin dejar hueco. 

	Proceso arreglosUnidimensionales
		Definir num, i, posicion Como Entero;
		Dimension num[5];
		Para i<-0 hasta 4 Con Paso 1 Hacer
			Escribir (i+1),". Digite un nro: ";
			leer num[i];
		FinPara
		Repetir
			Escribir "Digite la posición que quiere eliminar: ";
			leer posicion;
		Hasta Que posicion<4
		// Ubicamos el lugar que vamos a eliminar 
		// 1 - 2 - 3 - 4 - 5       2
		// 1 - 2 -   - 4 - 5 
		// 1 - 2 - 4 - 5
		i<-0;
		Mientras i<4 hacer
			si i = posicion Entonces
				//desplazando el arreglo
				Mientras i<=3 Hacer
					num[i]<-num[i+1];
					i<-i+1;
				FinMientras
			FinSi
			i<-i+1;
		FinMientras
		Escribir "El nuevo arreglo es: ";
		Para i<-0 hasta 3 Con Paso 1 Hacer
			Escribir num[i];
		FinPara
	FinProceso

Ejercicio 10

	// Leer dos arreglos de 5 nros enteros cada uno, que estarán ordenados crecientemente.
	// Copiar (fusionar) los 2 areglos en un tercero, de forma que los números sigan ordenados.

	Proceso arreglosUnidimensionales
		Definir num1, num2, i1, i2 Como Enteros;
		definir numFusionado, i3 como enteros;
		Definir estaOrdenado Como Logico;
		Dimension num1[5], num2[5], numFusionado[10];
		
		// Pedimos el primer arreglo ordenado
		Repetir
			estaOrdenado <- Verdadero;
			Escribir "Digite los elementos del primer arreglo";
			para i1<-0 hasta 4 Con Paso 1 Hacer
				Escribir (i1+1),". Digite un nro";
				leer num1[i1];
			FinPara
			
			// Verificamos si los elementos están ordenados
			Para i1<-0 hasta 3 Con Paso 1 Hacer
				si num1[i1]>num1[i1+1] Entonces
					estaOrdenado<-falso;
				FinSi
			FinPara
			
			//Si estaOrdenado es falso, entonces debe digitar de nuevo
			si estaOrdenado = Falso Entonces
				Escribir "El primer arreglo está desordenado, digite nuevamente.";
			FinSi
		Hasta Que estaOrdenado=Verdadero
		
		// Pedimos el segundo arreglo ordenado
		Repetir
			estaOrdenado <- Verdadero;
			Escribir "Digite los elementos del segundo arreglo";
			para i2<-0 hasta 4 Con Paso 1 Hacer
				Escribir (i2+1),". Digite un nro";
				leer num2[i2];
			FinPara
			
			// Verificamos si los elementos están ordenados
			Para i2<-0 hasta 3 Con Paso 1 Hacer
				si num2[i2]>num2[i2+1] Entonces
					estaOrdenado<-falso;
				FinSi
			FinPara
			
			//Si estaOrdenado es falso, entonces debe digitar de nuevo
			si estaOrdenado = Falso Entonces
				Escribir "El segundo arreglo está desordenado, digite nuevamente.";
			FinSi
		Hasta Que estaOrdenado=Verdadero
		
		//Fusionamos los 2 arreglos al tercero;
		i1<-0; // i1 Arreglo num1
		i2<-0; // i2 Arreglo num2
		i3<-0; // i3 Arreglo numFusionado
		
		//num1 =			1 3 5 7 9 
		//num2 =			2 4 6 8 10
		//numFusionado = 	1 2 3 4 5 6 7 8 9 10
		Mientras i1<5 y i2<5 Hacer
			si num1[i1]<num2[i2] Entonces // El elemento del arreglo num1 es menor 
				numFusionado[i3]<-num1[i1]; // Por lo tanto lo agregamos en el nuevo arreglo
				i1<-i1+1; //Avanzamos el iterador i1 en 1
				
			SiNo //El elemento del arreglo num2 es el menor
				numFusionado[i3]<-num2[i2]; // Por lo tanto lo agregamos en el nuevo arreglo
				i2<-i2+1; //Avanzamos el iterador i2 en 1
			FinSi
			
			i3<-i3+1; //El iterador del nuevo arreglo incrementa
		FinMientras
		
		//Cuando termine el ciclo mientras, significa que ya copiamos un arreglo
		//Falta un arreglo
		
		Si (i1 = 5) Entonces //Hemos terminado de copiar el arreglo num1, falta el arreglo num2
			Mientras (i2<5) Hacer //Copiamos el último elemento de num2 que nos falta
				numFusionado[i3]<-num2[i2]; //Terminamos de copiar el arreglo num2 al nuevo arreglo
				i2<-i2+1;
				i3<-i3+1; //<---- NO HAYNECESIDAD DE PONERLO
			FinMientras
		FinSi
		Si (i2 = 5) Entonces //Hemos terminado de copiar el arreglo num2, falta el arreglo num1
			Mientras (i1<5) Hacer //Copiamos el último elemento de num1 que nos falta
				numFusionado[i3]<-num1[i1]; //Terminamos de copiar el arreglo num1 al nuevo arreglo
				i1<-i1+1;
				i3<-i3+1; //<---- NO HAYNECESIDAD DE PONERLO
			FinMientras
		FinSi
		
		// Mostramos el nuevo arreglo en pantalla
		Para i3<-0 hasta 9 Con Paso 1 Hacer
			Escribir "Elemento " , numFusionado[i3];
		FinPara
	FinProceso

## 8. Capitulo VIII Ordenamientos

Consiste en organizar un conjunto de datos en un orden determinado según un criterio.

La ordenación puede ser interna o externa:

- Interna: La hacemos en memoria con arreglos. Es muy rápida.
- Externa: La hacemos en dispositivos de almacenamiento externo con archivos.

Para determinar lo bueno de un algoritmo de ordenación, hay que ver la complejidad del algoritmo, es decir se mide en el número de operaciones básicas que realiza un algoritmo. La operación básica de un algoritmo es la operación fundamental, que es la comparación. 

Tipos de algoritmos de ordenación:

- Método de la burbuja.
- Método de inserción.
- Método de selección .
- Método Radix Sort
- Método Shell
- Método Mezcias 
- Método Quick Sort 

## 2. Método de la burbuja.

La filosofía de éste método es ir comparando los elementos del arreglo de 2 en 2 y si no están colocados correctamente, intercambiarlos, así hasta que tengamos el arreglo ordenado.

Ejemplo: Ordenar	

					4 1 5 3 2 //
					0 1 2 3 4 //son sub indices -> j

					//nroActual>nroSiguient
					//		Cambio

	Para i<-0  Hasta 3 Con Paso 1 Hacer
		Para j<-0 Hasta 3 Con Paso 1 Hacer
			Si num[j]>num[j+1] Entonces
				aux<-num[j];
				num[j]<-num[j+1];
				num[j+1]<-aux;
			FinSi
		FinPara
	FinPara

Ejercicio completo en PSeInt (Método Burbuja)

	// Método burbuja
	// Pedir 5 elementos y ordenarlos crecientemente
	Proceso principal
		Definir i, j, num, aux Como Enteros;
		Dimension num[5];
		// Pedimos los elementos al usuario
		Para i<-0 Hasta 4 Con Paso 1 Hacer
			Escribir "Digite un nro";
				Leer num[i];
		FinPara
		// Ordenamos los elementos
		Para i<-0 hasta 3 Con Paso 1 Hacer // i incrementa cuando vayamos comparado cada elemento con el resto de elementos,
		// hasta que n elementos sea - 1, o sea en este caso será hasta 3 porque son 5 elementos;
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				si num[j]>num[j+1] Entonces // Si el valor en la posición j es menor al elemento siguiente entonces intercambiamos
					aux<-num[j];
					num[j]<-num[j+1];
					num[j+1]<-aux;
				FinSi
			FinPara
		FinPara
		
		// Mostramos en pantalla el arreglo ordenado.
		Escribir "Este es el arreglo ordenado:";
		Para i<-0 hasta 4 Con Paso 1 Hacer
			Escribir num[i];
		FinPara
	FinProceso

## 3. Método de Inserción.

Es una manera muy natural de ordenar para un ser humano, y puede usarse fácilmente para ordenar un mazo de cartas numeradas en forma arbitraria. Requiere O(n^2) operaciones para ordenar una lista de n elementos. 

Ejercicio demostrando éste método de Inserción:

	// Método por Inserción
	// Pedir 5 elementos y ordenarlos crecientemente
	Proceso principal
		Definir i, num, aux, pos Como Enteros;
		Dimension num[5];
		// Pedimos los elementos al usuario
		Para i<-0 Hasta 4 Con Paso 1 Hacer
			Escribir "Digite un nro";
				Leer num[i];
		FinPara
		// Ordenamos los elementos
		// 3 2 5 4 1 <-- son los valores de elementos, estos valores se almacenarán en el auxiliar
		// 0 1 2 3 4 <-- Son los subíndices del arreglo y se representan como i y pos 
		Para i<-1 hasta 4 Con Paso 1 Hacer // Iniciamos i en 1 porque luego vamos a comparar esa posición con la que tiene en la izquierda
			pos<-i; // pos vale i porque lo que hay en esa posición va a ser la actual
			aux<-num[i]; // almacenamos lo que hay en num[i] para que no perdamos el valor
			Mientras pos>0 y num[pos-1]>aux Hacer // Si es mayor a 0 y el elemento actual es mayor al anterior
				num[pos]<-num[pos-1]; // insertamos el elemento anterior al actual
				pos<-pos-1; // pos disminuye para saber si hay más elementos en que comparar si es mayor al anterior elemento
			FinMientras
			num[pos]<-aux; // Insertamos el valor guardado al espacio en blanco del arreglo
		FinPara
		
		// Mostramos los elementos
		Escribir "";
		Escribir "El arrelo ordenado es: ";
		
		Para i<-0 hasta 4 Con Paso 1 Hacer
			Escribir num[i];
		FinPara
	FinProceso

## Método por selección

Se trata de buscar el elemento más pequeño y colocarlo en la 1ra posición, después el segundo más pequeño y colocarlo en la segunda posición, y así sucesivamente hasta que el arreglo esté ordenado.

Ejercicio demostrando éste método de Selección: 

	// Método por Selección
	// Pedir 5 elementos y ordenarlos crecientemente
	Proceso principal
		Definir i, num, aux, j, min Como Enteros;
		Dimension num[5];
		// Pedimos los elementos al usuario
		Para i<-0 Hasta 4 Con Paso 1 Hacer
			Escribir "Digite un nro";
				Leer num[i];
		FinPara
		// Ordenamos los elementos
		// 3 2 5 4 1 <-- son los valores de elementos
		// 0 1 2 3 4 <-- Son los subíndices del arreglo y se representan como i y j
		
		Para i<-0 hasta 3 Con Paso 1 hacer // Es hasta 3 porque el siguiente ciclo va a sumar un indice mas
			min<-i;// el 1er elemento se almacena en min suponiendo 	que es el menor elemento
			
			// Seleccionamos el elemento menor de todos para luego seleccionarlo y guardarlo en el elemento num[i]
			Para j<-i+1 Hasta 4 Con Paso 1 Hacer // j es igual a i+1 porque va a servir para comparar el siguiente elemento con el elemento actual que es num[min]
				si num[min]>num[j] Entonces // Si el elemento actual (min) es mayor que el siguiente elemento, min será igual a la posición j
					min<-j;
				FinSi
			FinPara
			
			// Insertamos el elemento menor seleccionado en el arreglo
			aux<-num[i];
			num[i]<-num[min];
			num[min]<-aux;
		FinPara

## 9. Capítulo IX Búsquedas

¿Qué son las búsquedas?

Dado un determinado elemento, se trata de ver si existe un elemento con ese valor valor en el arrelo o archivo donde se busca, tal que se devuelva si está o no.

Veremos 2 tipos de búsquedas: 

- Búsqueda Secuencial
- Búsqueda Binaria

### Búsqueda secuencial:

Se puede aplicar para búsquedas interns y externas, y hay que ir pasando secuencialmente por todos los elementos de la estructura hasta encontrar el elemento o acabar la lista.

Ejemplo de Búsqueda secuencial:

	Proceso busqueda
		Definir num, i, posicion, dato Como Entero;
		Definir encontrado Como Logico;
		Dimension num[5];
		// Iniciamos los valores del arreglo
		num[0]<-5;
		num[1]<-45;
		num[2]<-3;
		num[3]<-9;
		num[4]<-1;
		
		// Preguntamos el elemento que el usuario quiere encontrar
		Escribir "Digite el valor que desea buscar: ";
		Leer dato;
		
		// Iniciamos variables
		i<-0;
		encontrado<-falso;
		Mientras i<5 y encontrado=falso Hacer
			si num[i]=dato Entonces
				encontrado<-Verdadero;
				posicion<-i;
			FinSi
			i<-i+1;
		FinMientras
		
		si encontrado=Verdadero Entonces
			Escribir "Elemento encontrado, en la posición: " , posicion;
		SiNo
			Escribir "Elemento no encontrado";
		FinSi
	FinProceso

### Búsqueda Binaria:

Para que se pueda aplicar la búsqueda binaria a un arreglo, éste debe estar previamente ordenado ascendentemente.

Se trata de dividir el espacio de búsqueda en sucesivas mitades hasta encontrar el elemento buscado o hasta que ya no pueda pueda hacer más mitades.

Primero hallamos el índice de la mitad del arreglo y miramos si el elemento coincide con él, si no coincide averiguamos donde debería estar el elemento buscado, si en la parte derecha o izquierda, y dentro de esa mitad hago lo mismo sucesivamente. 

Ejemplo de Búsqueda Binaria:

	Proceso busquedaBinaria
		Definir num, i, posicion, dato, mitad, inf, sup Como Entero;
		Definir encontrado, ascendente Como Logico;
		Dimension num[5];
		
		// Pedimos los valores del arreglo al usuario de forma ascendente
		
		Repetir
			ascendente<-Verdadero;
			para i<-0 Hasta 4 Con Paso 1 Hacer
				Escribir i,". Digite un nro: ";
				leer num[i];
			FinPara
			
			// Verificamos si están ingresados de forma ascendente
			Para i<-0 hasta 3 Con Paso 1 Hacer
				si num[i]<num[i+1] y ascendente=Verdadero Entonces
					ascendente<-Verdadero;
				SiNo
					ascendente<-falso;
				FinSi
			FinPara
			si ascendente=Falso Entonces
				Escribir "Debe digitar nros de manera ascendente.";
			FinSi
		Hasta Que ascendente=Verdadero;
		
		// Preguntamos el elemento que el usuario quiere encontrar
		Escribir "Digite el valor que desea buscar: ";
		Leer dato;
		
		// Ahora sí realizamos la búsqueda
		// Iniciamos las variables
		encontrado<-falso;
		inf<-0; // Inferior Vale 0 porque es el inicio del arreglo
		sup<-5; // Superior vale 5 poque en este arreglo existen 5 elementos
		mitad<-trunc((inf+sup)/2); // Sacamos la mitad del arreglo
		i<-0; // Iniciamos el iterarador en 0
		
		//Mientras que  inferior sea menor o igual a superior y i<5 y 
		Mientras (inf<=sup y i<5 y encontrado=falso) Hacer
			si num[mitad]=dato Entonces // si es verdad entonces almacenamos el valor de la posicion actual
				posicion<-mitad; // Almacenamos el valor de esa posicion
				encontrado<-Verdadero;
			SiNo
				si num[mitad]>dato Entonces
					sup<-mitad;
					mitad<-trunc((inf+sup)/2);
				SiNo
					inf<-mitad;
					mitad<-trunc((inf+sup)/2);
				FinSi
			FinSi
			i<-i+1;
		FinMientras
		
		// Verificamos si se encontró el elemento
		si encontrado=Verdadero Entonces
			Escribir "Elemento encontrado, en la posición: " , posicion;
		SiNo
			Escribir "Elemento no encontrado";
		FinSi
	FinProceso

## 10. Caítulo X Cadenas de Caracteres

## 10.1 Juego de Caracteres: 

En principio se programaba todo con 0 y 1 pero como esto costaba mucho, apareció la necesidad de crear un lenguaje semejante al humano para entendernos más fácilmente con la computadora, y para ello aparecen los juegos de carcteres. 

El juego de caracteres es una especie de alfabeto que usa la máquina.

Hay 2 tipos de caracteres:

- ASCII: El que más se usa.
- EBCDIC: Creado por IBM.

Hay 2 tipos de ASCII, el básico y el extendido.

- En el ASCII Básico, cada caracter se codifica con 7 bits, por lo que existen 2 = 128 caracteres.

- En el ASCII extendido, cada caracter ocupa 8 bits (1 byte) por lo que existirán 2 = 256 caracteres, numerados del 0 al 255.

En el EBCDIC, cada caracter ocupa también 8 bits.

En cualquiera de los 2 juegos existe 4 tipos de caracteres: 

- Alfabéticos: Letras mayúsculas y minúsculas.
- Numéricos: Números.
- Especiales: Todos los que no son letras y números, que vienen del teclado.
- Control: No son imprimibles y tienen asignados caracteres especiales. Sirven para determinar el fin de la línea, fin de texto.

Cadena de Caracteres.

- Es un conjunto de cero o más caracteres. Entre estos caracteres puede estar incluido el blanco.
- Las cadenaas de caracteres se almacenan en posiciones contiguas de memoria. (Al igual que los arreglos.)
- La longitud de una cadena es el número de caracteres de la misma.

	Ejemplos de cadena:

	"Bolivia es grande y hermosa" - Longitud = 27

	"Hola Mundo" - Longitud = 10 

- Una subcadena es una cadena extraída de otra.

	"Bolivia" es una subcadena de "Bolivia es grande y hermosa"

## 10.2 Operaciones con Cadenas

- Función Longitud:

		Proceso principal
			Definir frase como cadena;
			Definir tamanio como entero;
			
			frase <- "Hola Mundo";
			tamanio <- Longitud(frase);
			
			Escribir tamanio;
		FinProceso

- Función SubCadena:

		Proceso principal
			Definir frase, frase2 como cadena;
			
			frase <- "Hola Mundo";
			frase2 <- Subcadena(frase,0,3);
			
			Escribir frase2;
		FinProceso

- Función Concatenar:

		Proceso principal
			Definir frase, frase2, frase3 como cadena;
			Definir tamanio como entero;
			
			frase <- "Hola Mundo";
			frase2 <- " Mi nombre es Cristian";
			frase3 <- Concatenar(frase,frase2);
			Escribir frase3;
		FinProceso

- Función ConvertirANumero:

		Proceso principal
			Definir frase como cadena;
			Definir num Como Entero;
			
			frase <- "100";
			num <- ConvertirANumero(frase)+9;
			
			Escribir num;
			
		FinProceso

- Función ConvertirATexto:

		Proceso principal
			Definir frase como cadena;
			Definir num Como Entero;
			
			num <- 9;
			frase <- ConvertirATexto(num);
			Escribir frase;
			
		FinProceso

- Función Mayúsculas:

		Proceso principal
			Definir frase como cadena;
			
			frase <- "hola";
			frase <- Mayusculas(frase);
			Escribir frase;
			
		FinProceso

- Función Minúsculas:

		Proceso principal
			Definir frase como cadena;
			
			frase <- "HOLA";
			frase <- Minusculas(frase);
			Escribir frase;
			
		FinProceso

Ejercicio 1

	// Diseñe un programa que permita ingresar una cadena de decaracteres, y detecte cuántas vocales tiene.

	Proceso principal
		Definir frase, vocales como cadena;
		Definir contadorVocales, i, j como entero;
		
		// Pedimos cadena al usuario
		Escribir "Escriba una frase: ";
		Leer frase;
		vocales<-"aeiou";
		contadorVocales<-0;
		
		frase <- Minusculas(frase);
		Para i<-0 hasta Longitud(frase)-1 Con Paso 1 Hacer
			Para j<-0 hasta Longitud(vocales)-1 Con Paso 1 Hacer
				si Subcadena(frase,i,i)=Subcadena(vocales,j,j) Entonces
					contadorVocales<-contadorVocales+1;
				FinSi
			FinPara
		FinPara
		
		Escribir "";
		Escribir "La cantidad de vocales en esta cadena es de: ", contadorVocales, " vocales";
		
	FinProceso

Ejercicio 2

	// Calcular la longitud de 2 cadenas de caracteres, y mostrar y mostrar la cadena con mayor longitud

	Proceso principal
		Definir frase1, frase2 como cadena;
		Definir long1, long2 Como Entero;;
		// Pedimos cadena al usuario
		Escribir "Escriba la primer cadena: ";
		Leer frase1;
		
		Escribir "Escriba la segunda cadena: ";
		Leer frase2;
		
		// Comparamos si tienen la misma longitud
		si Longitud(frase1) = Longitud(frase2) Entonces
			Escribir "Ambas cadenas tienen la misma longitud";
		SiNo
			// Comparamos cuál tiene mayor logitud
			si Longitud(frase1) > Longitud(frase2) Entonces
				Escribir "La cadena con mayor longitud es: ", frase1;
				Escribir "Longitud ", Longitud(frase1);
			SiNo
				Escribir "La cadena con mayor longitud es: ", frase2;
				Escribir "Longitud ", Longitud(frase2);
			FinSi
		FinSi
	FinProceso

Ejercicio 3

	// Diseñe un algoritmo cuya entrada sea una Cadena, y un número entero N, cuya función sera generar
	// la cadena dada N veces

	Proceso principal
		Definir frase como cadena;
		Definir num,i Como Entero;
		// Pedimos cadena al usuario
		Escribir "Escriba la cadena: ";
		Leer frase;
		
		Repetir
			Escribir Sin Saltar "Digite el nro ";
			leer num;
		Hasta Que num>0
		
		// Imprimimos la cadena N veces
		Para i<-1 Hasta num Con Paso 1 Hacer
			Escribir frase;
		FinPara
	FinProceso

Ejercicio 4

Manera resuelta de Cristian:

	// Diseñe un algoritmo que  elimine los espacios en blanco de un texto

	Proceso principal
		Definir frase como cadena;
		Definir i Como Entero;
		// Pedimos cadena al usuario
		Escribir "Escriba la cadena: ";
		Leer frase;
		
		// Comparamos caracter por caracter
		Para i<-0 Hasta Longitud(frase)-1 Con Paso 1 Hacer
			si Subcadena(frase,i,i)<>" " Entonces
				Escribir Sin Saltar Subcadena(frase, i,i);
			FinSi
		FinPara
		Escribir "";
	FinProceso

Otra manera resuelta:

	// Diseñe un algoritmo que  elimine los espacios en blanco de un texto

	Proceso principal
		Definir frase, frase2 como cadena;
		Definir i Como Entero;
		
		// Pedimos cadena al usuario
		Escribir "Escriba la cadena: ";
		Leer frase;
		
		i<-0;
		frase2 <- "";
		
		// Comparamos caracter por caracter
		Mientras i<Longitud(frase) Hacer
			
			// Significa que no es un espacio, caso contrario sino es diferente significa que es un espacio
			// y por lo tanto si es un espacio, ni hace no hace nada(es decir no concatena el espacio).
			si Subcadena(frase,i,i) <> ' ' Entonces  
				frase2 <- Concatenar(frase2,Subcadena(frase,i,i));
			FinSi
			i<-i+1;
		FinMientras
		
		Escribir "";
		Escribir "La nueva cadena sin espacios es la siguiente: ",frase2;
	FinProceso

Ejercicio 5

	// Cambiar una cadena de caracteres al revés

	Proceso principal
		Definir frase, frase2 como cadena;
		Definir iUltimo Como Entero;
		
		// Pedimos cadena al usuario
		Escribir "Escriba la cadena: ";
		Leer frase;
		

		frase2 <- "";
		iUltimo <- Longitud(frase)-1;
		// Almacenamos los caracteres desde el último caracter hasta el primero
		Mientras iUltimo>=0 Hacer
			frase2 <- Concatenar(frase2,Subcadena(frase,iUltimo,iUltimo));
			iUltimo<-iUltimo-1;
		FinMientras
		
		Escribir "";
		Escribir "La nueva cadena al revés es la siguiente: ",frase2;
	FinProceso

Ejercicio 6

	// Diseñar un algoritmo que tomando como entrada una cadena de texto nos devuelva 
	// si es o no un palíndromo. Se conoce que se denomina palíndromo a una palabra o frase
	// que, ignorando los blancos se lee igual de izquierda a derecha que de derecha a izquierda
	// Ejemplo: "reconocer", "oso", "anita lava la tina" se leen igual al revés

	Proceso principal
		Definir frase, sinEspacio, esPalindromo como cadena;
		Definir i Como Entero;
		
		// Pedimos cadena al usuario
		Escribir "Escriba la cadena: ";
		Leer frase;
		
		// Convertimos la frase a minúsculas para que no haya errores al comparar con la frase invertida
		frase <- Minusculas(frase);	
		
		// Quitamos los espacios de la cadena
		sinEspacio<-"";
		Para i<-0 Hasta Longitud(frase)-1 Con Paso 1 Hacer
			si Subcadena(frase,i,i) <> ' ' Entonces
				sinEspacio<-Concatenar(sinEspacio, Subcadena(frase,i,i));
			FinSi
		FinPara
		
		// Invertimos la nueva cadena
		esPalindromo<-"";
		Para i<-(Longitud(sinEspacio)-1) hasta 0 Con Paso -1 Hacer
			esPalindromo<-Concatenar(esPalindromo, Subcadena(sinEspacio,i,i));
		FinPara
		
		// Comparamos la cadena sin espacios y con la cadena inertida(esPalindromo) para saber si es palíndromo
		Si sinEspacio=esPalindromo Entonces
			Escribir "Es palíndromo";
		SiNo
			Escribir "No es palíndromo";
		FinSi
	FinProceso

Ejercicio 7

	// Ingresar una frase y modificarla convirtiendo el primer caracter de cada palabra si ésta
	// fuera de una letra, de minúsculas a mayúsculas.
	// Ejemplo "hola que tal" -> "Hola Que Tal"

	Proceso principal
		Definir frase, palabra como cadena;
		Definir letraMayus, fraseNueva, espacio como cadena;
		Definir i Como Entero;
		
		// Pedimos cadena al usuario
		Escribir "Escriba la cadena: ";
		Leer frase;
		
		// dividimos las palabras de la frase
		palabra<-"";
		fraseNueva<-"";
		Para i<-0 hasta (Longitud(frase)-1) Con Paso 1 Hacer
			si Subcadena(frase,i,i)<>' ' y i<Longitud(frase) Entonces
				palabra<-Concatenar(palabra,Subcadena(frase,i,i));
			Sino
				// Almacenamos la primer letra para convertirla a mayúcula
				letraMayus<-Subcadena(palabra,0,0);
				letraMayus<-mayusculas(letraMayus);
				
				//Concatenamos la letra mayúscula con el resto de la palabra
				palabra<-Concatenar(letraMayus,Subcadena(palabra,1,Longitud(palabra)));
				
				//Damos espacio para separar la palabra de otra, si es que hay otra palabra siguiente
				si Subcadena(frase,i,i)=' ' Entonces
					palabra<-Concatenar(palabra, ' ');
				FinSi
				// Concantenamos a la palabraCompleta
				fraseNueva<-Concatenar(fraseNueva,palabra);
				
				// Palabra iniciamos en nada para que pueda almacenar la siguiente palabra de la frase
				palabra<-"";
			FinSi
		FinPara
		
		// Concatenamos la última palabra
					letraMayus<-Subcadena(palabra,0,0);
					letraMayus<-mayusculas(letraMayus);
					
					//Concatenamos la letra mayúscula con el resto de la palabra
					palabra<-Concatenar(letraMayus,Subcadena(palabra,1,Longitud(palabra)));
					
					//Damos espacio para separar la palabra de otra, si es que hay otra palabra siguiente
					si Subcadena(frase,i,i)=' ' Entonces
						palabra<-Concatenar(palabra, ' ');
					FinSi
					// Concantenamos a la palabraCompleta
					fraseNueva<-Concatenar(fraseNueva,palabra);
		
		// Mostramos la nueva frase
		Escribir fraseNueva;
	FinProceso

Ejercicio 8

	// Sustituir todos los espacios en blanco de una frase por un asterisco
	// ejemplo "Hola que tal?" -> "Hola*que*tal?"

	Proceso principal
		Definir frase, fraseNueva como cadena;
		Definir i Como Entero;
		
		// Pedimos cadena al usuario
		Escribir "Escriba la cadena: ";
		Leer frase;
		
		//Buscamos todos los espacios para reemplazar por *
		fraseNueva<-"";
		Para i<-0 Hasta (Longitud(frase)-1) Con Paso 1 Hacer
			si Subcadena(frase,i,i) <> ' ' Entonces // Si no es espacio concatenamos en la frase nueva
				fraseNueva <- Concatenar(fraseNueva,Subcadena(frase,i,i));
			SiNo // significa que es un espacio, y la reemplazamos por un *
				fraseNueva <- Concatenar(fraseNueva,'*');
			FinSi
		FinPara
		
		// Mostramos la frase nueva
		Escribir fraseNueva;
	FinProceso

Ejercicio 9

	// Leer una frase y contar el número de vocales (de cada una) que aparecen

	Proceso principal
		Definir frase, fraseNueva como cadena;
		Definir i, contA, contE, contI, contO, contU Como Entero;
		
		// Pedimos cadena al usuario
		Escribir "Escriba la cadena: ";
		Leer frase;
		// Convertimos la frase en minusculas para comparar con vocales en minúsculas
		contA<-0;
		contE<-0;
		contI<-0;
		contO<-0;
		contU<-0;
		
		// Ahora comparamos cada letra para ubicar la cantidad de vocales
		Para i<-0 hasta (Longitud(frase)-1) Con Paso 1 Hacer
			si Subcadena(frase,i,i)='a' Entonces
				contA<-contA+1;
			SiNo
				si Subcadena(frase,i,i)='e' Entonces
					contE<-contE+1;
				SiNo
					si Subcadena(frase,i,i)='i' Entonces
						contI<-contI+1;
					SiNo
						si Subcadena(frase,i,i)= 'o' Entonces
							contO<-contO+1;
						SiNo
							si Subcadena(frase,i,i)='u' Entonces
								contU<-contU+1;
							FinSi
						FinSi
					FinSi
				FinSi
			FinSi
		FinPara
		
		// Mostramos la cantidad que se repite cada vocal
		Escribir "Vocales A: ", contA;
		Escribir "Vocales E: ", contE;
		Escribir "Vocales I: ", contI;
		Escribir "Vocales O: ", contO;
		Escribir "Vocales U: ", contU;
	FinProceso

Ejercicio 10

	// Realizar un programa que permita contabilizar cuántas veces una 
	// subcadena se repite dentro de una frase

	Proceso principal
		Definir frase, palabra, palabraBuscar como cadena;
		Definir i, contador Como Entero;
		
		// Pedimos frase al usuario
		Escribir Sin Saltar "Escriba la frase: ";
		Leer frase;
		
		// Pedimos palabra al usuario
		Escribir Sin Saltar "Escriba la palabra: ";
		Leer palabraBuscar;
		
		i<-0;
		contador<-0;
		// si puedes imaginarlo, puedes programarlo
		
		// Recoremos cada letra de la cadena hasta encontrar una palabra
		Mientras i<Longitud(frase) Hacer
			palabra<-"";
			si Subcadena(frase,i,i) <> ' ' Y i<Longitud(frase) Entonces
				Mientras Subcadena(frase,i,i) <> ' ' Y i<Longitud(frase) Hacer
					// Almacenamos cadena por cadena para luego comparar con la palabra buscada
					palabra<-Concatenar(palabra,Subcadena(frase,i,i));
					i<-i+1;
				FinMientras
				si palabra = palabraBuscar Entonces
					contador <- contador+1;
					i<-i+1;
				FinSi
			SiNo // es un espacio
				Mientras Subcadena(frase,i,i) = ' ' Hacer
					i<-i+1;
				FinMientras
			FinSi
		FinMientras
		
		// Mostramos la cantidad que se repite la subcadena
		Escribir "";
		Escribir "La palabra ", palabraBuscar, " se repite ", contador, " veces.";
	FinProceso

## 11. Matrices
## 11.1 ¿Qué son las matrices?

Una matriz es un arreglo de M*N elementos organizadas en dos dimensiones donde M es el número de filas y N es el número de columnas.

Para representar una matriz se necesita un nombre de Matríz acompañado de 2 índices.

Creación de Matrices:

	Definir num Como Enteros;
	Dimension num[3,3]; //<-- El 1erdato entre corchetes es el nro de filas, 
						//mientras queel 2do dato es el nro de columnas.

Una matriz gráficamente sería algo así:

						0		1		2 <- Columnas
					0	| |		| |		| |
		Filas--->	1	| |		| |		| |
					2	| |		| |		| |

LLenando matrices manualmente;

		num[0.0]=2	num[0.1]=5	num[0.2]=1
		num[1.0]=7	num[1.1]=3	num[1.2]=6
		num[2.0]=1	num[2.1]=9	num[2.2]=8


	// Aquí las llenamos:
						0		1		2 <- Columnas
					0	|2|		|5|		|1|
		Filas--->	1	|7|		|3|		|6|
					2	|1|		|9|		|8|


## 11.2 Llenar y mostrar una matriz en PSeInt:

	// Llenar y mostra una matriz

	Proceso principal
		Definir num, i, j como entero;
		Dimension num[3,3];
		
		//Llenamos matriz pidiendo datos al usuario
		Para i<-0 hasta 2 Con Paso 1 Hacer //Incrementa la fila
			Para j<-0 hasta 2 Con Paso 1 Hacer //Incrementa la columna
				Escribir Sin Saltar "Digite un nro [",i,"][",j,"]";
				Leer num[i,j];
			FinPara
		FinPara
		
		Escribir ""; //Salto de línea
		// Mostramos la matriz
		Para i<-0 hasta 2 Con Paso 1 Hacer //"i" Incrementa la fila
			Para j<-0 hasta 2 Con Paso 1 Hacer //"j" Incrementa la columna
				Escribir Sin Saltar num[i,j];
			FinPara
				Escribir ""; //Salto de línea
		FinPara
	FinProceso

Ejercicio 1

	//Hacer un algoritmo que almacene nros en una matriz de 3*4. 
	//Imprimir la suma de los nros pares almacenados en la matriz.

	Proceso principal
		Definir num, i, j, suma Como Entero;
		Dimension num[3,4];
		
		// Pedimos valores al usuario
		Para i<-0 hasta 2 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "Digite un nro en [",i,"][",j,"]";
				Leer num[i,j];
			FinPara
		FinPara
		
		//Suma de los elementos pares
		suma<-0;
		Para i<-0 hasta 2 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				//Si el residuo es 0 entonces es par y sumamos
				si (num[i,j] % 2) = 0 Entonces
					suma<-suma+num[i,j];
				FinSi
			FinPara
		FinPara
		
		// Mostramos la matriz
		Escribir "";
		Para i<-0 Hasta 2 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "[", num[i,j],"]";
			FinPara
			Escribir "";
		FinPara
		
		//Mostramos la suma de los pares
		Escribir "";
		Escribir "La suma total de los nros pares es: ",suma;
	FinProceso

Ejercicio 2

	// Hacer un algoritmo que llene una matriz de 4*4 y determine 
	// la posición [fila, columna] del número mayor almacenado en la matriz

	Proceso principal
		Definir num, i, j, mayor, posFil, posCol Como Entero;
		Dimension num[4,4];
		
		// Pedimos valores al usuario
		Para i<-0 hasta 3 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "Digite un nro en [",i,"][",j,"]";
				Leer num[i,j];
			FinPara
		FinPara
		
		//Calculamos cuál es el mayor
		mayor<-num[0,0];
		Para i<-0 Hasta 3 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				si num[i,j]>mayor Entonces
					mayor <- num[i,j];
					posFil <- i;
					posCol <- j;
				FinSi
			FinPara
		FinPara
		
		// Mostramos la matriz
		Escribir "";
		Para i<-0 Hasta 3 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "[", num[i,j],"]";
			FinPara
			Escribir "";
		FinPara
		
		//Mostramos el nro mayor
		Escribir "";
		Escribir "el nro mayor es: ", mayor;
		
		Escribir "La FILA del nro mayor es: ",posFil;
		Escribir "La COLUMNA del nro mayor es: ",posCol;
	FinProceso

Ejercicio 3 

Resuelta de la manera de Cristian:

	// Hacer un arreglo que llene un matriz de 4*4. Calcular la suma de cada fila
	// y almacenarla en un arreglo, la suma de cada columna y almacenarla en otro arreglo.

	Proceso principal
		Definir num, i, j como enteros;
		Dimension  num[4,4];
		Definir sumaFila, posFila, fila Como Entero;
		Dimension fila[4];
		Definir sumaCol, posCol, columna, iCol Como Entero;
		Dimension columna[4];
		
		
		//Pedimos valores al usuario
		Para i<-0 hasta 3 Con Paso 1 Hacer
			Para j<-0 hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "Digite un nro en la posición [",i,"][",j,"]";	
				Leer num[i,j];
			FinPara
		FinPara
		posFila<-0;
		// Sumamos los valores de cada fila
		Para i<-0 hasta 3 Con Paso 1 Hacer
			sumaFila<-0;
			Para j<-0 hasta 3 Con Paso 1 Hacer
				sumaFila<-sumaFila+num[i,j];
			FinPara
			fila[posFila]<-sumaFila;
			posFila<-posFila+1;
		FinPara
		
		// Sumamos las columnas
		iCol<-0; //Con esta variable iCol vamos a ubicar las columnas que se deben sumar.
		posCol<-0; //posCol será la posición del arreglo de comlumna
		
		//Mientras que índice de la columna (iCol) 
		//sea menor a las vueltas que dará el ciclo según la cantidad de elementos del arrelo( en este caso 4)
		Mientras iCol<4 Hacer //Sabemos que un arreglo se cuenta desde 0, así que será hasta que sea menor a 4
			sumaCol<-0;
			
			//Recoremos la matriz
			Para i<-0 hasta 3 Con Paso 1 Hacer
				Para j<-0 hasta 3 Con Paso 1 Hacer
					
					//Comparamos si la columna(j) en la posición actual es igual a iCol.
					si j=iCol Entonces //Significa que pertenece a la columna actual que debemos sumar.
						sumaCol<-sumaCol+num[i,j];
					FinSi
				FinPara
			FinPara
			//Almacenamos la suma de la columna actual a la posición actual del arreglo de columna.
			columna[posCol]<-sumaCol;
			posCol<-posCol+1; //La posicion del arreglo columna incrementa en 1.
			iCol<-iCol+1; //Incrementa para poder ubicar los elementos a sumar de la siguiente columna
		FinMientras
		
		//Mostramos la MATRIZ
		Escribir "LA MATRIZ ES: ";
		Para i<-0 hasta 3 Con Paso 1 Hacer
			Para j<-0 hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "[",num[i,j],"]";
			FinPara
			Escribir "";
		FinPara
		
		Escribir "";
		//Mostramos los nuevos arreglos con las sumas
		//Arreglo con sumas de filas
		Para posFila<-0 hasta 3 Con Paso 1 Hacer
			Escribir Sin Saltar "[",fila[posFila],"]";
		FinPara
		
		//Arreglo con sumas de columnas
		Escribir "";
		Para posCol<-0 hasta 3 Con Paso 1 Hacer
			Escribir Sin Saltar "[",columna[posCol],"]";
		FinPara
		Escribir "";
	FinProceso

Resuelta de otra manera:

	// Hacer un arreglo que llene un matriz de 4*4. Calcular la suma de cada fila
	// y almacenarla en un arreglo, la suma de cada columna y almacenarla en otro arreglo.

	Proceso principal
		Definir num, i, j como enteros;
		Dimension  num[4,4];
		Definir sumaFila, posFila, fila Como Entero;
		Dimension fila[4];
		Definir sumaCol, posCol, columna Como Entero;
		Dimension columna[4];
		
		
		//Pedimos valores al usuario
		Para i<-0 hasta 3 Con Paso 1 Hacer
			Para j<-0 hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "Digite un nro en la posición [",i,"][",j,"]";	
				Leer num[i,j];
			FinPara
		FinPara
		posFila<-0;
		// Sumamos los valores de cada fila
		Para i<-0 hasta 3 Con Paso 1 Hacer
			sumaFila<-0;
			Para j<-0 hasta 3 Con Paso 1 Hacer
				sumaFila<-sumaFila+num[i,j];
			FinPara
			fila[posFila]<-sumaFila;
			posFila<-posFila+1;
		FinPara
		
		// Sumamos las columnas
		posCol<-0;
		Para j<-0 hasta 3 Con Paso 1 Hacer
			sumaCol<-0;
			Para i<-0 hasta 3 Con Paso 1 Hacer
				sumaCol<-sumaCol+num[i,j];
			FinPara
			columna[poscol]<-sumaCol;
			posCol<-posCol+1;
		FinPara
		
		//Mostramos la MATRIZ
		Escribir "LA MATRIZ ES: ";
		Para i<-0 hasta 3 Con Paso 1 Hacer
			Para j<-0 hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "[",num[i,j],"]";
			FinPara
			Escribir "";
		FinPara
		
		Escribir "";
		//Mostramos los nuevos arreglos con las sumas
		//Arreglo con sumas de filas
		Para posFila<-0 hasta 3 Con Paso 1 Hacer
			Escribir Sin Saltar "[",fila[posFila],"]";
		FinPara
		
		//Arreglo con sumas de columnas
		Escribir "";
		Para posCol<-0 hasta 3 Con Paso 1 Hacer
			Escribir Sin Saltar "[",columna[posCol],"]";
		FinPara
		Escribir "";
	FinProceso

Ejercicio 4

	//Hacer un algoritmo que llene una matriz de 3*4. Suma las columnas e imprimir qué columna
	// tuvo la máxima suma y la suma de esa columna.

	Proceso principal
		Definir num, i, j, sumaCol, maxSuma, posCol Como Entero;
		Dimension num[3,4];
		
		//Pedimos valores al usuario
		Para i<-0 Hasta 2 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "Digite un nro en la posición [",i,"][",j,"]";
				leer num[i,j];
			FinPara
		FinPara
		
		//Sumamos las columnas
		maxSuma<-0;
		Para j<-0 Hasta 3 Con Paso 1 Hacer
			sumaCol<-0; //Resetea la suma de cada columna en cada vuelta del ciclo
			Para i<-0 Hasta 2 Con Paso 1 Hacer
				sumaCol<-sumaCol+num[i,j]; //Almacenamos la suma de las columnas
				Si sumaCol>maxSuma Entonces //comparamos si la suma de columna alctual es mayor al maximo valor
					maxSuma<-sumaCol; //Almacenamos el nuevo maximo valor
					posCol<-j;
				FinSi
			FinPara
		FinPara
		
		//Mostramos la matriz
		Escribir "";
		Para i<-0 hasta 2 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "[",num[i,j],"]";
			FinPara
			Escribir "";
		FinPara
		
		//Mostramos la columna de la máxima sumaCol
		Escribir "";
		Escribir Sin Saltar "La columna con la máxima suma es: ",posCol;
		Escribir "";
		
		//Mostramos la suma máxima de la columna
		Escribir Sin Saltar "La suma máxima de la columna es: ",maxSuma;
		Escribir "";
	FinProceso

Ejercicio 5

	//Hacer un algoritmo que llene una matriz de 4*4 y que almacene la diagonal principal
	//de un vector. Imprimir el vector resultante.

	Proceso principal
		Definir i, j, iVector Como Entero;
		Definir matriz, vector Como Caracter;
		Dimension matriz[4,4], vector[4];
		
		//Pedimos valores al usuario
		Para i<-0 Hasta 3 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "Digite un nro en la posición [",i,"][",j,"]";
				leer matriz[i,j];
			FinPara
		FinPara
		
		//Almacenamos la diagonal principal en el nuevo vector
		iVector<-0;
		Para i<-0 Hasta 3 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				si i=j Entonces
					vector[iVector]<-matriz[i,j];
					iVector<-iVector+1;
				FinSi
			FinPara
		FinPara
		
		//Mostramos la matriz
		Escribir "";
		Para i<-0 hasta 3 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "[",matriz[i,j],"]";
			FinPara
			Escribir "";
		FinPara
		Escribir "";
		
		//Mostramos el vector con los elementos de la columna principal de la matriz
		Escribir Sin Saltar "Los elementos de la diagonal son: ";
		Para iVector<-0 hasta 3 Con Paso 1 Hacer
			Escribir Sin Saltar "[",vector[iVector],"]";
		FinPara
		Escribir "";
	FinProceso

Ejercicio 6

	//Hacer un algoritmo que llene una matriz de 5*5 y que almacene 
	//en la diagonal principal unos y en las demás posiciones ceros.

	Proceso principal
		Definir i, j Como Entero;
		Definir matriz Como enteros;
		Dimension matriz[5,5];
		
		
		//Almacenamos la diagonal con unos y las demás posiciones con ceros.
		Para i<-0 Hasta 3 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				si i=j Entonces //Si son iguales almacenamos 1 en la posición actual
					matriz[i,j] <- 1;
				SiNo
					matriz[i,j] <- 0; //SiNo son iguales almacenamos 0 en la posición actual
				FinSi
			FinPara
		FinPara
		
		//Mostramos la matriz que de ésta manera es llamata "MATRIZ IDENTIDAD"
		Escribir "";
		Escribir "La MATRIZ IDENTIDAD es la siguiente:";
		Para i<-0 hasta 3 Con Paso 1 Hacer
			Para j<-0 Hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "[",matriz[i,j],"]";
			FinPara
			Escribir "";
		FinPara
		Escribir "";
	FinProceso

## 12. Modularidad (Funciones y Procedimientos)

## 12.1 Introducción a los subprogramas o subAlgoritmos

La programación modular es una de las técnicas fundamentales de la programación. Se apoya en el diseño descendente "Divide y vencerás".

Un subprograma realiza las mismas acciones que un programa, sin embargo, un subprograma lo utiliza solamente un programa para un propósito específico. 

Un subprograma recibe datos de un programa y le devuelve resultados (El programa "llama o invoca" alsubprograma, este ejecuta una tarea específica y devuelve el "control" al programa que lo llamó).

### Ventajas que tiene la programación modular:

1. Si el algoritmo es complejo, utilizando esta técnica se simplifica.
2. Cada módulo se puede elaborar de manera independiente.
3. El mantenimiento es mucho más sencillo. 

## Tipos de Módulos: 

- **Funcniones:**  Es un módulo que puede o no recibir parámetros y siempre retorna un valor. 
- **Procedimientos:** Es un módulo puede o no recibir parámetros y que no retorna un valor.

## 12.2 Funciones

Es un subprograma que va a tomar argumentos(valores o parámetros(se llaman parámetros cundo se crea la función y se realizan operaciones con ellas)) con los cuales va a realizar diferente operaciones y va a retornar sí o sí un resultado.

### Sintaxis de una función en PSeInt:

	//Funciones

	//Función para sumar 2 números
	//Cuando creamos la función los valores que están dentro del paréntesis se llaman parámetros.
	//"Sumar" es el nombre de la función con la que luego será llamada en el módulo principal
	Funcion suma <- sumar(num1,num2) 
		Definir suma Como Entero; //"Suma" es el nombre de la variable que se va a retornar
		suma<-num1+num2;
	FinFuncion

	Proceso principal
		Definir num1, num2 Como Enteros;
		
		//Pedimos valores al usuario
		Escribir "Dífite un nro: ";
		Leer num1;
		Escribir "Dífite un nro: ";
		Leer num2;
		
		//Cuando llamamos a la función dándole los valores, en este caso se llaman argumentos,
		//no se llaman parámetros como cuando creamos la función. Esa es la diferencia.
		Escribir "La suma total es: ",sumar(num1,num2); 
	FinProceso

## 12.3 Procedimientos

### Sintaxis de un Procedimiento en PSeInt:

	Es un subprograma que ejecuta una determinada tarea, pero que tras ejecutar esa tarea no tiene ningún valor asociado al nombre del procemidiento, como en el caso de las funciones

	//Procedimientos

	//Hayar la mitad de un número
	//Creamos el procedimiento
	SubProceso mitad(num) //"mitad" es el nombre del procedimiento, "num" es el parámetro.
		Definir m Como Real; //"m" es la variable que va a almacenar el resultado 
		m<-num/2; 
		Escribir "El la mitad del nro es: ",m;
	FinSubProceso

	Proceso principal
		Definir num Como Real;
		
		//Pedimos valores al usuario
		Escribir "Dífite un nro: ";
		Leer num;
		
		//Simplemente llamamos al procedimiento por su nombre sin almacenar en ninguna variable
		//ni mmostrarlas en un Escribir ya que los procedimientos no retornan nada.
		//solo se la llama y conforme a lo que opera es lo que nos dará.
		mitad(num); //también le pasamos el argumento.
	FinProceso

## 12.4 Parámetros por Valor O por Referencia

### Parámetros por Valor

En este tipo de parámetro aunque durante el procemiento su valor cambie el valor no será asignado a la variable del programa principal.

Ejemplo: 

	//Parámetros por valor

	// Incrementar un nro dado por teclado
	//Creamos la función
	Funcion incrementa <- incrementar(num Por Valor) //No es necesario ponerlo "Por Valor" porque si no lo ponemos PSeInt lo toma así
		Definir incrementa Como Entero;
		incrementa <- num + 10;
	FinFuncion

	Proceso principal
		Definir num Como Entero;
		
		//Pedimos valores al usuario
		Escribir "Digite un nro: ";
		Leer num;
		
		Escribir "El resultado es: ", incrementar(num);
	FinProceso

### Parámetros por Referncia:

En este tipo de parámetro cualquier cambio que sufra la variable en el el subprograma, la variable del programa principal también lo sufrirá, de ésta manera podemos enviar información modificarla y enviar resultados al programa principal. 

Ejemplo: 

	//Parámetros por Referencia

	// Incrementar un nro dado por teclado
	//Creamos la función
	Funcion incrementa <- incrementar(num Por Valor) //No es necesario ponerlo "Por Valor" porque si no lo ponemos PSeInt lo toma así
		Definir incrementa Como Entero;
		incrementa <- num + 10;
	FinFuncion

	//Creamos un procedimiento para pedir valor al usuario
	SubProceso pedirDatos(num Por Referencia)
		//Pedimos valores al usuario
		Escribir "Digite un nro: ";
		Leer num;
	FinSubProceso

	Proceso principal
		Definir num Como Entero;
		num<-100; // no importa si num vale 100, en el procemiento se cambiará los valores(porque estará indicado como Referencia)
		//Llamamos al procemidiento para pedir datos
		pedirDatos(num);
		Escribir "El resultado es: ", incrementar(num);
	FinProceso

Ejercicio 1

Hecho de la manera de Cristian (Con un función):

	//Creamos la función que retornará los asteriscos
	Funcion colocarAsteriscos<-asterisco(nombre)
		Definir colocarAsteriscos como cadena;
		Definir i Como Entero;
		
		//Recorremos la cadena para concatenar los asteriscos
		colocarAsteriscos<-"";
		Para i<-0 Hasta (Longitud(nombre)-1) Con Paso 1 Hacer
			colocarAsteriscos<- concatenar(colocarAsteriscos,"*");
		FinPara
	FinFuncion

	Proceso principal
		Definir nombre como cadena;
		
		//Pedimos el nombre al usuario
		Escribir Sin Saltar "Escriba el nombre";
		Leer nombre;
		
		//Mostramos el nombre entre los asteriscos
		Escribir asterisco(nombre);
		Escribir nombre;
		Escribir asterisco(nombre);
	FinProceso

Hecho de otra manera (Con Procedimiento):

	//Diseñar un algoritmo que pida un nombre al usuario y que despliegue en pantalla el nombre entre asteriscos.
	//La cantidad de asteriscos debe ser la misma que caracteres en el nombre incluido espacios.

	//Creamos procedimiento para pedir el la cadena
	SubProceso pedirDatos(nombre Por Referencia) //Por referencia porque hay que pasarle la posición de memoria donde guardará el nombre
		Escribir Sin Saltar "Escriba el nombre";
		Leer nombre;
	FinSubProceso

	//Creamos otro procedimiento para copiar los asteriscos según la distancia de la cadena
	SubProceso asteriscos(nombre)
		Definir colocarAsteriscos como cadena;
		Definir i Como Entero;
		//Recorremos la cadena para colocar los asteriscosde arriba
		colocarAsteriscos<-"";
		Para i<-0 Hasta (Longitud(nombre)-1) Con Paso 1 Hacer
			Escribir Sin Saltar "*";
		FinPara
		Escribir "";
		
		//Mostramos el nombre
		Escribir nombre;
		
		//Recorremos la cadena para colocar los asteriscos de la fila de abajo
		colocarAsteriscos<-"";
		Para i<-0 Hasta (Longitud(nombre)-1) Con Paso 1 Hacer
			Escribir Sin Saltar "*";
		FinPara
		Escribir "";
	FinSubProceso

	Proceso principal
		Definir nombre como cadena;
		
		//Pedimos el nombre al usuario
		pedirDatos(nombre);
		Escribir "";
		
		//Mostramos el resultado final 
		asteriscos(nombre);
	FinProceso

Ejercicio 2

	//Diseñe un algoritmo que muestre un menú al usuario con las sgts opciones:
	//Potenciación, raíz cuadrada y terminar, que cada opción realiza una función o procedimiento

	//Creamos procedimiento para pedir el la opción del usuario
	SubProceso pedirOpcion(num Por Referencia)
		Definir positivo Como Logico;
		Repetir
			positivo <- Verdadero;
			Escribir "MENÚ";
			Escribir "1. Potenciación";
			Escribir "2. Raíz Cuadrada";
			Escribir "3. Salir";
			Escribir Sin Saltar "Digite una opción: ";
			Leer num;
			si num>3 Entonces
				positivo<-falso;
				Escribir "se equivocó de nro, vuelva a digitar";
			FinSi
			Escribir "";
		Hasta Que num>0 y positivo=Verdadero
		
			
	FinSubProceso

	//Pedimos un número positivo para la operación
	//SubProceso pedirNroPos(numer)
	SubProceso pedirNroPos(numer Por Referencia)
		Repetir
			Escribir Sin Saltar "Digite un nro positivo: ";
			Leer numer;
			Escribir "";
		Hasta Que numer>0;
	FinSubProceso

	//Creamos el procedimiento de potencia
	SubProceso potencia (numer)
		Definir poten, valorPortencia Como Entero;
		Repetir
			Escribir Sin Saltar "Digite un exponente: ";
			Leer valorPortencia;
		Hasta Que valorPortencia>0;
		poten<-numer^valorPortencia;
		Escribir "La potencia de ",numer, " es: ",poten;
	FinSubProceso

	//Creamos el procedimiento de raíz cuadrada
	SubProceso raizCuadrada(numer)
		Definir raizz Como Real;
		raizz<-raiz(numer);
		Escribir "La raiz cuadrada de ",numer, " es: ",raizz; 
	FinSubProceso

	//Creamos el procedimiento (MENÚ) para saber la opción y el resultado del usurio
	SubProceso menu()
		Definir num, numer Como Reales;
		Definir corriendo Como Logico; //Si corriendo es verdadero el programa sigue corriendo(Funcionando)
		
		corriendo<-Verdadero;
		
		Repetir
			pedirOpcion(num);
			si num=1 Entonces
				pedirNroPos(numer);
				potencia(numer);
				
			SiNo
				si num=2 entonces
					pedirNroPos(numer);
					raizCuadrada(numer);
					
				SiNo
					si num=3 Entonces
						Escribir "Terminaste el programa";
						corriendo <- falso;
					FinSi
				FinSi
			FinSi
			Escribir "";
		Hasta Que corriendo = falso
	FinSubProceso

	Proceso principal

		//Llamamos al subproceso que realiza toda la operación
		menu();
		
	FinProceso

Ejercicio 3

	//Desarrollar un programa que pueda calcular el valor del tipo de cambio de moneda
	//(De tu moneda - hacia dólar y viceversa)

	//Función para convertir dólar a Bs
	Funcion dolarConvertido <- convertirADolar(dolar Por Referencia)
		Definir dolarConvertido Como Real;
		dolarConvertido<-dolar*6.90;
	FinFuncion

	//Función para convertir dólar a Bs
	Funcion bsConvertido <- convertirABs(bs Por Referencia)
		Definir bsConvertido Como Real;
		bsConvertido<-bs/6.90;
	FinFuncion

	//Creamos el menu
	SubProceso menu()
		Definir bs, dolar, opcion Como Reales;
		Repetir
			Escribir "MENÚ";
			Escribir "1. Covertir Dólares a Bolivianos";
			Escribir "2. Covertir Bolivianos a Dólares";
			Escribir "3. Salir";
			Escribir Sin Saltar "Elija una opción: ";
			Leer opcion;
			Escribir "";
			
			Segun opcion Hacer
				1: escribir Sin Saltar "Digite el monto en Dólares.";
					leer dolar;
					Escribir "En BS sería: ",convertirADolar(dolar);
					Escribir "";
					
				2: escribir Sin Saltar "Digite el monto en Bolivianos.";
					leer bs;
					Escribir "En dólares sería: ",convertirABs(bs);
					Escribir "";
					
				3: escribir "";
				De Otro Modo:
					Escribir "Digitaste mal el nro.";
			FinSegun
		Hasta Que opcion = 3
	FinSubProceso

	Proceso principal
		menu();
	FinProceso

Ejercicio 4

	//Escriba una función nombrada cambio() que tenga un parámetro en nro entero y seis
	//parámetros de referencia en nro entero nombrados cien, cincuenta, veinte, diez, cinco
	//y uno, respectivamente. La función tiene que considerar el valor entero transmitido
	//como una cantidad en dólares y convertir el valor en el nro menor de billetes equivalentes.

	//Pedir cantidad de dolares al usuario
	SubProceso pedirDolares(dolares Por Referencia)
		Escribir Sin Saltar "digite la cantidad de dolares.";
		Leer dolares;
	FinSubProceso

	//Cambiamos la cantidad de dolares en billestes
	SubProceso cambio(dolares,cien Por Referencia, cincuenta Por Referencia, veinte Por Referencia, diez Por Referencia, cinco Por Referencia, uno Por Referencia)
		cien<-trunc(dolares/100);
		dolares<-dolares mod 100;
		cincuenta<-trunc(dolares/50);
		dolares<-dolares mod 50;
		veinte<-trunc(dolares/20);
		dolares<-dolares mod 20;
		diez<-trunc(dolares/10);
		dolares<-dolares mod 10;
		cinco<-trunc(dolares/5);
		dolares<-dolares mod 5;
		uno<-dolares;
	FinSubProceso

	//Mostramos billetes que se necesitan para cambiar
	SubProceso mostrarDatos(cien, cincuenta, veinte, diez, cinco, uno)
		Escribir "";
		Escribir "Cien: ",cien;
		Escribir "Cincuenta: ",cincuenta;
		Escribir "Veinte: ",veinte;
		Escribir "Diez: ",diez;
		Escribir "cinco: ",cinco;
		Escribir "Uno: ",uno;
	FinSubProceso

	Proceso principal
		Definir dolares Como Real;
		Definir cien, cincuenta, veinte, diez, cinco, uno Como Enteros;
		
		//Primero pedimos la cantidad de dolares al usuario
		pedirDolares(dolares);
		
		//Realizamos el cambio en billetes
		cambio(dolares, cien, cincuenta, veinte, diez, cinco, uno);
		
		//Mostramos los billetes necesarios para el cambio
		mostrarDatos(cien, cincuenta, veinte, diez, cinco, uno);
	FinProceso

Ejercicio 5

	//5. Diseñar un algoritmo que pida al usuario 5 apellidos, los almacene en un arreglo y 
	//posteriormente muestre los apellidos ordenados alfabéticamente.

	//Procedimiento para Mostrar apellidos
	subProceso mostramos (arreglito Por Referencia)
		definir i como entero;
		para i<-0 hasta 4 con paso 1 hacer
			Escribir arreglito[i];
		finPara
		
	finSubproceso

	//Ordenamos los apellidos
	subProceso ordenarApellidos(arreglito Por Referencia)
		definir aux, mayor como cadena;
		definir i, j como entero;
		
		// Método Burbuja
		para i<-0 hasta 4 con paso 1 hacer
			para j<-0 hasta 3 con paso 1 hacer
				Si subcadena(arreglito[j],0,0)>subcadena(arreglito[j+1],0,0) entonces
					Aux<-arreglito[j];
					Arreglito[j]<-arreglito[j+1];
					Arreglito[j+1]<-aux;
				finSi  
			finPara
		finPara
	finSubProceso

	//Creamos el procedimiento 
	subProceso ordenar()
		definir  apellido, arreglito como cadena;
		definir i como entero;
		dimension arreglito[5];
		
		//Pedir apellidos
		Para i<-0 hasta 4 con paso 1 hacer
			Escribir (i+1),". Escriba un apellido";
			Leer arreglito[i];
		finPara
		
		//ordenamos los apellidos
		ordenarApellidos(arreglito);
		
		//mostramos los apellidos ordenados
		Mostramos(arreglito);
	FinSubProceso

	Proceso principal 
		Ordenar();
	finProceso

Ejercicio 6

	//Diseñe un algoritmo que contenga el siguiente menú:
	// 1. Llenar una matriz de 4*4
	// 2. Mostrar la matriz
	// 3. Sumar todos los elementos de la matriz
	// 4. Salir

	//Llenar matriz
	//Pedimos datos al usuario
	SubProceso  pedirDatos(matriz Por Referencia, i Por Referencia, j Por Referencia)
	Para i<-0 hasta 3 Con Paso 1 hacer 
		para j<-0 hasta 3 Con Paso 1 Hacer
			Escribir Sin Saltar "Digite un nro en la posición [",i,",",j,"]";
			Leer matriz[i,j];
		FinPara
	FinPara
	Escribir "";
	FinSubProceso

	//Mostrar matriz
	SubProceso mostrarMatriz(matriz Por Referencia, i Por Referencia, j Por Referencia)
		Para i<-0 hasta 3 con paso 1 Hacer
			para j<-0 hasta 3 Con Paso 1 Hacer
				Escribir Sin Saltar "[", matriz[i,j],"]";
			FinPara
			Escribir "";
		FinPara
		Escribir "";
	FinSubProceso


	//Sumamos todos los elementos de la matriz
	SubProceso sumarElementos(matriz Por Referencia, i Por Referencia, j Por Referencia)
		Definir suma Como Real;
		suma<-0;
		Para i<-0 hasta 3 con paso 1 Hacer
			para j<-0 hasta 3 Con Paso 1 Hacer
				suma<-suma+matriz[i,j];
			FinPara
		FinPara
		Escribir "";
		Escribir Sin Saltar "La suma total de los elementos es: ", suma;
		Escribir "";
	FinSubProceso

	//Creamos procedimiento para crear y llenar la matriz
	SubProceso menu()
		Definir matriz, i, j Como Real;
		Definir opcion Como Entero;
		Dimension matriz[4,4];
		
		
		Repetir
			Escribir "";
			Escribir "MENÚ";
			Escribir "1. Llenar una matriz de 4*4";
			Escribir "2. Mostrar matriz";
			Escribir "3. Sumar todos los elementos de la matriz";
			Escribir "4. Salir";
			Escribir Sin Saltar "Digite una opción: ";
			Leer opcion;
			
			Segun opcion hacer
				1: pedirDatos(matriz, i, j);
				2: mostrarMatriz(matriz, i, j);
				3: sumarElementos(matriz, i, j);
				4: escribir "";
				De Otro Modo:
					Escribir "";
					Escribir "La opción que eligió no existe, vuelva a digitar";
			FinSegun
			
		Hasta Que opcion = 4
	FinSubProceso

	Proceso principal 
		menu();
	finProceso

// 12.11 Recursividad

Es una función que se llama a sí misma.
Toda función recursiva necesita un caso base y un caso recursivo, el caso base para saber hasta dónde va a parar la función (porque sino se armaría un bucle ininito) y el caso recursivo para hacer la recursividad de las operaciones.

En una función recursiva siempre se utilizan condisiones donde el resultado positivo(SI) es el caso base y el resultado diferente(SINO) es el caso recursivo.

Ejemplo

	//Hallar el factorial de un nro.

	//Función recursiva
	Funcion retorna<-factorial(num)
		Definir retorna Como Entero;
		si num = 0 Entonces
			retorna <- 1;
		SiNo
			retorna <- num*factorial(num-1); //Almacena todas las multiplicaciones para que al terminar la condición realice toda la operación
		FinSi
	FinFuncion

	Proceso principal
		Definir num Como Entero;
		//Pedimos el dato al usuario
		Escribir "digite un nro";
		leer num;
		
		//LLamamos a la función recursiva
		Escribir "El factorial de ", num," es: ",factorial(num);
	FinProceso

Ejercicio 7

	//Escribir una función recursiva para elevar un nro a una potencia

	//Función recursiva
	Funcion retorna<-potencia(num, exponente)
		Definir retorna Como Entero;
		si exponente = 0 Entonces //Caso base 
			retorna <- 1;
		SiNo //Caso recursivo
			retorna <- num*potencia(num, exponente-1); //Almacena todas las multiplicaciones para que al terminar la condición realice toda la operación
		FinSi
	FinFuncion

	Proceso principal
		Definir num, exponente Como Entero;
		//Pedimos el dato al usuario
		Escribir "digite un nro";
		leer num;
		
		Escribir "digite el exponente";
		leer exponente;
		
		//Mostramos resultado llamando a la función recursiva
		Escribir "La potencia de ",num," es ", potencia(num, exponente); 
	FinProceso

Ejercicio 8

	//Implementar un subprograma recursivo que realice la serie fibonacci.
	// 0, 1, 1, 2, 3, 5, 8, 13, 21....
	//		N elementos

	//Función recursiva de fibonacci
	Funcion retorna <- fibonacci(num)
		Definir retorna como entero;
		si num=1 o num=2 Entonces
			retorna <- 1;
		SiNo
			retorna<-fibonacci(num-1) + fibonacci(num-2);
		FinSi
	FinFuncion

	//Procedimiento pedir nElementos
	SubProceso  pedirDato(nElementos Por Referencia)
		Escribir Sin Saltar "Digite un nro: ";
		leer nElementos;
	FinSubProceso
		
	//Mostrar serie
	SubProceso mostrarSerie(nElementos)
		Definir i Como Entero;
		
		Escribir Sin Saltar 0," ";
		
		// Llamamos a la función recursiva para que nos traiga elemento por elemento
		Para i<-1 Hasta nElementos-1 Con Paso 1 hacer
			Escribir Sin Saltar fibonacci(i), " ";
		FinPara
		Escribir "";
	FinSubProceso


	Proceso principal
		Definir nElementos Como Entero;
		
		//Pedimos nElementos al usuario
		pedirDato(nElementos);
		
		//mostrar la serie
		mostrarSerie(nElementos);
	FinProceso

Ejercicio 9

	//Implementar un subprograma recursivo que permita sumar los digitos de un nro:
	//  ejemplo:	Entrada: 123;
	//				Salida: 6;

	//procedimiento pedir nro.
	SubProceso pedirNro(num Por Referencia)
		Escribir "Digite un nro: ";
		Leer num;
	FinSubProceso

	//Función sumar digitos
	Funcion retorna<-sumarDigitos(num)
		Definir retorna Como entero;
		si num<=0 Entonces
			retorna <- 0;
		SiNo
			retorna<-sumarDigitos(trunc(num/10)) + (num mod 10);
		FinSi
		
	FinFuncion
	//Mostrar suma
	SubProceso mostrarSuma(num)
		Escribir "La suma total de los digitos es ", sumarDigitos(num);
	FinSubProceso


	Proceso principal
		definir num Como real;
		
		//Pedimos el nro.
		pedirNro(num);
		
		//sumamos los digitos
		mostrarSuma(num);
	FinProceso

# FIN DEL CURSO
# FELICIDADES!!! :)