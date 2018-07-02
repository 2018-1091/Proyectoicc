# Proyectoicc 

El número de asiento que se le ha asignado a cada persona que desea ingresar al teatro se encuentra
impreso en el ticket de entrada. Si existe un total de 20 filas y por cada fila hay 100 asientos, 
se debe determinar el número de fila y el número del asiento en el que se encuentra la persona 
a partir del número que se encuentra en el ticket.


n= int(input())
filas1 = 0 
asientos1 = 0
filas2 = 0
asientos2 = 0
if n>=1 and n<=8000:
  if n % 100 == 0
    filas1 = filas1 + (n//200)
    asientos1 = asientos1 + 200
    print(filas1, asientos1)
  else:
    filas2 = filas2 + (n//200) + 1
    asientos2 = asientos2 + (n%200)
    print(filas2, asientos2)
