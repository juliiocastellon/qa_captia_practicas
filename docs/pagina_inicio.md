# 🖥️ Página de inicio

**Objetivo principal:** Permite al operario obtener de un vistazo el estado actual de la planta, identificar tareas y alarmas prioritarias y acceder a la siguiente acción recomendada por la IA.

## 📸 Mapeo de interfaz

<img width="1677" height="938" alt="image" src="https://github.com/user-attachments/assets/7e2ce1a8-008e-4d5f-85d4-4caa07d8d27c" />

## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Lectura AI de la instalación | Bloque informativo | — | Es lo primero que verás al entrar. La IA analiza automáticamente el estado de la instalación y te lo resume en lenguaje natural: qué alarmas hay activas, cuántas tareas están vencidas y cuál es el nivel de confianza del análisis. |
| 2 | Citas numeradas [1][2] / "Ver fuentes" | Enlace | Despliega panel "Fuentes consultadas" | ¿De dónde saca la IA esa información? Haz clic en cualquiera de las citas numeradas o en "Ver fuentes" para verlo. [1] muestra las alarmas activas (con prioridad P1/P2) y [2] las tareas vencidas y su estado. |
| 3 | Siguiente mejor acción | Bloque informativo | — | Justo debajo del resumen, la IA te sugiere cuál debería ser tu próximo paso y por qué. Es una recomendación, no una obligación, pero está ordenada por impacto en producción, calidad, mantenimiento y energía. |
| 4 | Botón "Por qué veo esto" | CTA Secundario | Despliega panel en la misma vista | Si quieres entender qué criterios ha usado la IA para generar el resumen, este botón los muestra. Ten en cuenta que actualmente los parámetros se muestran en formato técnico (severity_pill, narrative_mode, kpis, etc.), por lo que está orientado principalmente a perfiles técnicos. |
| 5 | Botón "Revisar tareas vencidas" | CTA Principal | Abre panel lateral "Copiloto CAPTIA" | Abre el Copiloto CAPTIA en un panel lateral con el contexto ya cargado. No necesitas escribir nada: el asistente ya sabe qué tareas están vencidas y qué alarmas hay sin reconocer y te muestra un análisis directo. |
| 6 | Botón "Analizar con Copilot" | CTA Principal | Abre análisis IA | Abre el Copiloto CAPTIA para hacer un análisis más abierto del estado actual de la instalación. A diferencia del botón anterior, aquí puedes guiar tú la conversación con tus propias preguntas. |
| 7 | Radar de atención | Panel informativo | — | Un panel visual que agrupa el estado de la instalación en 6 grandes áreas: Safety, Quality, Energy, Production, Maintenance y Data Health. Cada una muestra su nivel de prioridad (BASE, MEDIA o ALTA). Si aparece "s/d" significa que ese origen de datos aún no está conectado. |
| 8 | Manufacturing Signal Board | Tabla de métricas | — | Una tabla con 9 indicadores clave de la instalación en tiempo real. Los valores pueden ser numéricos, "s/d" (sin datos disponibles) o "Sin MES" (el sistema de gestión de producción no está conectado). El contador "5 s/d" te indica cuántos indicadores están actualmente sin datos. |
| 9 | Contexto y preparación | Panel informativo | Enlace "Configurar vigilancia" | Te muestra qué servicios tiene conectados la IA (API Backend, Firebase, Dashboard Adapter), la calidad de los datos disponibles y qué falta por conectar para mejorar el análisis. Desde aquí también puedes ajustar qué vigila Captia con el enlace "Configurar vigilancia". |
| 10 | Siguientes mejores acciones | Carrusel de tarjetas | Varía por tarjeta | Un carrusel con hasta 10 acciones concretas que la IA recomienda para este turno. Cada tarjeta indica qué tipo de acción es (PREPARAR, NAVEGAR o ANALIZAR), su prioridad (Alta, Media o Baja) y si se ejecuta con Copilot o navegando directamente a una sección. El contador "4 de 10" te indica cuántas acciones hay disponibles en total. |

## 💡 Guía de uso 

La página de inicio es tu centro de control al comenzar cada turno. En cuanto accedas, la IA analizará automáticamente el estado de la instalación y te mostrará un resumen con las alarmas activas, tareas vencidas y la acción más urgente a tomar. Desde el Radar de atención y el Manufacturing Signal Board podrás ver de un vistazo qué dominios e indicadores requieren tu atención, identificando fácilmente qué tiene datos disponibles y qué está pendiente de conexión. Si necesitas profundizar, las tarjetas de "Siguientes mejores acciones" te guiarán paso a paso hacia la siguiente tarea prioritaria, ya sea preparando un informe, navegando a una sección o lanzando un análisis con Copilot.
