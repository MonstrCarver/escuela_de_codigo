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

<img width="312" alt="image" src="https://user-images.githubusercontent.com/101203478/159408955-a29fd22c-2ee5-48c9-b751-253f5efc18c7.png">

* Un programa que pida una letra y detecte si es una vocal. 

### ALGORITMO

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
      
### DIAGRAMA DE FLUJO

<img width="283" alt="image" src="https://user-images.githubusercontent.com/101203478/159412650-8166e3ed-e3ce-49c1-91ef-172dc8742b76.png">

* Programa que pida 3 números y los muestre en pantalla de menor a mayor.  



* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.

### ALGORITMO

      INICIO
      
      Declarar(numero)
      Mostrar("Ingresa un numero del 1 al 12")
      Asignar(numero)
      EN CASO DE (letra) HAGA
         Caso 1: MOSTRAR ("Enero")
         Caso 2: MOSTRAR ("Febrero")
         Caso 3: MOSTRAR ("Marzo")
         Caso 4: MOSTRAR ("Abril")
         Caso 5: MOSTRAR ("Mayo")
         Caso 6: MOSTRAR ("Junio")
         Caso 7: MOSTRAR ("Julio")
         Caso 8: MOSTRAR ("Agosto")
         Caso 9: MOSTRAR ("Septiembre")
         Caso 10: MOSTRAR ("Octubre")
         Caso 11: MOSTRAR ("Noviembre")
         Caso 12: MOSTRAR ("Diciembre")
         SINO MOSTRAR ("Ingresaste una opcion no valida. Vuelve a intentarlo")
      FIN CASO
         
      FIN

### DIAGRAMA DE FLUJO

<img width="305" alt="image" src="https://user-images.githubusercontent.com/101203478/159419213-c84bcb83-e498-4d13-9220-b10e656ecf17.png">

* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.

### ALGORITMO

      INICIO
      
      Declarar(candidato)
      Mostrar("Elija un candidato para votar")
      Asignar(candidato)
      EN CASO DE (candidato) HAGA
         Caso A: MOSTRAR ("Usted ha votado por el partido rojo")
         Caso B: MOSTRAR ("Usted ha votado por el partido verde")
         Caso C: MOSTRAR ("Usted ha votado por el partido azul")
         SINO MOSTRAR ("Opcion erronea")
      FIN CASO
         
      FIN

### DIAGRAMA DE FLUJO

<img width="298" alt="image" src="https://user-images.githubusercontent.com/101203478/159413947-c64582e9-4d5f-4303-8a3a-c7f80966c92a.png">

* Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.
