# 🖥️ Página de inicio

**Objetivo principal:** Permite al operario obtener de un vistazo el estado actual de la planta, identificar tareas y alarmas prioritarias y acceder a la siguiente acción recomendada por la IA.

## 📸 Mapeo de interfaz

<img width="1920" height="944" alt="Texto (2)" src="https://github.com/user-attachments/assets/22de5d40-42a8-4a2f-9658-178763379417" />


## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Lectura AI de la instalación | Bloque informativo | — | Permite al usuario consultar un resumen automático generado por inteligencia artificial sobre el estado actual de la instalación. Para utilizarlo, el usuario únicamente debe revisar el bloque informativo donde se muestran alarmas activas, tareas vencidas y el nivel de confianza del análisis realizado por la IA. |
| 2 | Citas numeradas [1][2] / "Ver fuentes" | Enlace | Despliega panel "Fuentes consultadas" | Permite al usuario consultar las fuentes de datos utilizadas por la IA para generar el análisis mostrado. Para utilizarlo, el usuario debe pulsar sobre las referencias [1], [2] o el enlace “Ver fuentes” para abrir el panel con el detalle de alarmas, tareas y datos analizados. |
| 3 | Siguiente mejor acción | Bloque informativo | — | Permite al usuario visualizar la acción prioritaria recomendada por la IA para el turno actual junto con el impacto esperado sobre producción, calidad, mantenimiento o energía. El usuario puede utilizar esta información como guía para priorizar acciones operativas. |
| 4 | Botón "Por qué veo esto" | CTA Secundario | Despliega panel en la misma vista | Permite al usuario consultar los parámetros y criterios utilizados por la IA para generar el briefing mostrado en pantalla. Para utilizarlo, el usuario debe pulsar el botón “Por qué veo esto” y revisar los datos técnicos y reglas aplicadas al análisis. |
| 5 | Botón "Revisar tareas vencidas" | CTA Principal | Abre panel lateral "Copiloto CAPTIA" | Permite al usuario abrir automáticamente el Copiloto CAPTIA con el análisis contextual ya preparado sobre tareas vencidas y alarmas pendientes. Para utilizarlo, el usuario debe pulsar el botón y el asistente mostrará directamente el foco prioritario detectado. |
| 6 | Botón "Analizar con Copilot" | CTA Principal | Abre análisis IA | Permite al usuario iniciar un análisis libre mediante el Copiloto CAPTIA para consultar el estado actual de la instalación. Para utilizarlo, el usuario debe pulsar el botón y escribir preguntas o consultas personalizadas relacionadas con los datos monitorizados. |
| 7 | Radar de atención | Panel informativo | — | Permite al usuario visualizar el estado de diferentes dominios clave de la instalación como Safety, Quality, Energy, Production, Maintenance y Data Health. El usuario puede identificar rápidamente qué áreas requieren mayor atención según el nivel de prioridad mostrado. |
| 8 | Manufacturing Signal Board | Tabla de métricas | — | Permite al usuario consultar indicadores clave de producción y operación en tiempo real. Para utilizarlo, el usuario debe revisar los valores mostrados y comprobar el estado de cada métrica, identificando posibles datos faltantes o sistemas no conectados. |
| 9 | Contexto y preparación | Panel informativo | Enlace "Configurar vigilancia" | Permite al usuario consultar el estado de conexión de servicios y calidad de datos utilizados por Captia. Para utilizarlo, el usuario puede revisar la información técnica mostrada o pulsar “Configurar vigilancia” para modificar los elementos monitorizados por la plataforma. |
| 10 | Siguientes mejores acciones | Carrusel de tarjetas | Varía por tarjeta | Permite al usuario visualizar recomendaciones generadas por la IA ordenadas según prioridad. Para utilizarlo, el usuario puede navegar entre las tarjetas y seleccionar la acción recomendada que desea ejecutar o analizar. |
| 11 | Botón "?" (signo de interrogación) | CTA Secundario | Despliega panel en la misma vista | Permite al usuario consultar información técnica avanzada sobre el layout, reglas activas y configuración aplicada a la vista actual. Para utilizarlo, el usuario debe pulsar el botón “?” y revisar los parámetros mostrados en el panel desplegado. |
| 12 | Botón "Vista clásica" | CTA Secundario | Navega al dashboard principal | Permite al usuario acceder rápidamente al dashboard o SCADA principal configurado dentro de la plataforma. Para utilizarlo, el usuario debe pulsar el botón “Vista clásica”. Si no existe un panel principal configurado, se mostrará la pantalla de configuración correspondiente. |


## 💡 Guía de uso 

La página de inicio es tu centro de control al comenzar cada turno. En cuanto accedas, la IA analizará automáticamente el estado de la instalación y te mostrará un resumen con las alarmas activas, tareas vencidas y la acción más urgente a tomar. Desde el Radar de atención y el Manufacturing Signal Board podrás ver de un vistazo qué dominios e indicadores requieren tu atención, identificando fácilmente qué tiene datos disponibles y qué está pendiente de conexión. Si necesitas profundizar, las tarjetas de "Siguientes mejores acciones" te guiarán paso a paso hacia la siguiente tarea prioritaria, ya sea preparando un informe, navegando a una sección o lanzando un análisis con Copilot.

 [📚 Índice](../README.md) · [Siguiente →](./barra_superior.md)
