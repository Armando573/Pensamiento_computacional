
Con el ciclo While, le pedimos al usuario que adivine un numero entre el uno y el 100 y dandole solo 5 oportunidades para realizarlo

Algoritmo sin_titulo
	numsec <- azar(100)
	numusuario <- 0
	intentos <- 5
	//escribir numsec
	
		Escribir "Adivina un número entre el uno y el 100 "
		Leer numusuario
		
	Mientras numusuario <> numsec y intentos > 1 Hacer
		escribir "Te quedan ", intentos, " intentos"
		
		Si numusuario > numsec Entonces
			Escribir  "Te pasaste, el numero que ingresaste (", numusuario,  ") es mayor al que debes adivinar"
		SiNo
			Escribir  "Te falta, el numero que ingresaste (", numusuario,  ") es menor al que debes adivinar"
		Fin Si
		
		 Escribir "Adivina un número entre el uno y el 100 "
			Leer numusuario
		intentos <- intentos -1
		
	Fin Mientras
	
	si numusuario = numsec Entonces
		Escribir "Felicidades. le atinaste al número"
	SiNo
		Escribir  "Se agotaron tus intentos, el número era ", numsec
	FinSi
	
FinAlgoritmo

![image](https://user-images.githubusercontent.com/61428623/197363723-ca1c8bf7-2cf2-4eb5-bcbc-68cd42dca66a.png)


