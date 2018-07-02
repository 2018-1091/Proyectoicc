# Proyectoicc 

n= int(input())

filas1 = 0 
asientos1 = 0
filas2 = 0
asientos2 = 0

if n>=1 and n<=2000:
  if n % 100 == 0:
    filas1 = filas1 + (n//100)
    asientos1 = asientos1 + 100
    print("Número de fila:",filas1, "Número de asiento:",asientos1)
  else:
    filas2 = filas2 + (n//100) + 1
    asientos2 = asientos2 + (n%100)
    print("Número de fila:",filas2, "Número de asiento:",asientos2)


