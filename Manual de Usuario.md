# Manual de Usuario — Chatbot de Vacaciones

1. Ejecutar el programa: `python Chat.py`
2. Elegir una opción del menú:
   - **1.** Registrarse
   - **2.** Pedir vacaciones
   - **3.** Salir
3. Si elige **Registrarse**: ingresar nombre completo y DNI (7 u 8 dígitos, sin puntos). El sistema asigna automáticamente 14 días iniciales de vacaciones.
4. Si elige **Pedir vacaciones**: ingresar el nombre completo registrado, luego la fecha de inicio y la fecha de fin en formato `DD/MM/AAAA`.
5. El sistema informa el saldo disponible antes de procesar la solicitud, y responde con el estado final:
   - **Aprobada**: indica fechas y saldo restante.
   - **Rechazada**: indica el motivo (saldo insuficiente).
6. Para finalizar la sesión, seleccionar la opción **3** (Salir).
