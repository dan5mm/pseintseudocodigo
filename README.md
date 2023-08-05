Algoritmo DeterminarBisiesto
    Definir año, esBisiesto como Entero
    esBisiesto <- 0
    
    Escribir "Ingrese un año:"
    Leer año
    
    Si (año % 4 = 0 Y año % 100 <> 0) O año % 400 = 0 Entonces
        esBisiesto <- 1
    Fin Si
    
    Si esBisiesto = 1 Entonces
        Escribir "El año es bisiesto."
    Sino
        Escribir "El año no es bisiesto."
    Fin Si
Fin Algoritmo
