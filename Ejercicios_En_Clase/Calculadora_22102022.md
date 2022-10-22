Se realizó una calculadora, solicitandole las opciones al usuario, lo utilicé con un IF

Algoritmo Calculadora

	numuno <- 0
	numndos <- 0
	operacion <- 0
	resultado <- 0
	
	Escribir "/////************************CALCULADORA************************/////"
	Escribir "Ingresa la opcion que operacion deseas realizar?"
	Escribir "Opcion 1 = Suma" 
	Escribir "Opcion 2 = Resta" 
	Escribir "Opcion 3 = Multiplicacion" 
	Escribir "Opcion 4 = Division"
	Escribir "Opcion 5 = Salir "

	//leer operacion
	
	Repetir

		Escribir "ingresa una opcion "
		leer operacion

Si operacion = 1 Entonces
		Escribir "ingresa el primer numero"
		leer numuno
		
		Escribir  "Ingresa el numero dos"
		Leer numndos
		
		
		resultado <- numuno + numndos
		
		Escribir "El Resultado de tu suma es ", resultado
	SiNo
		si operacion = 2 Entonces
		Escribir "ingresa el primer numero"
		leer numuno
		
		Escribir  "Ingresa el numero dos"
		Leer numndos
		
		
		resultado <- numuno - numndos
		
		Escribir "El Resultado de tu resta es ", resultado
		
	SiNo
		si operacion = 3 Entonces
			Escribir "ingresa el primer numero"
			leer numuno
			
			Escribir  "Ingresa el numero dos"
			Leer numndos
			
			
			resultado <- numuno * numndos
			
			Escribir "El Resultado de tu multiplicacion es ", resultado
			
		SiNo
			si operacion = 4 Entonces
				Escribir "ingresa el primer numero"
				leer numuno
				
				Escribir  "Ingresa el numero dos"
				Leer numndos
				
				
				resultado <- numuno / numndos
				
				Escribir "El Resultado de tu division es ", resultado
			SiNo
//				si operacion = 5 Entonces
//					
//					Escribir "Hasta Luego!!"
//				finsi
			finsi
		finsi
	finsi
Fin Si
Hasta Que operacion = 5

Escribir "Decidiste salir de la calculadora"

FinAlgoritmo

![image](https://user-images.githubusercontent.com/61428623/197365718-752d25dc-00d0-4bee-b5c5-7292e6a33d44.png)

![image](https://user-images.githubusercontent.com/61428623/197365728-f97afee4-bbc0-44ac-8e04-f62ae07e1708.png)

![image](https://user-images.githubusercontent.com/61428623/197365730-f3735e5f-3b76-4228-9d94-3630859ed5bb.png)
