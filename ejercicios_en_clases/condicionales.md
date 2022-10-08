Algoritmo sin_titulo
	letra<-""
	Escribir "Escribe la letra"
	Leer letra
	Si letra== "a" o letra=="A" Entonces
		Escribir "La letra es una vocal y es la A"
	SiNo
		Si letra== "e" o letra=="E" Entonces
			Escribir "La letra es una vocal y es la E"
		SiNo
			Si letra== "i" o letra=="I" Entonces
				Escribir "La letra es una vocal y es la I"
			SiNo
				Si letra== "o" o letra=="O" Entonces
					Escribir "La letra es una vocal y es la O"
				SiNo
					Si letra== "u" o letra=="U" Entonces
						Escribir "La letra es una vocal y es la U"
					SiNo
						Escribir "La letra que escribiste no es una vocal"
					Fin Si
				Fin Si
			Fin Si
		Fin Si
	Fin Si
FinAlgoritmo

