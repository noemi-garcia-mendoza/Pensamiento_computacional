##Algoritmo calculadora

      num_1<-0
      num_2<-0
      resultado<-0
      operacion<-0
      continuacion= "si"

      Mientras continuacion="si" Hacer
      Escribir "ingresa el primer numero"
      Leer num_1
      Escribir "ingresa el segundo numero"
      Leer num_2

      Escribir "que operacion deseas realizar; suma(1), resta(2), multiplicacion(3) o divicion (4),"
      Leer operacion
      Segun operacion Hacer
        1:
          resultado= (num_1+ num_2)
          Escribir "el resultado de la operacion es", " ", resultado
        2:
          resultado= (num_1 - num_2)
          Escribir "el resultado de la operacion es", " ", resultado
        3:
          resultado= (num_1/num_2)
          Escribir "el resultado de la operacion es", " ", resultado
        4:
          resultado= (num_1 * num_2)
          Escribir "el resultado de la operacion es", " ", resultado

        De Otro Modo:
          Escribir "operador no valido"
      FinSegun

      Escribir "quieres hacer otra operacion"
      Leer continuacion
    FinMientras


    FinAlgoritmo
