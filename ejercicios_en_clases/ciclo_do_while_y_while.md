## NUMERO AL AZAR CON LOS CICLOS WHILE Y DO WHILE 

    Algoritmo Ciclo_do_while

      num_sec<-azar(100)
      num_usu<-0
      vidas<-5
      Escribir "adivina el numero del 1 al 100"
      Leer num_usu
      Mientras num_usu<>num_sec y vidas>1 Hacer
        Si num_usu>num_sec Entonces
          Escribir "tu numero es mayor"
        SiNo
          Escribir "tu numero es menor"
        Fin Si
        Escribir "adivina el numero del 1 al 100"
        Leer num_usu
        vidas=vidas-1

      Fin Mientras
      Si num_usu=num_sec Entonces
        Escribir "felicidade"
      SiNo
        Escribir "se acabaron tus vidas"
      Fin Si

    FinAlgoritmo


