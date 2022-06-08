# portafolio
fecha = "19-05-2022"; garita = "Los sauces #2320 Bulnes"; encargado = ""; recorrido = 0; total_pasajeros = 0; estudiantes = 0; adulto = 0; adulto_mayor = 0; contador = 0; pasajeros = 0; 
total_estudiantes = 0; total_adulto = 0; total_adultom = 0; 
encargado = input("ingresar el nombre de el encargado")
recorrido = int(input("ingresar cantidad de recorridos"))
while contador < recorrido:
    contador = contador + 1
    print("ingresar cantidad total de pasajeros")
    pasajeros = int(input())
    print("ingresar cantidad total de pasjeros estudiantes")
    estudiantes = int(input())
    print("ingresar la cantidad total de pasajeros adultos")
    adulto = int(input())
    print("ingresar la cantidad total de pasajeros adultos mayores")
    adulto_mayor = int(input())
    total_pasajeros += pasajeros 
    total_estudiantes += estudiantes
    total_adulto += adulto
    total_adultom += adulto_mayor
print("################################")
print("Fecha:", fecha)
print("Encargado de turno:", encargado)
print("total pasajeros:", total_pasajeros)
print("total estudiantes:", total_estudiantes)
print("total adultos:", total_adulto)
print("total adulto mayor:", total_adultom)
print("este algoritmo fue creado por seba y franco")
