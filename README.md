# PreEntregaCoder

Monitoreo de Temperatura - Bahía Blanca

Trigger: Ejecución automática programada cada 60 minutos.

API: Obtención de datos reales de clima vía HTTP Request (Open-Meteo).

Mapeo: Nodo "Organizar Datos" para filtrar y normalizar variables.

Condicional: Evalúa si la temperatura ambiente supera los 26°C.

Rama True: Envía una alerta por Gmail ante picos de calor detectados.

Rama False: Informa estado normal/fresco y procesa logs de control.

Manejo de Datos: Uso de expresiones dinámicas para reportes precisos.

Objetivo: Automatizar el seguimiento del clima local de forma eficiente.
