# 🖥️ Nueva Tarea — Formulario de Creación

**Objetivo Principal:** Permite al usuario registrar una nueva tarea en el sistema, definiendo su información básica, planificación, asignación, contexto industrial, detalles GMAO y etiquetas.

---

## 📸 Mapeo de Interfaz

<img width="378" height="602" alt="image" src="https://github.com/user-attachments/assets/10a0b534-39ec-4c9e-8841-4faa41174db9" />

---

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Sección "Información básica" | Sección de formulario | Recoge los datos principales de la tarea | Contiene los campos obligatorios de identificación de la tarea. El campo "Título" es obligatorio y permite describir brevemente la tarea. El campo "Descripción" es opcional y permite añadir más detalles sobre la tarea. |
| 2 | Sección "Planificación" | Sección de formulario | Define el estado, prioridad y fechas | Permite configurar el estado inicial de la tarea (por defecto "Pendiente"), la prioridad (por defecto "Media") y el tipo (por defecto "Otro"). También incluye los campos "Fecha límite" y "Fecha inicio planificada" en formato dd/mm/aaaa para definir la planificación temporal de la tarea. |
| 3 | Sección "Asignación" | Sección de formulario | Asigna un responsable a la tarea | Permite seleccionar el usuario responsable de la tarea mediante el selector "Asignado a". Para utilizarlo, el usuario debe pulsar el selector y elegir el responsable de la lista disponible. |
| 4 | Sección "Contexto industrial" | Sección de formulario | Vincula la tarea a activos industriales | Permite asociar la tarea a una fábrica, zona y máquina o equipo concreto mediante sus respectivos campos de ID o nombre. Para utilizarlo, el usuario debe introducir los identificadores o nombres de los activos correspondientes. |
| 5 | Sección "Detalles GMAO" | Sección de formulario | Configura parámetros de mantenimiento | Permite definir la severidad de la tarea (por defecto "Medio"), la categoría técnica (por defecto "Otra"), la duración estimada en minutos (por defecto 60) y si se espera una parada mediante la casilla "Se espera parada". |
| 6 | Sección "Etiquetas" | Sección de formulario | Categoriza la tarea mediante etiquetas | Permite añadir etiquetas a la tarea para facilitar su clasificación y búsqueda. Para utilizarlo, el usuario debe pulsar "+ Añadir etiqueta…" y seleccionar o crear las etiquetas deseadas. |
| 7 | Botón "Cancelar" | Botón secundario | Cierra el formulario sin guardar | Permite abandonar el proceso de creación descartando todos los datos introducidos. Para utilizarlo, el usuario debe pulsar el botón y confirmar si se le solicita confirmación. |
| 8 | Botón "Crear tarea" | CTA Principal | Guarda y registra la nueva tarea | Confirma la creación de la tarea con todos los datos introducidos en el formulario. Para utilizarlo, el usuario debe completar al menos el campo obligatorio "Título" y pulsar el botón. |

---

## 💡 Guía de Uso

El formulario **Nueva Tarea** centraliza toda la información necesaria para registrar correctamente una tarea en el sistema, desde su identificación hasta su contexto industrial y parámetros de mantenimiento.

Se utiliza principalmente para:

- Registrar nuevas tareas de mantenimiento o seguimiento
- Asignar responsables y definir fechas de ejecución
- Vincular tareas a activos industriales concretos
- Categorizar tareas por severidad, tipo y etiquetas
- Planificar paradas asociadas a intervenciones

### ✅ Cómo crear una tarea correctamente

1. Accede al formulario pulsando "+ Nueva tarea" desde la vista Lista o Kanban.
2. Introduce el título obligatorio y, opcionalmente, una descripción.
3. Configura el estado, prioridad, tipo y fechas en la sección Planificación.
4. Selecciona el responsable en la sección Asignación.
5. Vincula la tarea a la fábrica, zona y equipo correspondiente en Contexto industrial.
6. Rellena los detalles GMAO: severidad, categoría, duración estimada y si se espera parada.
7. Añade etiquetas si es necesario para facilitar la clasificación.
8. Pulsa "Crear tarea" para registrar la tarea en el sistema.
