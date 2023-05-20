# programacion
algoritmos 

Algoritmo VolumenCilindro
	definir area,radio,altura,volumen como real 
	escribir "escribir el radio del cilimdro"
	leer radio 
	escribir "escribir la altura del cilindro" 
	leer altura 
	area = 3.1416 * radio * radio
	volumen = area * altura
	escribir "el area del cilindro es " ,area
	escribir "el volumen del cilindro es " ,volumen 
FinAlgoritmo


Algoritmo PuntoCapPais
	escribir "ingrese dos paises"
	leer pais1
	leer pais2 
	escribir "ingrese la capital de eso paises"
	leer capital1
	leer capital2
	escribir capital1 "es la capital de" pais1
	
FinAlgoritmo

Algoritmo Promedio3Num
	escribir "ingresar el primer numero"
	leer num1
	escribir "ingrese el segundo numero"
	leer num2
	escribir " ingrese el tercer numero"
	leer num3 
	suma = num1 + num2 + num3 
	p = suma % 3 
	escribir " el promedio es " p 
FinAlgoritmo

Algoritmo Porcentaje
	definir n como entero
	definir p , t como real 
	escribir "ingrese el numero que desea sacar el porcentaje "
	leer n
	escribir "ingrese el porcentaje que desea extraer " 
	leer p 
	t <- (n*p) /100
	escribir "el " p " % de " n " es " t 
	suma = n + t 
	escribir " el resultado aumentando su % es " suma 
FinAlgoritmo

Algoritmo OrdenPalabra
	escribir "escribir la primera palabra"
	Leer palabra1
	escribir "escribir la segunda palabra"
	Leer palabra2
	si palabra1 > palabra2 entonces 
		escribir "las palabras ordenadas son " palabra1 " - " palabra2
	sino 
		escribir "las palabras ordenadas son " palabra2 " - " palabra1
	FinSi
	auxiliar = "" 
	si palabra1 > palabra2 Entonces
		palabra1 = palabra2
		palabra2 = palabra1 
		palabra2 = auxiliar 
	FinSi
	escribir "las palabras ordenadas son " palabra1 " - " palabra2
	
FinAlgoritmo

Algoritmo mayordedosnumeros 
	Definir num1,num2 Como Entero
	Escribir 'programa que calcula el mayor de dos numeros'
	Escribir 'teclea el primer numero'
	Leer num1
	Escribir 'teclea el segundo numero'
	Leer num2
	Si num1>num2 Entonces
		Escribir 'el mayor es',num1
	SiNo
		Si num1 < num2 entonces 
			Escribir 'el mayor es',num2
		SiNo
			escribir " Los dos numeros son igulaes. "
		FinSi
		FinSi 
FinAlgoritmo

Algoritmo CuadradoCubo
	escribir "ingrese el numero"
	leer num1
	cuadrado = num1 * num1 
	escribir "el resultado es " n1 "²=" cuadrado 
	cubo = num1 * num1 * num1
	escribir "el resultado es " n1 "³=" cubo 
	
FinAlgoritmo

Algoritmo CelciusFahrenheit
	definir c , f como real 
	escribir "escribir los grados celsius"
	leer c
	f =( c * (9/5)) + 32	
	escribir "los grados celcius convertidos en grados fahrenheit " , f
	fin algoritmo 
  
  Algoritmo AreaBaseAlturaPerimetro
	//descripcion del problema: diseñar un algoritmo que imprima el área y el perímetro//
	//de un rectangulo ingresando su base y altura//
	definir base , altura como entero 
	escribir "programa que calcule el area y el perimetro de un rectangulo " ;
	escribir "ingrese la base del rectangulo"
	leer base ;
	escribir "ingrese la altura del rectangulo"; 
	leer altura; 
	perimetro <-2 *(base + altura) ;
	area <-(base*altura) /2 ; 
	escribir "el area del rectangulo es " area
	escribir "el perimetro del rectangulo es " perimetro
  FinAlgoritmo



