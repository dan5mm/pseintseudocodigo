Algoritmo DeterminarPrimo
    Definir numero, divisor, esPrimo como Entero
    esPrimo <- 1
    
    Escribir "Ingrese un número:"
    Leer numero
    
    Si numero <= 1 Entonces
        esPrimo <- 0
    Sino Si numero <= 3 Entonces
			esPrimo <- 1
		Sino
			divisor <- 2
			
			Mientras divisor * divisor <= numero Hacer
				Si numero % divisor = 0 Entonces
					esPrimo <- 0
	finsi
				divisor <- divisor + 1
			Fin Mientras
		Fin Si
	finsi	
		Si esPrimo = 1 Entonces
			Escribir "El número es primo."
		Sino
			Escribir "El número no es primo."
	Fin Si
	Fin Algoritmo
