# sepulvedagonzalezangelalejandro_3_1215_3W

# Diccionario con frutas y sus precios por kilo en pesos

print("Sepulveda Gonzalez Angel Alejandro,1215,3W")

precios_frutas = {

  'Manzana': 70.0,  # Precio por kilo de manzana en pesos
    
  'Banana': 40.0,   # Precio por kilo de banana en pesos
    
  'Naranja': 55.0   # Precio por kilo de naranja en pesos

}


# Pedir al usuario que ingrese la fruta y la cantidad de kilos

fruta = input("Introduce una fruta (Manzana, Banana, Naranja): ")

kilos = float(input("¿Cuántos kilos quieres comprar? "))

# Verificamos si la fruta está en el diccionario y calculamos el precio o mostramos un mensaje de error

if fruta in precios_frutas:

  precio_total = precios_frutas[fruta] * kilos
    
  print(f"El precio de {kilos} kilos de {fruta} es {precio_total} pesos.")

else:
   
  print("La fruta no está en el diccionario.")

![image](https://github.com/user-attachments/assets/dbb49bd6-e16a-47d7-add2-fa1875415456)
![image](https://github.com/user-attachments/assets/ed5f019f-7191-40d3-9f8c-fcd3c61e785a)
