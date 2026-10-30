# Checkpoint 4 - Automatización n8n

Automatización integrada que procesa correos entrantes mediante un Agente de IA y gestiona notificaciones en Slack.

## Estructura del flujo
- **Trigger de Gmail:** Captura los correos entrantes.
- **IF de validación:** Filtra y previene auto-respuestas.
- **Consulta CRM:** Búsqueda y validación de datos del cliente.
- **Nodo de Limpieza:** Formateo y saneamiento de variables.
- **Creación de Borrador:** Generación de respuesta automática mediante IA con integración a Slack.

## Credenciales y OAuth2
El flujo utiliza autenticación OAuth2 configurada correctamente para los servicios de Google y Slack.
