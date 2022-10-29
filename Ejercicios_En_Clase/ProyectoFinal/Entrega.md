Solicitud
Instrucciones:

1. Diseña un algoritmo representándolo en un diagrama de flujo y pseudocódigo para mostrar el mensaje APROBADO si la nota final de un estudiante es mayor o igual que 4,0, y el mensaje REPROBADO en caso contrario, considere además el siguiente requisito adicional que la nota debe cumplir: debe estar dentro del rango 1,0 a 7,0
2. Diseña un algoritmo representándolo en diagrama de flujo y pseudocódigo para obtener la edad promedio de un grupo de N alumnos.


1.
Algoritmo estudiantes
	calif <- 0
	
	Escribir "Cual es tu Calificacion?"
	Leer calif

	si calif <= 4 Entonces
		
		Escribir  "Los siento, estas REPROBADO"
		
	FinSi
	
	si calif >= 5 y calif <= 7 Entonces
		
		Escribir  "Felicidades estas APROBADO"
	FinSi
	
	
	si calif >= 8  Entonces
		
		Escribir  "Calificacion no valida"
	FinSi
FinAlgoritmo

![image](https://user-images.githubusercontent.com/61428623/198855538-07a5a1b5-2e5e-4f26-acdc-38c50e22b9c2.png)
![image](https://user-images.githubusercontent.com/61428623/198855547-3f227615-3c47-46d5-ae4b-636f4d06a958.png)


2.-
Algoritmo Promedio_Grupo
	total <- 0
	edad <- 0
	promedio <- 0;
	i <- 0
	
    Escribir "¿Cuantos alumnos son en el grupo?:";
	Leer total
	
    Para i<-1 Hasta total Con Paso 1 Hacer
		
        Escribir "Dame la edad del Alumno ", i;
        Leer edad;
        promedio <- promedio + edad;
       
    FinPara
    Si total = 0 Entonces
        promedio <- 0;
    SiNo
        promedio <- promedio/total;
    FinSi
    Escribir "La edad promedio del Grupo es de: ", promedio;
	
	
FinAlgoritmo


![image](https://user-images.githubusercontent.com/61428623/198855557-0fe7dea4-684f-454d-993c-fa580ae2eef5.png)

![image](https://user-images.githubusercontent.com/61428623/198855571-bf313a8c-add1-4633-b638-1e43438574d5.png)

![image](https://user-images.githubusercontent.com/61428623/198855577-8264f054-7b64-4be6-8f6d-a64ea8f699e3.png)









