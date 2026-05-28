# 🖥️ Globals

**Objetivo Principal:** Permite al usuario seleccionar y configurar nodos de acceso a variables globales de proceso, ya sea para construir estructuras tipadas, leerlas o escribir en ellas.

## 📸 Mapeo de Interfaz

<img width="616" height="636" alt="image" src="https://github.com/user-attachments/assets/059a6be0-743c-4f8b-8fe7-c9686764dc50" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Configuración | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- | :--- |
| — | Sección "Globals" (cabecera) | Contenedor / Acordeón | Expande/colapsa la lista de nodos globales disponibles | - | Agrupa los 3 tipos de nodos de variables globales bajo un único bloque colapsable. Muestra el contador de items (3). |
| 1 | Variable UDT | Opción seleccionable | Abre configuración de Variable UDT | [Configuración](./Configuración/variables_udt.md) | Construye una estructura de datos tipada (UDT) mapeando variables globales del proceso. |
| 2 | Leer global | Opción seleccionable | Abre configuración de lectura de variable global | [Configuración](./Configuración/leer_global.md) | Lee el valor actual de una variable de proceso global. |
| 3 | Escribir global | Opción seleccionable | Abre configuración de escritura de variable global | [Configuración](./Configuración/escribir_global.md) | Escribe un valor en una variable de proceso global mediante adapter command. |

## 💡 Guía de Uso

1. Accede a la sección **Globals** dentro del editor de workflow.
2. Selecciona el tipo de nodo que necesitas:
   - **Variable UDT**: cuando necesites construir una estructura tipada agrupando varias variables globales.
   - **Leer global**: cuando el workflow necesite consultar el valor actual de una variable de proceso.
   - **Escribir global**: cuando el workflow deba modificar el valor de una variable de proceso vía adapter command.
3. Una vez seleccionado, configura los parámetros específicos del nodo elegido.
4. Puedes reordenar los nodos arrastrando el icono de puntos (⠿) a la izquierda de cada item.


[← Volver a Nodos del Workflow](./nodos.md)
