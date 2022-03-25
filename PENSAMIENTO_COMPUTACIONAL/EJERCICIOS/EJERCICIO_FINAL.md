Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayor o menor al almacenado, así como el número de intemtos restantes.

       Algoritmo Juego
	        intentos<-10
	        num_secreto<- azar(20)+1
	
	        Escribir '¿Quieres jugar conmigo?'
	        Leer sip
         	Escribir "¡Perfecto! Solo necesito que adivines un numero"
	        Escribir "¡Facil! ¿O no? Lo unico malo es que tienes solo 10 intentos"
	        Escribir "¿Listo?"
	        Leer sip
	        Escribir "Con calma, dime tu numero de la suerte"
	        Leer num_ingresado
	        Mientras num_secreto<>num_ingresado || intentos>1 Hacer
		      Si num_secreto>num_ingresado Entonces
			          Escribir "Te falto un poquito, subele"
		      SiNo
			          Escribir "Te sobro un muchito, bajale"
		      Fin Si
		      intentos<-intentos-1
		      Escribir "No olvides que te quedan ",intentos," intentos"
		      Leer num_ingresado
	        Fin Mientras
	
	        Si num_secreto=num_ingresado Entonces
		            Escribir "Eres muy bueno en estos juegos ¡Ganaste!"
	        SiNo
		            Escribir "Mejor suerte para la proxima, el numero era ", num_secreto
	        Fin Si
	
	
          FinAlgoritmo

![evaluacion](https://user-images.githubusercontent.com/101203478/160169658-2b89db36-37f6-444f-8af0-60c018bbb4a9.png)


Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing
