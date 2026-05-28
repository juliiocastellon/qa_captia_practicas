# 🖥️ Triggers

**Objetivo Principal:** Permite al usuario seleccionar y configurar el tipo de evento que inicia la ejecución automática de un workflow.

## 📸 Mapeo de Interfaz

<img width="504" height="593" alt="Captura de pantalla 2026-05-27 084518" src="https://github.com/user-attachments/assets/49ddfb77-4cf3-4d59-8b19-bf5599041d66" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Configuración | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Sección "Triggers" (cabecera) | Contenedor / Acordeón | Expande/colapsa la lista de triggers disponibles | - | Agrupa los 4 tipos de triggers disponibles bajo un único bloque colapsable. Muestra el contador de items (4). |
| 1.1 | Trigger manual | Opción seleccionable | Configura el workflow para ejecución manual |  [Configuración](./Configuración/trigger_manual.md) | Permite lanzar el workflow de forma manual bajo demanda, sin automatización. |
| 1.2 | Trigger programado | Opción seleccionable | Abre configuración de cron/horario |  [Configuración](./Configuración/trigger_programado.md) | Ejecuta el workflow de forma recurrente según una expresión cron o franjas horarias definidas. |
| 1.3 | Trigger por umbral | Opción seleccionable | Abre configuración de variable y valor límite |  [Configuración](./Configuración/trigger_por_umbral.md) | Dispara el workflow cuando una variable monitorizada supera un valor umbral definido. |
| 1.4 | Trigger por consigna | Opción seleccionable | Abre configuración de señal SCADA |  [Configuración](./Configuración/trigger_por_consigna.md) | Activa el workflow cuando el sistema SCADA modifica una consigna o setpoint específico. |

## 💡 Guía de Uso

1. Accede a la sección **Triggers** dentro del editor de workflow.
2. Selecciona el tipo de trigger que mejor se adapta a tu caso de uso:
   - **Manual**: cuando quieras ejecutar el workflow puntualmente desde la interfaz.
   - **Programado**: cuando necesites ejecuciones periódicas (cada hora, cada día, etc.).
   - **Por umbral**: cuando la lógica dependa de que una variable supere un valor determinado.
   - **Por consigna**: cuando el disparo deba estar vinculado a un cambio de setpoint en SCADA.
3. Una vez seleccionado, configura los parámetros específicos del trigger elegido.
4. Puedes reordenar los triggers arrastrando el icono de puntos (⠿) a la izquierda de cada item.




[← Volver a Nodos del Workflow](./nodos.md)
