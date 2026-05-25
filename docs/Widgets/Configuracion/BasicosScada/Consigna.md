# 🎚️ Consigna · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **Consigna**, utilizado para visualizar y modificar valores directamente desde dashboards y pantallas SCADA mediante interacción del operador.

---

# 📸 Mapeo de Interfaz

<img width="1077" height="611" alt="image" src="https://github.com/user-attachments/assets/2936efb7-f769-4de1-a481-6de17369ae64" />


---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Sección "Elemento" | Configuración del widget | Gestiona el estado del widget | Permite visualizar el tipo de widget seleccionado y bloquearlo para evitar moverlo accidentalmente dentro del dashboard o SCADA. Para utilizarlo, el usuario debe pulsar “Bloquear” cuando quiera fijar definitivamente su posición. |
| 2 | Sección "Capas" | Organización visual | Gestiona superposición | Permite controlar cómo se posiciona la Consigna respecto a otros widgets del canvas. Para utilizarlo, el usuario puede modificar el Z-Index manualmente o utilizar “Traer al frente” y “Enviar atrás”. |
| 3 | Sección "General" | Configuración básica | Personaliza el widget | Permite modificar el título y comportamiento general de la Consigna. Para utilizarlo, el usuario puede escribir un nombre personalizado, activar “Mostrar título” o habilitar el botón de tendencia. |
| 4 | Sección "Asignación" | Configuración de datos | Configura lectura y escritura | Permite seleccionar las variables utilizadas por la Consigna tanto para lectura como para escritura. Para utilizarlo, el usuario debe pulsar “Cambiar” y seleccionar las señales deseadas. También permite configurar el modo de confirmación. |
| 5 | Sección "Formato" | Configuración visual | Ajusta visualización de valores | Permite configurar cómo se mostrará el valor dentro del widget. Para utilizarlo, el usuario puede definir unidades, número de decimales, alineación y activar la visualización del último valor confirmado. |
| 6 | Sección "Validación" | Configuración de límites | Configura restricciones | Permite establecer límites mínimos, máximos y pasos permitidos para los valores introducidos. Para utilizarlo, el usuario debe rellenar los campos deseados y definir el comportamiento fuera de rango. |
| 7 | Sección "Confirmación" | Configuración de seguridad | Ajusta confirmaciones | Permite definir el tiempo de espera y tolerancia de confirmación tras enviar una nueva consigna. Para utilizarlo, el usuario debe introducir los valores de timeout y tolerancia deseados. |
| 8 | Sección "Tipografía" | Configuración visual | Modifica estilos de texto | Permite ajustar tamaños, colores y peso tipográfico del contenido mostrado por la Consigna. Para utilizarlo, el usuario debe mover los sliders o seleccionar el estilo visual deseado. |
| 9 | Sección "Estilo" | Configuración visual | Personaliza apariencia | Permite modificar el color de fondo, bordes y grosor visual del widget. Para utilizarlo, el usuario debe seleccionar colores y ajustar los parámetros visuales disponibles. |
| 10 | Sección "Logs" | Configuración de registros | Gestiona visualización de logs | Permite mostrar el historial de cambios realizados sobre la Consigna. Para utilizarlo, el usuario puede activar “Mostrar botón Logs”, definir límites y habilitar actualización automática. |
| 11 | Sección "Editor" | Configuración del canvas | Ajusta comportamiento de edición | Permite activar el ajuste automático a cuadrícula mientras se mueve la Consigna dentro del canvas. Para utilizarlo, el usuario debe activar “Snap a cuadrícula”. |
| 12 | Sección "Acciones" | Gestión del widget | Elimina el widget | Permite eliminar la Consigna del dashboard o pantalla SCADA. Para utilizarlo, el usuario debe seleccionar el widget y pulsar “Eliminar elemento”. |

---

# 💡 Guía de Uso

El widget **Consigna** está diseñado para permitir al operador visualizar y modificar valores directamente desde la interfaz SCADA o dashboard.

Se utiliza principalmente para:

- Ajustar parámetros de operación
- Modificar consignas de producción
- Cambiar valores configurables
- Controlar procesos manualmente
- Introducir valores supervisados
- Gestionar parámetros dinámicos

## ✅ Cómo configurar correctamente la Consigna

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard o SCADA.
3. Desde el panel de propiedades:
   - Configura variables de lectura y escritura.
   - Ajusta límites y validaciones.
   - Configura formato visual y tipografía.
   - Personaliza colores y estilos.
   - Define opciones de confirmación y logs.
4. Guarda los cambios realizados.

---

[← Volver a Widgets SCADA Básicos](../widgetsScada_basicos.md)
