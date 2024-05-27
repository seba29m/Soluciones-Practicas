#En una escuela, luego de tomar un determinado examen, es necesario calcular el promedio de notas (las notas van de 0 a 10) de los alumnos de un curso. 
#Se necesita saber si el rendimiento ha sido elevado (el promedio es mayor a 8), aceptable (el promedio está comprendido entre 6 y 8) o bajo (promedio es inferior a 6). 
#Desarrollar un algoritmo que resuelva este problema. 
#Para tener en cuenta: las autoridades del colegio saben cuántos estudiantes del curso han rendido el examen.

#Definición de las variables
    #Cantidad de alumnos que rindieron
cantidad_alumnos = int(input("Ingrese la cantidad de alumnos que rindieron: "))
    #variable que sume las notas
suma_notas = 0

#Ingreso de notas
for i in range(cantidad_alumnos):
    while True:
        nota = float(input("Ingrese la nota del estudiante: "))
        if 0 <= nota <= 10:
            suma_notas += nota
            break
        
#Calcular el promedio
promedio = suma_notas / cantidad_alumnos

# Determinar el rendimiento
if promedio > 8:
    rendimiento = "elevado"
elif 6 <= promedio <= 8:
    rendimiento = "aceptable"
else:
    rendimiento = "bajo"

# Mostrar el rendimiento
print(f"El promedio de notas es {promedio:.2f}. El rendimiento ha sido {rendimiento}.")
