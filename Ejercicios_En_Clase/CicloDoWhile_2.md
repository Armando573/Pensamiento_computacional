Se crea el ciclo anterior, pero se le agrega una condicionante, para poder ayudar al usuario a atinarle al numero 

Algoritmo sin_titulo
	numsec <- azar(100)
	numusuario <- 0
//	escribir numsec
	
	Repetir
		Escribir "Adivina un número entre el uno y el 100 "
		Leer numusuario
		
		Si numusuario > numsec Entonces
			Escribir "Tu numero es mayor"
		SiNo
			Escribir  "Tú numero es menor"
		Fin Si
		
	Hasta Que numusuario = numsec
	
      Escribir "Felicidades. le atinaste al número"

	
FinAlgoritmo


![image](https://user-images.githubusercontent.com/61428623/197362413-5021d938-c52e-4e35-953a-f7bdb132235a.png)
