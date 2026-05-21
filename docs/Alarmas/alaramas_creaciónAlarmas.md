# 🖥️ Alarmas – Nueva Regla

**Objetivo Principal:** Permite al usuario configurar y crear una nueva regla de alarma definiendo sus condiciones de disparo, la acción resultante y los metadatos de clasificación.

## 📸 Mapeo de Interfaz

*(Formulario de creación de nueva regla de alarma)*

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre" | Input de texto | — | Escribe aquí un nombre descriptivo que identifique claramente qué situación detecta esta regla. |
| 2 | Campo "Descripción" | Textarea | — | Úsalo para documentar el propósito de la regla o cualquier detalle relevante para otros usuarios que la gestionen en el futuro. |
| 3 | Campo "Group By" | Input de texto | — | Introduce aquí las dimensiones por las que quieres agrupar las alarmas generadas por esta regla, separadas por coma. Úsalo para que alarmas del mismo tipo pero de distintos hosts o áreas se traten de forma independiente. |
| 4 | Checkbox "Habilitada / Activa" | Toggle / Checkbox | Activa o desactiva la regla al crearla | Márcalo si quieres que la regla empiece a evaluar condiciones en cuanto se cree; desactívalo si necesitas configurarla sin que entre en producción todavía. |
| 5 | Selector de operador lógico | Desplegable | Define si deben cumplirse todas o alguna de las condiciones | Cámbialo a ANY (OR) si quieres que la alarma se dispare cuando se cumpla al menos una condición; mantenlo en AND si todas deben cumplirse simultáneamente. |
| 6 | Selector de función de agregación | Desplegable | Define cómo se agrega el valor de la variable | Selecciona la función de agregación que se aplicará a la métrica: avg, sum, max, min, etc. Úsalo para evaluar tendencias en lugar de valores puntuales. |
| 7 | Campo de métrica | Input de texto | — | Escribe aquí el nombre de la variable o métrica sobre la que se evaluará la condición de disparo. |
| 8 | Campo de ventana temporal | Input de texto | — | Define el intervalo de tiempo sobre el que se evalúa la condición (por ejemplo, 5m = últimos 5 minutos). Ajústalo según la velocidad de cambio de la variable que estás monitorizando. |
| 9 | Selector de operador comparador | Desplegable | Define el tipo de comparación de la condición | Selecciona el operador de comparación: >, <, >=, <=, ==. Determina en qué dirección debe cruzarse el umbral para disparar la alarma. |
| 10 | Campo de valor umbral | Input numérico | — | Introduce el valor a partir del cual se disparará la alarma. Ajústalo según los límites operativos aceptables de la variable monitorizada. |
| 11 | Botón eliminar condición (×) | Acción | Elimina la condición de la fila correspondiente | Úsalo para borrar una condición que ya no necesites sin tener que rehacer la regla desde cero. |
| 12 | Enlace "+ Agregar condición" | Acción | Añade una nueva fila de condición al bloque When | Úsalo cuando necesites que la regla evalúe más de una condición simultáneamente antes de disparar la alarma. |
| 13 | Selector "Severidad" | Desplegable | Define el nivel de severidad de la alarma generada | Asígnale el nivel de criticidad adecuado (P1–P4) para que el sistema priorice correctamente la respuesta operativa. |
| 14 | Campo "Prioridad" | Input numérico | — | Introduce un valor numérico para ordenar esta regla respecto a otras del mismo nivel de severidad en caso de conflicto. |
| 15 | Campo "Categoría" | Input de texto | — | Úsalo para clasificar la alarma dentro de una categoría funcional que facilite su filtrado y análisis posterior. |
| 16 | Campo "Subcategoría" | Input de texto | — | Úsalo para añadir un nivel adicional de clasificación dentro de la categoría seleccionada. |
| 17 | Campo "Propietario" | Input de texto | — | Asigna aquí el equipo o persona responsable de gestionar las alarmas que genere esta regla. Por defecto aparece como "unassigned". |
| 18 | Botón "Crear Regla" | CTA Principal | Guarda y activa la nueva regla | Púlsalo una vez hayas completado todos los campos para crear la regla y que comience a evaluar condiciones según la configuración definida. |
| 19 | Enlace "Cancelar" | Acción secundaria | Descarta el formulario y regresa al listado de reglas | Úsalo si decides no crear la regla y quieres volver al listado sin guardar ningún cambio. |

## 💡 Guía de Uso

Para crear una nueva regla de alarma, comienza asignando un **nombre** (1) claro que describa qué situación detecta, y utiliza la **descripción** (2) para documentar el contexto para otros usuarios. En el bloque **Condiciones (When)** define qué variable monitorizar (7), con qué función de agregación (6), en qué ventana temporal (8) y qué umbral debe superarse (9–10); si necesitas evaluar varias condiciones a la vez, usa **+ Agregar condición** (12) y configura el operador lógico (5) según si deben cumplirse todas o solo alguna. En el bloque **Acción (Then)** asigna la **severidad** (13) adecuada para que el sistema priorice correctamente la respuesta, y completa los campos de categoría y propietario para facilitar su gestión posterior. Cuando todo esté configurado, pulsa **Crear Regla** (18) para activarla, o **Cancelar** (19) si decides no guardar los cambios.
