# 🖥️ Página de inicio

**Objetivo principal:** Permite al operario obtener de un vistazo el estado actual de la planta, identificar tareas y alarmas prioritarias y acceder a la siguiente acción recomendada por la IA.

## 📸 Mapeo de interfaz

<img width="1920" height="944" alt="Texto (1)" src="https://github.com/user-attachments/assets/f805a0ad-1592-4f61-9ff0-e688b355d44b" />


## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Lectura AI de la instalación | Bloque informativo | — | Resume el estado de la instalación con lenguaje natural. Indica alarmas activas y tareas vencidas del turno actual, junto con el nivel de confianza del análisis en porcentaje. |
| 2 | Citas numeradas [1][2] / "Ver fuentes" | Enlace | Despliega panel "Fuentes consultadas" | Permite consultar las fuentes de datos utilizadas por la IA. [1] muestra las alarmas activas por prioridad (P1/P2) y [2] el estado de las tareas (vencidas, que vencen hoy y total). Accesible desde las citas numeradas o desde el enlace "Ver fuentes (2)". |
| 3 | Siguiente mejor acción | Bloque informativo | — | Muestra la acción prioritaria recomendada por la IA para el turno actual, acompañada de una descripción breve de su impacto esperado en producción, calidad, mantenimiento y energía. |
| 4 | Botón "Por qué veo esto" | CTA Secundario | Despliega panel en la misma vista | Muestra los parámetros aplicados por la IA para generar el briefing: severity_pill, narrative_mode, kpis, watchlist, reasons y tenant_inventory. Orientado a perfiles técnicos; el formato actual no está adaptado para el usuario final. |
| 5 | Botón "Revisar tareas vencidas" | CTA Principal | Abre panel lateral "Copiloto CAPTIA" | Abre el Copiloto CAPTIA con el contexto de la acción precargado. El asistente muestra directamente las razones detectadas (tareas vencidas y alarmas sin reconocer) y el foco prioritario, sin necesidad de introducir ninguna instrucción manual. |
| 6 | Botón "Analizar con Copilot" | CTA Principal | Abre análisis IA | Lanza el Copiloto CAPTIA en modo abierto para analizar el estado actual de la instalación. A diferencia del botón anterior, permite al usuario guiar el análisis con sus propias preguntas. |
| 7 | Radar de atención | Panel informativo | — | Muestra el estado de 6 dominios clave de la instalación: Safety, Quality, Energy, Production, Maintenance y Data Health. Cada dominio indica su nivel de prioridad (BASE, MEDIA o ALTA). Los dominios sin origen de datos conectado muestran "s/d". |
| 8 | Manufacturing Signal Board | Tabla de métricas | — | Presenta 9 indicadores clave con su valor en tiempo real. Los estados posibles son: valor numérico, "s/d" (sin datos disponibles) o "Sin MES" (sistema de gestión de producción no conectado). El contador "5 s/d" refleja cuántos indicadores están actualmente sin datos. |
| 9 | Contexto y preparación | Panel informativo | Enlace "Configurar vigilancia" | Detalla los servicios conectados (API Backend, Firebase, Dashboard Adapter), la calidad de los datos disponibles y los gaps pendientes de conexión. Incluye el enlace "Configurar vigilancia" para ajustar qué monitoriza Captia. |
| 10 | Siguientes mejores acciones | Carrusel de tarjetas | Varía por tarjeta | Presenta hasta 10 acciones recomendadas por la IA, ordenadas por prioridad. Cada tarjeta especifica el tipo de acción (PREPARAR, NAVEGAR o ANALIZAR), el nivel de prioridad (Alta, Media o Baja) y el motor de ejecución (Copilot o Navega). El contador "4 de 10" indica el total de acciones disponibles. |
| 11 | Botón "?" (signo de interrogación) | CTA Secundario | Despliega panel en la misma vista | Muestra información técnica del layout actual: modo de operación, plantilla y rol aplicados (generic_home / ADMIN_TENANT), reglas activas (R3, events count), boosts activos (ordenación de KPIs) y origen del cálculo con timestamp. Orientado a perfiles técnicos y soporte. |
| 12 | Botón "Vista clásica" | CTA Secundario | Navega al dashboard principal | Redirige al dashboard marcado como principal por el usuario. Si ningún dashboard o vista SCADA está marcado como principal, muestra una pantalla de configuración con el mensaje "Configura tu panel de inicio" y el botón "Seleccionar contenido de inicio". |


## 💡 Guía de uso 

La página de inicio es tu centro de control al comenzar cada turno. En cuanto accedas, la IA analizará automáticamente el estado de la instalación y te mostrará un resumen con las alarmas activas, tareas vencidas y la acción más urgente a tomar. Desde el Radar de atención y el Manufacturing Signal Board podrás ver de un vistazo qué dominios e indicadores requieren tu atención, identificando fácilmente qué tiene datos disponibles y qué está pendiente de conexión. Si necesitas profundizar, las tarjetas de "Siguientes mejores acciones" te guiarán paso a paso hacia la siguiente tarea prioritaria, ya sea preparando un informe, navegando a una sección o lanzando un análisis con Copilot.
