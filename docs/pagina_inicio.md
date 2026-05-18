# Página de inicio

## Objetivo principal
Permite al operario obtener de un vistazo el estado actual de la planta, identificar tareas y alarmas prioritarias y acceder a la siguiente acción recomendada por la IA.

## 📸 Mapeo de interfaz
<img width="1918" height="907" alt="image" src="https://github.com/user-attachments/assets/d1598a7b-dda0-47f8-9ff0-2b9f70e62062" />

## 🧩 Despiece de elementos funcionales

| Sección | Descripción | Observaciones QA |
|---|---|---|
| Saludo y turno | Muestra el nombre del usuario, turno activo (mañana), fecha y última lectura. Indica tareas pendientes en rojo | "4 tareas" actúa como enlace o alerta |
| Lectura AI de planta | Bloque principal de IA que resume el estado de la planta con lenguaje natural. Muestra alarmas activas, tareas vencidas y confianza del análisis | Incluye badges: REVISADO, PENDIENTE, CONFIANZA. Citas numeradas [1][2] con fuentes. Botón "Por qué veo esto" |
| Siguiente mejor acción | Sugiere la acción prioritaria ("Revisar tareas vencidas") con descripción breve del impacto | Dos CTAs: "Revisar tareas vencidas" y "Analizar con Copilot" |
| Radar de atención | Panel derecho con 6 dominios industriales (Safety, Quality, Energy, Production, Maintenance, Data Health) con prioridad, estado y nivel (BASE/MEDIA) | Sin datos muestra "s/d". Etiqueta global "PREVENTIVO" en naranja |
| Manufacturing Signal Board | Tabla con 9 métricas clave: Producción, OEE, Alarmas activas, Tareas GMAO, Calidad, Energía, Paradas, Cuello botella, Cambios | Estados: "Sin MES", "s/d", valores numéricos. Badge "0 críticos = control" y contador "5 s/d" |
| Siguientes mejores acciones | Carrusel de tarjetas de acción sugeridas por la IA con prioridad, tipo (PREPARAR/NAVEGAR/ANALIZAR) y descripción breve | Muestra 4 de 10 acciones disponibles ("4 de 10" visible en esquina). Cada tarjeta tiene nivel de prioridad (Alta/Media/Baja) y motor (Copilot/Navega) |
| Contexto y preparación | Servicios conectados, calidad de datos, qué vigila Captia y qué falta mejorar. Enlace "Configurar vigilancia" | Muestra 3 servicios activos con indicadores de color. Sección "Falta para mejorar" indica gaps de datos |
| Navegación lateral | Menú con etiquetas visibles: Inicio, SCADA, Dashboards, Informes, Automatizaciones, Tareas, Calendario, Alarmas, Variables, Auditoría, Cuenta | En la captura anterior los iconos aparecían sin etiquetas — con el menú expandido sí se ven. Verificar comportamiento en distintas resoluciones |
| Toggle ON (inferior izquierdo) | Botón verde "ON" en la parte inferior del sidebar. Versión v0.24 visible debajo | Función no documentada — verificar qué activa/desactiva |
| Barra superior | Logo, toggle Carrusel, indicador de conexión (verde), notificaciones, menú de usuario, accesos SCADA/GMAO/Dashboards, estado "OPERACION ESTABLE", botón "Vista clásica" | "Vista clásica" sugiere que existe una vista alternativa — verificar si está implementada |

## 💡 Guía de uso

### ¿Qué verás al entrar?
Al iniciar sesión llegarás directamente a la página de inicio. La plataforma detecta automáticamente tu turno activo y genera un resumen del estado de la planta basado en los datos disponibles en ese momento.

### Cómo leer la Lectura AI de planta
El bloque azul central es el resumen más importante de la página. La IA analiza alarmas, tareas y dashboards conectados y presenta:
- **El estado actual** en una frase directa ("Atención requerida ahora: 4 tareas vencidas")
- **Los badges** indican qué ha revisado la IA (REVISADO), qué está pendiente de datos (PENDIENTE) y el nivel de confianza (CONFIANZA alta/media/baja)
- **Las citas numeradas** [1][2] enlazan a las fuentes de datos usadas. Haz clic en "Ver fuentes" para consultarlas

### Cómo usar el Radar de atención
Muestra 6 dominios industriales ordenados por prioridad. Cada dominio indica:
- Un valor numérico si hay datos disponibles
- **s/d** si el origen de datos no está conectado
- Nivel de prioridad: BASE (normal), MEDIA (requiere atención), ALTA (acción inmediata)

### Cómo usar el Manufacturing Signal Board
Tabla de señales de producción con 9 métricas. Estados posibles:
- **Sin MES** — el sistema MES no está conectado
- **s/d** — sin datos disponibles
- Un número — valor actual de la métrica
- Etiquetas de color (pendiente, atención, revisar, alta, base) indican urgencia
- El badge **"5 s/d"** indica cuántas métricas están sin datos en ese momento

### Cómo usar las Siguientes mejores acciones
Carrusel en la parte inferior con hasta 10 acciones sugeridas por la IA. Cada tarjeta muestra:
- **Tipo de acción**: PREPARAR, NAVEGAR o ANALIZAR
- **Prioridad**: Alta, Media o Baja
- **Motor**: Copilot (análisis IA) o Navega (redirección a sección)
- Una descripción breve de lo que hace la acción
- Usa las flechas del carrusel para ver las 10 acciones disponibles

### Acciones disponibles desde esta página
- **Revisar tareas vencidas** — abre el listado de tareas que han superado su fecha límite
- **Analizar con Copilot** — lanza un análisis asistido por IA sobre el estado actual
- **Por qué veo esto** — explica qué datos y reglas ha usado la IA para generar el resumen
- **Configurar vigilancia** — permite ajustar qué alarmas, tareas y dashboards monitoriza Captia

## ⚠️ Limitaciones conocidas
- Los dominios sin origen de datos conectado (MES, scrap, consumo energético) muestran "s/d" y no generan recomendaciones
- El toggle "Carrusel" de la barra superior rota automáticamente entre dashboards; desactívalo si prefieres navegación manual
- El botón "Vista clásica" aparece en la barra superior pero su funcionalidad está pendiente de verificar
- El botón verde "ON" del sidebar inferior no tiene descripción visible de su función
- La navegación lateral puede mostrar solo iconos sin etiquetas en resoluciones reducidas
