# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* Programa que pida un número y diga si es positivo o negativo

### ALGORITMO

    INICIO
  
    Declarar(número)
    Mostrar("Ingresa un número cualquiera")
    Asignar(número)
    SI (número < 0) ENTONCES MOSTRAR ("Es un número positivo")
    SINO (número > 0) ENTONCES MOSTRAR ("Es un número negativo")
    SINO (número = 0) ENTONCES MOSTRAR ("Es un número neutro")
    
    FIN
    
### DIAGRAMA DE FLUJO

![image](https://user-images.githubusercontent.com/101203478/159042380-a5a499e4-15d9-4e08-9ab0-7fb9c6a59388.png)

* Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.

### ALGORITMO

    INICIO
    
    Declarar(letra)
    Mostrar("Ingresa la letra s ó n")
    Asignar(letra)
    SI (letra == s || letra == n) ENTONCES MOSTRAR ("Correcto")
    SINO MOSTRAR ("Incorrecto")
    
    FIN
    
### DIAGRAMA DE FLUJO



* Un programa que pida una letra y detecte si es una vocal. 

      INICIO 
      
      Declarar(letra)
      Mostrar("Ingresa una letra cualquiera")
      Asignar(letra)
      EN CASO DE (letra) HAGA
         Caso a: MOSTRAR ("Es una vocal")
         Caso e: MOSTRAR ("Es una vocal")
         Caso i: MOSTRAR ("Es una vocal")
         Caso o: MOSTRAR ("Es una vocal")
         Caso u: MOSTRAR ("Es una vocal")
         SINO MOSTRAR ("Ingresaste una consonante")
      FIN CASO
         
      FIN
      
      

* Programa que pida 3 números y los muestre en pantalla de menor a mayor.  



* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.



* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.



* Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.
