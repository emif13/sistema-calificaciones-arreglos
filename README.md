# sistema-calificaciones-arreglos 

Sistema de Calificaciones con Arreglos
Descripción
Este proyecto fue desarrollado como parte de la asignatura Introducción a la Programación.

Objetivo
Aplicar los conceptos de arreglos, índices y vectores utilizando Python.

Lenguaje utilizado
Python 3

Funcionalidades
Mostrar calificaciones.
Acceder a elementos mediante índices.
Modificar datos.
Calcular promedio.
Mostrar nota más alta y más baja.
Contar aprobados y reprobados.
Ejecución
python sistema_calificaciones.py

Autor
Emil Aguasvivas






calificaciones = [95, 85, 75, 60, 100, 45, 88, -5, 105]

for calificacion in calificaciones:
    print(f"\nCalificación: {calificacion}")

    if calificacion < 0 or calificacion > 100:
        print("Calificación fuera del rango permitido")
    elif calificacion >= 90:
        print("Excelente")
    elif calificacion >= 80:
        print("Muy bueno")
    elif calificacion >= 70:
        print("Aprobado")
    else:
        print("Reprobado") 
