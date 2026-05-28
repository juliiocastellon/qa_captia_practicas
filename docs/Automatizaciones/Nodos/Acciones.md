# 🖥️ Acciones

**Objetivo Principal:** Permite al usuario seleccionar y configurar el tipo de acción que ejecutará el workflow como respuesta a un trigger activado.

## 📸 Mapeo de Interfaz

<img width="376" height="497" alt="image" src="https://github.com/user-attachments/assets/06c4120a-608b-4ca4-928f-ce63016ab15c" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Configuración | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Sección "Acciones" (cabecera) | Contenedor / Acordeón | Expande/colapsa la lista de acciones disponibles | - | Agrupa los 5 tipos de acciones disponibles bajo un único bloque colapsable. Muestra el contador de items (5). |
| 2 | Enviar email | Opción seleccionable | Abre configuración de envío de email | [Configuración](./Configuración/enviar_email.md)  | Permite configurar el envío de un correo electrónico como respuesta al trigger. |
| 3 | Enviar WhatsApp | Opción seleccionable | Abre configuración de mensaje WhatsApp | [Configuración](./Configuración/enviar_whatsapp.md)  | Permite configurar el envío de un mensaje de WhatsApp como respuesta al trigger. |
| 4 | Generar informe | Opción seleccionable | Abre configuración de generación de PDF | [Configuración](./Configuración/generar_informe.md)  | Permite generar un informe en formato PDF a partir de una plantilla predefinida. |
| 5 | Petición HTTP | Opción seleccionable | Abre configuración de webhook/API externa | [Configuración](./Configuración/peticion_http.md)  | Permite realizar una llamada a una API externa mediante una petición HTTP (webhook). |
| 6 | Crear tarea | Opción seleccionable | Abre configuración de tarea GMAO | [Configuración](./Configuración/crear_tarea.md)  | Permite crear automáticamente una tarea en el sistema GMAO vinculada al evento del trigger. |

## 💡 Guía de Uso

1. Accede a la sección **Acciones** dentro del editor de workflow.
2. Selecciona el tipo de acción que debe ejecutarse cuando el trigger se active:
   - **Enviar email**: para notificaciones por correo electrónico.
   - **Enviar WhatsApp**: para notificaciones por mensajería instantánea.
   - **Generar informe**: para producir un PDF automático desde plantilla.
   - **Petición HTTP**: para integrar con sistemas externos vía webhook.
   - **Crear tarea**: para generar órdenes de trabajo en el GMAO automáticamente.
3. Una vez seleccionada, configura los parámetros específicos de la acción elegida.
4. Puedes reordenar las acciones arrastrando el icono de puntos (⠿) a la izquierda de cada item.
