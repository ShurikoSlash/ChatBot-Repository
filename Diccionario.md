# Diccionario de Datos — Chatbot de Vacaciones

| Variable | Tipo | Descripción |
|---|---|---|
| dni | string (7-8 dígitos) | Documento Nacional de Identidad del empleado; clave de búsqueda en el registro. |
| nombre | string | Nombre completo del empleado. |
| fecha_inicio | date (DD/MM/AAAA) | Fecha inicial del período de vacaciones solicitado. |
| fecha_fin | date (DD/MM/AAAA) | Fecha final del período de vacaciones solicitado. |
| dias_disponibles / saldo | int | Días de vacaciones disponibles para el empleado. |
| dias_solicitados | int | Cantidad de días calculados entre fecha_inicio y fecha_fin (inclusive). |
| estado | string | Resultado de la solicitud: "Aprobada" o "Rechazada". |
