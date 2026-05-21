# 🖥️ Auditoría

**Objetivo principal:** Permite al usuario consultar y supervisar el registro de actividad del sistema, visualizando acciones realizadas, accesos, cambios y eventos generados dentro de la plataforma.

## 📸 Mapeo de interfaz
<img width="1223" height="585" alt="image" src="https://github.com/user-attachments/assets/12813df9-7dd4-4a2a-b2a5-247190dfb2bb" />

## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Filtro de rango temporal | Selector de fecha | Filtrar registros | Permite al usuario definir el periodo de tiempo sobre el que se consultarán los eventos de auditoría. Para utilizarlo, el usuario debe seleccionar una fecha de inicio y una fecha final para mostrar únicamente los registros comprendidos dentro de ese rango temporal. |
| 2 | Buscador de usuario | Campo de búsqueda | Filtrar por usuario | Permite al usuario localizar registros de auditoría asociados a usuarios concretos mediante email o identificador. Para utilizarlo, el usuario debe escribir el nombre, email o identificador del usuario en el buscador para filtrar automáticamente los resultados. |
| 3 | Filtro de acción | Filtro desplegable | Filtrar acciones | Permite al usuario mostrar únicamente determinados tipos de acciones registradas dentro del sistema. Para utilizarlo, el usuario debe abrir el desplegable y seleccionar la acción que desea visualizar. |
| 4 | Filtro de tipo de recurso | Filtro desplegable | Filtrar recursos | Permite al usuario visualizar eventos relacionados con módulos o recursos específicos de la plataforma. Para utilizarlo, el usuario debe seleccionar el tipo de recurso desde el menú desplegable correspondiente. |
| 5 | Botón "Actualizar" | CTA Secundario | Refrescar auditoría | Permite al usuario actualizar manualmente los registros y eventos mostrados en pantalla para consultar la información más reciente. Para utilizarlo, el usuario debe pulsar el botón “Actualizar”. |
| 6 | Filtro de resultado | Filtro desplegable | Filtrar resultados | Permite al usuario visualizar registros según el resultado de la acción ejecutada, como éxito o error. Para utilizarlo, el usuario debe seleccionar el resultado deseado desde el filtro desplegable. |
| 7 | Acciones de filtrado | CTA Secundario | Aplicar/Limpiar filtros | Permite al usuario aplicar los filtros configurados o limpiar rápidamente la búsqueda actual. Para utilizarlo, el usuario debe pulsar “Aplicar filtros” para ejecutar la búsqueda o “Limpiar filtros” para restablecer los valores por defecto. |
| 8 | Registro de auditoría | Tabla de eventos | Consultar actividad | Permite al usuario visualizar el historial detallado de eventos y acciones realizadas dentro de la plataforma. Para utilizarlo, el usuario puede consultar información como usuario, recurso, resultado o fecha de ejecución directamente desde la tabla de auditoría. |

## 💡 Guía de uso

La sección de Auditoría permite supervisar toda la actividad registrada dentro de la plataforma, facilitando el seguimiento de accesos, modificaciones y acciones ejecutadas por los usuarios.

Desde la parte superior puedes aplicar filtros por fecha, usuario, acción, recurso o resultado para localizar rápidamente eventos específicos. La tabla principal muestra información detallada de cada registro, incluyendo quién realizó la acción, sobre qué recurso se ejecutó y cuál fue el resultado obtenido.

Esta sección resulta especialmente útil para tareas de supervisión, trazabilidad, seguridad y análisis operativo dentro del entorno industrial.

[← Anterior](../Variables/Crear_variable.md) • [📚 Índice](../README.md) • [Siguiente →](../Cuenta/Cuenta.md)
