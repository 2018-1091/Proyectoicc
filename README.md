# Proyectoicc 


# Estadios 
print("Tipo de destino: Estadios para el Mundial Rusia 2018")
print('1. Luzniki Stadium')
print('2. Spartak Stadium')
print('3. Nizny Novrorom Stadium')
print('4. Samara Arena Stadium')
print('5. Kazan Arena Stadium')
print('6. Mordovia Arena Stadium')
print()
# Tribunas 
print('Tribunas establecidas:')
print('A. Tribuna Oriente')
print('B. Tribina Central')
print('C. Tribuna Occidente')
print()

a=int(input('¿A cúal de los estadios irás a ver el partido? (Ingresa un número): '))

b=input('¿En qué tribuna te gustaría ubicarte?(Ingresa una letra): ')
n= int(input("¿En qué asiento te gustaría sentarte?"))

print()
print()

if a==1:
  if b=="A":
    print('El precio es 140 dolares ')
  else:
    if b=="B":
      print('El precio es 100 dolares')
    else:
      print('El precio es 160 dolares')
elif a==2:
   if b=="A":
     print('El precio es 190 dolares')
   else:
    if b=="B":
      print('El precio es 180 dolares')
    else:
      print('El precio es 100 dolares')
elif a==3:
   if b=="A":
     print('El precio es 140 dolares')
   else:
    if b=="B":
      print('El precio es 90 dolares')
    else:
      print('El precio es 60 dolares')
elif a==4:
  if b=="A":
    print('El precio es 185 dolares')
  else:
    if b=="B":
      print('El precio es 175 dolares')
    else:
      print('El precio es 99 dolares')
elif a==5:
   if b=="A":
     print('El precio es 135 dolares')
   else:
    if b=="B":
      print('El precio es 90 dolares')
    else:
      print('El precio es 59 dolares')
elif a==6:
   if b=="A":
     print('El precio es 140 dolares')
   else:
     if b=="B":
       print('El precio es 95 dolares')
     else:
       print('El precio es 69 dolares')
else:
   print('Números fuera de rango')

# Asientos

filas1 = 0 
asientos1 = 0
filas2 = 0
asientos2 = 0

if b=="A":
  print("Tribuna Oriente")

elif b=="B":
  print("Tribuna Central")

elif b=="C":
  print("Tribuna Occidental")

if n>=1 and n<=15000:
  if n % 100 == 0:
    filas1 = filas1 + (n//300)
    asientos1 = asientos1 + 300
    print("Número de fila:",filas1, "Número de asiento:",asientos1)
  else:
    filas2 = filas2 + (n//300) + 1
    asientos2 = asientos2 + (n%300)
    print("Número de fila:",filas2, "Número de asiento:",asientos2)


