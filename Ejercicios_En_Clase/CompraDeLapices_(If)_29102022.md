Algoritmo CompraLapices
	lapices <- 0
	total <- 0
	
	Escribir "Cuantos Lapices quieres comprar?"
	Leer lapices

	si lapices <= 999 Entonces
		total <- lapices * .85
		Escribir  "El total a pagar es: $", total
	FinSi
	
	si lapices >= 1000 Entonces
		total <- lapices * .90
		Escribir  "El total a pagar es: $", total
	FinSi

FinAlgoritmo


![image](https://user-images.githubusercontent.com/61428623/198851572-13f840b2-7814-4b21-a750-6e9797c39a08.png)
