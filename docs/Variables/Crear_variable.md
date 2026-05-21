# 🖥️ Crear variable global

**Objetivo principal:** Permite al usuario crear nuevas variables globales dentro de la plataforma para utilizarlas posteriormente en dashboards, automatizaciones, SCADA e informes.

## 📸 Mapeo de interfaz
<img width="482" height="576" alt="image" src="https://github.com/user-attachments/assets/27d8b310-88f9-4f21-b762-9b29e29e5b8c" />

## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre" | Campo de texto | Introducir nombre | Permite al usuario definir el nombre visible de la variable dentro de la plataforma. Para utilizarlo, el usuario debe escribir el nombre que desea asignar a la variable en el campo correspondiente. |
| 2 | Selector de tipo de señal | Selector desplegable | Elegir tipo de señal | Permite al usuario seleccionar el tipo de señal asociado a la variable, como analógica o digital. Para utilizarlo, el usuario debe abrir el desplegable y seleccionar el tipo de señal adecuado según la variable que desea crear. |
| 3 | Selector de tipo de dato | Selector desplegable | Elegir tipo de dato | Permite al usuario definir el formato de dato utilizado por la variable, como entero, decimal o booleano. Para utilizarlo, el usuario debe seleccionar el tipo de dato desde el menú desplegable correspondiente. |
| 4 | Campo "Unidad" | Campo de texto | Definir unidad | Permite al usuario especificar la unidad de medida asociada a la variable, como °C, %, kWh u otras. Para utilizarlo, el usuario debe escribir la unidad deseada en el campo disponible. |
| 5 | Selector de categoría | Selector desplegable | Asignar categoría | Permite al usuario clasificar la variable dentro de una categoría funcional configurada en la plataforma. Para utilizarlo, el usuario debe abrir el desplegable y seleccionar la categoría correspondiente. |
| 6 | Campo "Descripción" | Campo de texto | Añadir descripción | Permite al usuario añadir información adicional o contexto sobre la variable creada. Para utilizarlo, el usuario debe escribir una descripción explicativa en el campo correspondiente. |
| 7 | Selector de asset asociado | Selector contextual | Asociar asset | Permite al usuario vincular la variable a un asset, dispositivo o entidad concreta de la instalación. Para utilizarlo, el usuario debe abrir el selector y elegir el asset que desea relacionar con la variable. |
| 8 | Campo "Valor inicial" | Campo numérico | Definir valor inicial | Permite al usuario establecer el valor inicial de la variable al momento de su creación. Para utilizarlo, el usuario debe introducir el valor numérico deseado en el campo correspondiente. |

## 💡 Guía de uso

La ventana de creación de variables globales permite registrar nuevas señales dentro de la plataforma para su utilización en distintos módulos como dashboards, automatizaciones o pantallas SCADA.

Para crear una variable, primero debes definir un nombre identificativo y seleccionar tanto el tipo de señal como el tipo de dato asociado. Posteriormente, puedes añadir información complementaria como unidad de medida, categoría funcional, descripción o asset relacionado.

Opcionalmente, también es posible definir un valor inicial para la variable antes de guardarla dentro del sistema.

[← Anterior](./Variables.md) • [📚 Índice](../README.md) • [Siguiente →](../Auditoria/Auditoria.md)
