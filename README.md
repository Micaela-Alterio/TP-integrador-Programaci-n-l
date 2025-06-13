# TP-integrador-Programacion 1
Repositorio de programación l UTN


Árbol Genealógico Binario en Python

Este proyecto implementa un **árbol genealógico binario** en Python utilizando programación orientada a objetos. Cada nodo representa una persona, y los nodos conectados representan sus **progenitores**.


## Objetivo

- Modelar una estructura jerárquica familiar usando un árbol binario ascendente.
- Aplicar conceptos de clases, listas y recursividad.
- Implementar los tres tipos de recorridos clásicos: **preorden**, **inorden** y **postorden**.



## ¿Cómo funciona?

Se define una clase `Persona` que incluye:

- Un nombre (`nombre`)
- Una lista de progenitores (`progenitores`)
- Métodos para:
  - Agregar progenitores
  - Imprimir el árbol con indentación jerárquica
  - Recorrer el árbol en preorden, inorden y postorden



## Estructura del árbol

ana = Persona("Ana")
berta = Persona("Berta")
carlos = Persona("Carlos")
ana.agregar_progenitor(berta)
ana.agregar_progenitor(carlos)


