# 🖥️ Crear variable global

**Objetivo principal:** Permite al usuario crear nuevas variables globales dentro de la plataforma para utilizarlas posteriormente en dashboards, automatizaciones, SCADA e informes.

## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre" | Campo de texto | Introducir nombre | Permite definir el nombre visible de la variable global dentro de la plataforma. |
| 2 | Selector de tipo de señal | Selector desplegable | Elegir tipo de señal | Permite seleccionar el tipo de señal asociado a la variable, como analógica o digital. |
| 3 | Selector de tipo de dato | Selector desplegable | Elegir tipo de dato | Permite definir el formato de dato utilizado por la variable, como decimal, entero o booleano. |
| 4 | Campo "Unidad" | Campo de texto | Definir unidad | Permite especificar la unidad de medida asociada a la variable, como °C, %, kWh, etc. |
| 5 | Selector de categoría | Selector desplegable | Asignar categoría | Permite clasificar la variable dentro de una categoría funcional configurada en la plataforma. |
| 6 | Campo "Descripción" | Campo de texto | Añadir descripción | Permite introducir información adicional o contexto sobre la variable creada. |
| 7 | Selector de asset asociado | Selector contextual | Asociar asset | Permite vincular la variable a un asset, dispositivo o entidad concreta dentro de la instalación. |
| 8 | Campo "Valor inicial" | Campo numérico | Definir valor inicial | Permite establecer el valor inicial que tendrá la variable al ser creada. |

## 💡 Guía de uso

La ventana de creación de variables globales permite registrar nuevas señales dentro de la plataforma para su utilización en distintos módulos como dashboards, automatizaciones o pantallas SCADA.

Para crear una variable, primero debes definir un nombre identificativo y seleccionar tanto el tipo de señal como el tipo de dato asociado. Posteriormente, puedes añadir información complementaria como unidad de medida, categoría funcional, descripción o asset relacionado.

Opcionalmente, también es posible definir un valor inicial para la variable antes de guardarla dentro del sistema.
