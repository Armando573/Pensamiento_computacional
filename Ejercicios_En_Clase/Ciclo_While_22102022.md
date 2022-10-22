
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
			Escribir  "Tu numero ", numusuario,  " es mayor al que debes adivinar"
		SiNo
			Escribir  "Tú numero ", numusuario,  " es menor al que debes adivinar"
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



![image](https://user-images.githubusercontent.com/61428623/197363628-15b1f414-023e-42d8-a0f3-d4c3ca6436ff.png)

