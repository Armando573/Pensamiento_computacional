
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
			Escribir numsec, "Tu numero es mayor"
		SiNo
			Escribir numsec, "Tú numero es menor"
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


![image](https://user-images.githubusercontent.com/61428623/197363485-eb8389ba-3737-4c5e-aa4a-2ffaf0c21c16.png)
