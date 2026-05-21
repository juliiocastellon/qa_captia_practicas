# 🖥️ Alarmas – Reglas de Alarma

**Objetivo Principal:** Permite al usuario consultar, gestionar y crear las reglas que definen las condiciones de disparo de las alarmas del sistema.

## 📸 Mapeo de Interfaz

<img width="1137" height="180" alt="image" src="https://github.com/user-attachments/assets/3c1e95f0-bb7d-4c0a-9a52-9e9ae81159b2" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Título "Reglas de Alarma" | Cabecera informativa | — | — |
| 2 | Botón "Nueva Regla" | CTA Principal | Abre el flujo de creación de una nueva regla | Haz clic aquí para comenzar a definir una nueva condición de disparo de alarma en el sistema. |
| 3 | Enlace "Reintentar" | Acción de recuperación | Reintenta la carga del listado de reglas | Púlsalo una vez el administrador haya resuelto el problema de configuración para comprobar si el listado carga correctamente. |
| 4 | Estado de error "Error al cargar datos" | Mensaje de error | — | Comunica este mensaje a tu administrador de sistema para que configure la variable EVENTS_ENGINE_URL y restaure el funcionamiento de esta sección. |

## 💡 Guía de Uso

La pestaña **Reglas de Alarma** es el espacio desde el que se configuran las condiciones que determinan cuándo y cómo se dispara cada alarma en el sistema. En condiciones normales, esta vista mostraría el listado completo de reglas activas, permitiendo consultarlas, editarlas o eliminarlas, así como crear nuevas mediante el botón **Nueva Regla** (2). En el estado actual, la vista no puede cargar el contenido porque la variable de entorno **EVENTS_ENGINE_URL** no está configurada en el sistema (4); para resolver esta incidencia es necesario que un administrador revise y complete la configuración del motor de eventos. Una vez subsanado el problema, pulsa **Reintentar** (5) para cargar el listado sin necesidad de recargar la página.
