# nota
Nota=float(input("Ingrese su nota (mayor a cero y menor que cinco):"))
while (Nota>5.0) or (Nota<0):
     print("la nota ingresada mo es valida, porfavor intentalo de nuevo")
     Nota=float(input("Ingrese su nota (mayor a cero y menor que cinco):"))
if(Nota<3.0):
    print("Bajo rendimieto")
elif (Nota<=4.0):
    print ("rendimiento basico") 
else:
    print ("Alto rendimiento") 
print ("Terminaste,vuelva pronto")
