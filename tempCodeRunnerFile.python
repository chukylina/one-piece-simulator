#Simulador de Torneos de One piece
import math

#Ingrese numero de rondas
#int->int
print("¿Número de rondas?(debe ingresar solo el numero)")
rondas = int(input())

#ingrese nombre participante
#str-> str
#crear lista de Participantes
#str-> int
#Crear lista de participantes ingresados
def recolectar_participantes():
    participantes = []  # Lista vacía para almacenar los participantes
    while True:
        participante = input("Introduce el nombre del participante (o escribe 'fin' para terminar): ")
        if participante.lower() == 'fin':  # Condición para salir del bucle
            break  # Sale del bucle si el usuario escribe 'fin'
        
        if participante:  # Comprueba que el input no esté vacío
            participantes.append(participante)  # Añade el participante a la lista
        else:
            print("Por favor, introduce un nombre válido.")  # Mensaje de error si está vacío

    if participantes:  # Verifica si hay participantes en la lista
        print("Participantes:", participantes)  # Muestra la lista final de participantes
    else:
        print("No se ingresaron participantes.")  # Mensaje si no hay participantes

    return participantes  # Devuelve la lista de participantes

# Llama a la función
recolectar_participantes()
