# ChatBot-Repository

TPI for OE - Organización Empresarial - UTN

## Descripción

Chatbot desarrollado en Python que automatiza el proceso de solicitud de vacaciones dentro de una empresa. Permite que un empleado se registre, consulte su saldo disponible y solicite vacaciones mediante una conversación por consola, validando la información ingresada y actualizando los días disponibles de forma automática.

## Objetivo

Automatizar un proceso administrativo que normalmente se realiza de forma manual, reduciendo tiempos de gestión y minimizando errores humanos.

## Tecnologías utilizadas

- Python 3
- CSV como base de datos simulada
- GitHub para control de versiones

## Archivos del proyecto

**Chat.py** — Contiene toda la lógica del chatbot.

**vacacionesDB.csv** — Base de datos simulada de empleados. Campos: `dni`, `nombre`, `dias_disponibles`.

**solicitudes_log.csv** — Registro histórico de solicitudes realizadas (se genera automáticamente en modo append).

## Funcionalidades

- Registro de nuevos empleados (DNI + nombre).
- Validación de DNI (formato y duplicados).
- Consulta de días disponibles.
- Solicitud de vacaciones con validación de fechas.
- Verificación de saldo disponible.
- Registro de solicitudes aprobadas y rechazadas.
- Actualización automática del saldo.
- Creación automática de la base de datos si no existe.

## Ejecución

1. Abrir una terminal.
2. Ubicarse en la carpeta del proyecto.
3. Ejecutar:

python Chat.py

Flujo General

1. El usuario escribe "vacaciones".
2. El sistema solicita el número de DNI.
3. El sistema verifica la existencia del empleado.
4. Se solicitan fechas de inicio y fin.
5. El sistema calcula los días solicitados.
6. Se valida el saldo disponible.
7. La solicitud es aprobada o rechazada.
8. Se registra la operación.

Autor

Ezequiel Gómez

Trabajo Práctico Integrador

Organización Empresarial

Tecnicatura Universitaria en Programación a Distancia# ChatBot-Repository
TPI for OE - Programacion I - UTN
