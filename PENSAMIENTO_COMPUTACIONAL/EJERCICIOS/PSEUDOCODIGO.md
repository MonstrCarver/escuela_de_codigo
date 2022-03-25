
Convierte los siguientes ejercicios realizado durante el taller a pseudocodigo.

1. Realizar un algoritmo y diagrama de flujo de un programa que solicite un número y lo multiplique por 9, mostrando su resultado.

       Algoritmo Tabla_del_9
	
          Escribir 'Ingresa un numero'
        	Leer numero1
	        variable <- numero1*9
          Escribir variable

       FinAlgoritmo

![Tabla del 9](https://user-images.githubusercontent.com/101203478/159967531-60fc23f1-914b-4113-8008-c21a9a2d7dae.png)

2. Realiza un diagrama de flujo para obtener la suma de diez cantidades, que se soliciten al usuario, mediante la utilización de un ciclo “Mientras”. 

       Algoritmo Suma
	     
          variable <- 0
	        contador <- 1
          Mientras contador<=10 Hacer
		           Leer num
	        	   variable <- variable+num
		           contador <- contador+1
	  FinMientras
	  Escribir variable
       
       FinAlgoritmo

![Suma](https://user-images.githubusercontent.com/101203478/159971967-7e0dd1f6-9c2a-4ca8-b73b-6a9b4f3ea4a3.png)

3. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

        Algoritmo Promedio
	   
	   Escribir "Ingresa tu calificacion del primer periodo"
	   Leer Calificacion1
	   Escribir "Ingresa tu calificacion del segundo periodo"
	   Leer Calificacion2
           Escribir "Ingresa tu calificacion del tercer periodo"
           Leer Calificacion3
           Escribir "Ingresa tu calificacion del cuarto periodo"
           Leer Calificacion4
           variable<-(Calificacion1+Calificacion2+Calificacion3+Calificacion4)/4
           Si variable>=6 Entonces
	        	Escribir "¡Felicidades! Aprobaste la materia"
	   SiNo
	        	Escribir "Lo siento mucho pero reprobaste :c"
	   Fin Si
        
	FinAlgoritmo

![promedio](https://user-images.githubusercontent.com/101203478/160151328-44695890-d5c1-42ac-a55d-838096c6307e.png)

4. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.


5. Un programa que pida una letra y detecte si es una vocal.


6. Programa que pida 3 números y los muestre en pantalla de menor a mayor.


7. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.


8. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.
